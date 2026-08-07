# PokéStarters — Versão Table-Based Layout

Este projeto é uma adaptação do PokéStarters (originalmente construído com HTML
semântico e Bootstrap) para a técnica antiga de **table-based layout**, muito
usada para estruturar páginas inteiras entre o final dos anos 90 e meados dos
anos 2000, antes da consolidação do CSS para essa finalidade.

## Por que table-based layout é uma técnica antiga

Antes do CSS ganhar suporte confiável de posicionamento (`float`, e mais tarde
`flexbox` e `grid`), o `<table>` era praticamente a única ferramenta capaz de
alinhar elementos lado a lado, criar colunas e controlar espaçamentos de forma
previsível entre navegadores. Desenvolvedores passaram a usar tabelas não para
exibir dados tabulares — seu propósito original —, mas para montar toda a
estrutura visual da página: cabeçalho, menu, colunas de conteúdo e rodapé
viravam `<tr>` e `<td>` aninhados.

Essa técnica caiu em desuso pelos seguintes motivos:

- **Uso incorreto da semântica HTML**: tabelas foram criadas para dados
  tabulares (linhas e colunas relacionadas), não para leiaute. Usá-las como
  esqueleto da página quebra o significado do documento.
- **Acessibilidade prejudicada**: leitores de tela interpretam `<table>` como
  dado tabular. Uma página inteira dentro de tabelas aninhadas confunde a
  navegação de quem depende de tecnologia assistiva.
- **Código difícil de manter**: cada ajuste visual exige mexer na estrutura
  do HTML (aninhar mais tabelas, adicionar `<td>`), em vez de apenas alterar
  o CSS. HTML e apresentação ficam misturados.
- **Peso e rigidez**: tabelas aninhadas geram HTML muito mais pesado e menos
  flexível para responsividade — o navegador só renderiza a tabela depois de
  calcular a estrutura inteira, o que também piora a performance percebida.
- **SEO prejudicado**: motores de busca têm mais dificuldade de entender a
  hierarquia e a importância do conteúdo quando ele está espalhado em células
  de tabela em vez de tags semânticas (`<header>`, `<nav>`, `<main>` etc.).

Com a chegada do CSS2/CSS3 e, mais tarde, do Flexbox e do Grid, o layout por
tabelas se tornou desnecessário e é hoje considerado uma má prática.

## Dificuldades encontradas na adaptação

- **Perder a semântica**: o projeto original usava `<header>`, `<nav>`,
  `<main>`, `<section>` e `<footer>`, que já indicam sozinhos o papel de cada
  bloco. Ao converter tudo para `<table>`/`<tr>`/`<td>`, essa informação se
  perde e passa a depender só de comentários no código (`<!-- CABEÇALHO -->`,
  `<!-- RODAPÉ -->`) para continuar legível.
- **Âncoras de navegação**: os links do menu (`#home`, `#pokemons`, `#sobre`)
  usavam `id` nos elementos semânticos. Como tabela não tem um "container"
  natural para isso, foi preciso recriar os alvos com `<a name="...">`, técnica
  típica da época, já que nem todo navegador antigo suportava saltar para
  qualquer `id` de forma confiável.
- **Lista de Pokémon**: no HTML original, os `<img>` ficavam soltos como
  irmãos dos `<li>`, fora da lista de fato — um aninhamento inválido. Isso não
  existe em tabela: cada Pokémon virou uma linha `<tr>` com duas colunas
  (nome e imagem), o que aliás corrigiu esse problema de estrutura.
- **Formulário dentro de tabela**: alinhar rótulo (`<label>`) e campo lado a
  lado exigiu colocar o `<form>` inteiro dentro de uma célula e usar uma
  tabela auxiliar para cada par label/input — o padrão clássico de formulários
  "antigos". Percebi também que o campo de e-mail no original reaproveitava o
  `id="nome"` do campo de nome; corrigi para `id="email"` durante a adaptação.
- **Responsividade praticamente inexistente**: como as larguras são definidas
  em atributos HTML (`width="500"`) e não em CSS, a página não se adapta bem
  a telas menores — outro motivo pelo qual essa técnica não se sustenta hoje.

## Comparação com a estrutura semântica moderna

| Aspecto | Table-based layout | HTML semântico + CSS |
|---|---|---|
| Estrutura | `<table>`, `<tr>`, `<td>` para tudo | `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` |
| Estilo/posicionamento | Atributos HTML (`width`, `align`, `cellpadding`) | CSS (`flexbox`, `grid`, classes) |
| Acessibilidade | Ruim — leitor de tela interpreta como dado tabular | Boa — cada tag comunica seu papel |
| SEO | Prejudicado — hierarquia pouco clara | Favorecido — motores de busca entendem a estrutura |
| Manutenção | Baixa — leiaute preso ao HTML | Alta — leiaute isolado no CSS |
| Responsividade | Praticamente inexistente | Nativa, via media queries/flex/grid |
| Uso de `<table>` | Para leiaute (uso indevido) | Reservado a dados tabulares de verdade |

Em resumo: a versão semântica separa **conteúdo** (HTML) de **apresentação**
(CSS), o que é exatamente o princípio que a técnica de tabelas viola. A versão
table-based só faz sentido hoje como exercício histórico — para entender por
que o CSS moderno existe e por que ele resolveu um problema real.
