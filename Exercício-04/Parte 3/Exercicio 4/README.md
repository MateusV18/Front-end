# Exercício 4 - TechStore (Parte 3: Galeria de Produtos com Cards)

## O que foi feito nesta etapa

- `produtos.html` transformado em galeria com **5 produtos cadastrados**:
  Teclado Mecânico Aurora, Mouse Gamer Pulse, Headset Studio Lite,
  Monitor 24 Vision e Mochila TechPack.
- Cada card contém: nome do produto, descrição curta, preço imaginário e
  botão "Ver Detalhes" apontando para a página de detalhe correspondente.
- Galeria organizada com `display: flex` e `flex-wrap: wrap` na classe
  `.products-grid`, permitindo que os cards quebrem para a próxima linha
  automaticamente.
- Criados os arquivos `produto-teclado.html`, `produto-mouse.html`,
  `produto-headset.html`, `produto-monitor.html` e `produto-mochila.html`
  (ainda como esqueleto, para evitar links quebrados — o conteúdo completo
  será adicionado na Parte 4).

## Respostas das questões teóricas

- Principal função de um card de produto: reunir informações essenciais do
  produto de forma visual e clicável.
- Combinação para os cards quebrarem para a próxima linha com Flexbox:
  `display: flex` e `flex-wrap: wrap`.
- Informação que não deve faltar em um card: nome do produto e valor
  imaginário.
- Seletor CSS usado para estilizar todos os cards com a mesma classe:
  `.card-produto`.
- Por que cada produto deve ter link de detalhes: para permitir que o
  usuário clique no card e veja a descrição mais completa do produto.

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
