# Exercício 4 — Layout com Flexbox: Loja de Produtos (`TechStore`)

Este projeto consiste em uma loja virtual fictícia multipáginas desenvolvida como parte do **Exercício 4** da trilha de desenvolvimento frontend, estruturada dentro do repositório GitHub `frontend`, na pasta dedicada `Exercicio 4`.

## 📁 Estrutura de Pastas do Projeto

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

## 🛠️ Tecnologias e Padrões Técnicos Utilizados

1. **HTML5 Semântico**: Estruturação limpa de páginas (`header`, `main`, `footer`, `nav`, `section`, `article`).

1. **CSS Externo Obrigatório**: 100% da estilização visual, variáveis de cores, sistema de sombras e tipografia estão centralizados exclusivamente em `css/style.css`. Nenhum estilo *inline* ou tag `<style>` foi utilizada.

1. **Layout Flexbox e Grid**:
  - **Cabeçalho Flexbox**: Organizado com `display: flex`, `justify-content: space-between`, `align-items: center` e `gap`.
  - **Galeria Responsiva**: Organizada com grades flexíveis e `auto-fit` / `flex-wrap`.
  - **Páginas de Detalhes**: Layout em duas colunas utilizando Flexbox/Grid para separar áreas visuais e textuais.

1. **Efeitos de Hover Modernos**: Transições suaves (`transition: all 0.3s ease`) aplicadas em botões, links de navegação e cards de produtos (com efeito de elevação *translateY* e sombras dinâmicas).

1. **Responsividade Básica**: Adaptação fluida para dispositivos móveis através de *Media Queries*.

---

## 📄 Descrição das Páginas

- **`index.html`**: Página de boas-vindas com banner *Hero*, apresentação institucional da marca e chamada para ação (*Call to Action*) para explorar o catálogo.

- **`produtos.html`**: Galeria contendo 5 produtos cadastrados (*Teclado Mecânico Aurora*, *Mouse Gamer Pulse*, *Headset Studio Lite*, *Monitor 24 Vision* e *Mochila TechPack*), com nomes, descrições curtas, preços imaginários e botões direcionando para as páginas de detalhes.

- **Páginas de Detalhes (****`produto-*.html`****)**: Páginas individuais dedicadas a cada item, apresentando informações completas, listas de especificações técnicas e botão de interesse para contato.

- **`contato.html`**: Página de atendimento contendo dados fictícios e um formulário visual interativo com campos para Nome, E-mail e Mensagem.

---

Desenvolvido com foco em boas práticas de arquitetura frontend, reuso de código e manutenibilidade.