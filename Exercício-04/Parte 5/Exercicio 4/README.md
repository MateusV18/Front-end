# Exercício 4 — TechStore (Loja Fictícia Multipáginas)

Loja virtual fictícia multipáginas desenvolvida como parte do Exercício 4 da
trilha de desenvolvimento frontend, estruturada dentro do repositório GitHub
`frontend`, na pasta `Exercicio 4`.

## Descrição do projeto

A TechStore é uma pequena loja fictícia de periféricos e acessórios de
tecnologia, com página de boas-vindas, galeria de produtos, páginas de
descrição individuais (com valores imaginários) e página de contato com
formulário visual.

## Estrutura de pastas

```
frontend/
└── Exercicio 4/
    ├── css/
    │   └── style.css
    ├── img/
    ├── index.html
    ├── produtos.html
    ├── produto-teclado.html
    ├── produto-mouse.html
    ├── produto-headset.html
    ├── produto-monitor.html
    ├── produto-mochila.html
    ├── contato.html
    └── README.md
```

## Tecnologias utilizadas

- HTML5 semântico (`header`, `main`, `nav`, `section`, `footer`)
- CSS3 externo (`css/style.css`) — zero CSS inline, zero tag `<style>`
- Flexbox (cabeçalho, galeria de produtos, layout das páginas de detalhe)
- Transições e efeitos de `:hover`
- Media Queries para responsividade básica

## Descrição das páginas

- **`index.html`** — página de boas-vindas com seção *hero*, apresentação da
  marca e chamada para ação levando à galeria de produtos.
- **`produtos.html`** — galeria com os 5 produtos cadastrados (Teclado
  Mecânico Aurora, Mouse Gamer Pulse, Headset Studio Lite, Monitor 24
  Vision e Mochila TechPack), cada um com nome, descrição curta, preço
  imaginário e botão para a página de detalhes.
- **`produto-teclado.html`, `produto-mouse.html`, `produto-headset.html`,
  `produto-monitor.html`, `produto-mochila.html`** — páginas individuais de
  cada produto, com preço em destaque, descrição completa, lista de
  especificações técnicas e botão "Demonstrar Interesse".
- **`contato.html`** — informações fictícias de atendimento e formulário
  visual (Nome Completo, E-mail, Mensagem), sem envio real (`action="#"`).

## Destaques técnicos desta etapa (refinamento final)

- Efeitos de `:hover` no menu (mudança de cor, fundo levemente colorido e
  borda inferior de destaque), nos botões (`.btn`, com elevação via
  `transform: translateY(-2px)` e sombra mais intensa) e nos cards de
  produto (elevação com `translateY(-6px)`, sombra mais forte e mudança de
  cor da borda).
- `transition: all 0.3s ease` aplicada nos elementos com hover para suavizar
  as animações.
- Media query em `768px` para empilhar o menu e o layout das páginas de
  detalhe em telas menores.

## Checklist final

- [x] Página de boas-vindas em `index.html` com chamada para ação
- [x] Galeria com 5 produtos em `produtos.html`
- [x] Cada card leva para uma página de descrição do produto
- [x] Cada produto possui valor imaginário
- [x] `contato.html` criada com formulário visual
- [x] Menu presente em todas as páginas
- [x] Layout com Flexbox no cabeçalho e na galeria
- [x] Cards organizados em grade visual
- [x] Hover aplicado em menu, botões e cards
- [x] CSS externo exclusivamente em `css/style.css` (zero inline, zero tag `style`)
- [x] README atualizado com descrição, estrutura e tecnologias

## Como visualizar o projeto

Abra o arquivo `index.html` em qualquer navegador, ou publique a pasta
`Exercicio 4` via GitHub Pages.
