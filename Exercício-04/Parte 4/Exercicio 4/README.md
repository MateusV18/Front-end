# Exercício 4 - TechStore (Parte 4: Páginas de Detalhe e Contato)

## O que foi feito nesta etapa

- Criadas as 5 páginas de detalhe de produto (`produto-teclado.html`,
  `produto-mouse.html`, `produto-headset.html`, `produto-monitor.html`,
  `produto-mochila.html`), cada uma com:
  - Nome do produto (`h1`);
  - Preço imaginário com destaque visual (`.preco-destaque`);
  - Descrição completa do produto;
  - Lista de especificações técnicas;
  - Botão "Demonstrar Interesse" levando para `contato.html`.
- Layout em duas colunas nas páginas de detalhe usando Flexbox
  (`.detalhe-produto`): placeholder de imagem à esquerda, informações à
  direita.
- `contato.html` finalizada com informações fictícias da loja (endereço,
  e-mail e telefone) e formulário visual com campos Nome Completo, E-mail e
  Mensagem, usando `action="#"` (sem envio real).
- Continua sem nenhum CSS inline ou tag `<style>` — tudo centralizado em
  `css/style.css`.

## Respostas das questões teóricas

- Objetivo principal de uma página de detalhes: apresentar informações mais
  completas do item após o clique na galeria.
- O que precisa existir para evitar link quebrado com
  `href="produto-mouse.html"`: um arquivo chamado `produto-mouse.html` no
  caminho indicado.
- Campo adequado para formulário visual de contato: Mensagem.
- Classe que faz sentido para destacar o preço: `.preco-destaque`.
- Por que o formulário pode usar `action="#"`: porque o objetivo é criar a
  interface visual, sem backend de envio real.

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

## Como visualizar

Abra o arquivo `index.html` em qualquer navegador.
