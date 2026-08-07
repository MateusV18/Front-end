# Exercício 4 - TechStore (Parte 2: Cabeçalho Flexbox e Página de Boas-vindas)

## O que foi feito nesta etapa

- Cabeçalho transformado em navegação moderna com **Flexbox**:
  - `display: flex` no container do cabeçalho (`.nav-container`);
  - `justify-content: space-between` para separar logo e menu;
  - `align-items: center` para alinhamento vertical;
  - `gap: 1.5rem` entre os itens do menu.
- Seção *hero* criada em `index.html` com título, texto de apresentação da
  marca e botão de chamada para ação levando à galeria de produtos.
- Mesma estrutura de cabeçalho copiada para `index.html`, `produtos.html` e
  `contato.html`.
- Nenhum estilo inline ou tag `<style>` utilizada — tudo em `css/style.css`.

## Respostas das questões teóricas

- Propriedade que transforma um elemento em flex container: `display: flex`
- Propriedade para alinhar verticalmente os itens do cabeçalho: `align-items: center`
- Prática que melhora a manutenção do menu em um site multipáginas: criar um
  CSS externo compartilhado por todas as páginas.
- Elementos que são flex items quando `.topo` usa `display: flex`: a marca da
  loja (logo) e o `nav` do menu.
- Propriedade para espaço uniforme entre os links do menu: `gap`.

## Estrutura de pastas

```
frontend/
└── Exercicio 4/
    ├── css/
    │   └── style.css
    ├── img/
    ├── index.html
    ├── produtos.html
    ├── contato.html
    └── README.md
```

## Como visualizar

Abra o arquivo `index.html` em qualquer navegador.
