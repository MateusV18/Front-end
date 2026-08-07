# MercadoTech — Loja de Tecnologia e Institucional (Projeto Final)

Repositório oficial e final do projeto contínuo **MercadoTech**, desenvolvido para as atividades práticas de desenvolvimento web.

## 🏢 Sobre a Empresa e Objetivos

A **MercadoTech** é uma empresa imaginária focada na comercialização de produtos de tecnologia de ponta, incluindo computadores, periféricos, smartphones, acessórios gamer e soluções para automação residencial e corporativa. 

O objetivo da loja é oferecer uma experiência de compra intuitiva, moderna e responsiva, unindo um site de e-commerce ágil a uma seção institucional sólida que transmite confiança, inovação e suporte especializado aos nossos clientes.

---

## 📚 Conceitos Teóricos

### O que é um Framework CSS?

Um **Framework CSS** é um pacote pré-construído que contém uma biblioteca de arquivos CSS (e frequentemente componentes JavaScript) prontos para uso. Ele fornece uma estrutura padronizada, grade responsiva (*grid system*) e estilos base para elementos de interface (como botões, formulários, barras de navegação e cartões). O principal objetivo de um framework CSS é agilizar o desenvolvimento web frontend, garantindo consistência visual, design responsivo em diferentes tamanhos de tela e compatibilidade entre navegadores, sem que o desenvolvedor precise escrever todo o código do zero.

#### Exemplo além do Bootstrap: Tailwind CSS
O **Tailwind CSS** é um exemplo popular de framework CSS utilitário (*utility-first*). Diferente do Bootstrap (que fornece componentes prontos como botões e cards estilizados), o Tailwind fornece classes de utilidade de baixo nível (como `flex`, `pt-4`, `text-center`, `bg-blue-500`) que permitem construir designs customizados diretamente no HTML, compondo estilos personalizados de forma rápida e modular.

### Por que o Projeto utiliza Bootstrap?
O **Bootstrap** foi escolhido para o projeto **MercadoTech** por sua robustez, maturidade e facilidade de implementação através de CDN. Ele oferece um sistema de grades flexível e responsivo excelente para e-commerce, além de componentes prontos (como carrosséis, barras de navegação e modais) que aceleram a entrega de protótipos funcionais e profissionais, mantendo a padronização visual exigida.

---

## 🚀 Estrutura Completa de Páginas do Projeto

O projeto final possui cinco páginas principais totalmente integradas por uma navbar responsiva e pelo arquivo de estilos externo:

1. **`index.html`**: Página inicial (Home) com apresentação institucional, destaques de pilares e categorias de produtos.
2. **`produtos.html`**: Catálogo completo contendo **seis cards de produtos** de alta performance com preços e botões de compra.
3. **`sobre.html`**: Página institucional com a história da empresa, métricas de crescimento, missão, visão, valores e equipe de liderança.
4. **`contato.html`**: Página de atendimento com formulário completo e seletor de assuntos.
5. **`carrinho.html`**: Página simulando o carrinho de compras do e-commerce.

---

## 📱 Testes Responsivos e Ajustes do Mundo Real

Durante o desenvolvimento, foram realizados testes em diferentes larguras de tela:
- **Dispositivos Móveis (< 576px)**: Ajuste do sistema de grid para 1 coluna (`col-12`), garantindo que botões e textos não transbordem e que o menu mobile (hamburguer) funcione perfeitamente.
- **Tablets (768px - 992px)**: Utilização de colunas adaptativas (`col-md-6`), distribuindo os cards de forma equilibrada em duas colunas.
- **Desktops (> 992px)**: Distribuição em três colunas (`col-lg-4`), aproveitando o espaço horizontal com elegância e legibilidade.

---

## 🌐 Publicação no GitHub Pages

O projeto está pronto para publicação no **GitHub Pages**:
- **Instruções**:
  1. Acesse o repositório no GitHub.
  2. Vá em **Settings** > **Pages**.
  3. Em **Build and deployment**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
  4. Clique em **Save** e acesse o link gerado pelo GitHub Pages.

---

## 📁 Estrutura Final de Pastas

```text
mercadotech/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   └── images/
├── README.md
├── index.html
├── produtos.html
├── sobre.html
├── contato.html
└── carrinho.html
```

---

## 🛠️ Tecnologias Utilizadas & Autor
- **HTML5** | **CSS3** (Externo em `assets/css/style.css`) | **Bootstrap 5.3 (CDN)** | **Bootstrap Icons** | **Git / GitHub**
- **Desenvolvido por**: Aluno / Desenvolvedor MercadoTech
