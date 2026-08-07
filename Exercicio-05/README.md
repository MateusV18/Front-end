# Exercício 5 — Loja Virtual Responsiva "Verde Vida"

Este diretório contém o projeto completo da loja virtual responsiva **Verde Vida**, organizado em **5 partes evolutivas**. Cada pasta `Parte N` é um snapshot autocontido do projeto naquele estágio da evolução, contendo todos os arquivos necessários (HTML, CSS e pastas `css/` e `img/`) para ser aberto e testado isoladamente no navegador. A partir de `index.html` em qualquer pasta, o projeto funciona de forma independente.

## Evolução do projeto

| Parte | Pasta | Estágio do projeto | Principais conteúdos |
|-------|-------|--------------------|----------------------|
| Parte 1 | `Parte 1/` | Estrutura base e planejamento | Pastas criadas, 9 HTMLs base, `css/style.css` com variáveis CSS personalizadas, fonte Poppins e reset; README com nome da loja, tema, produtos com preços, estrutura e paleta de cores. |
| Parte 2 | `Parte 2/` | Home personalizada e portfólio inicial | Header com nome e slogan, navegação com 4 links, hero com CTA, seção de destaques com 3 cards em coluna única (mobile), rodapé; primeira versão do portfólio. |
| Parte 3 | `Parte 3/` | Galeria e páginas individuais | Galeria completa com os 5 produtos (nome, bloco visual, descrição, preço em R$ e "Ver detalhes"); 5 páginas de detalhe com descrição completa, preço em destaque, lista de 5 características e "Voltar à galeria"; CSS Grid na galeria (1 coluna mobile). |
| Parte 4 | `Parte 4/` | Menu responsivo e media queries | Menu responsivo sem JavaScript (checkbox + `:checked`) em todas as páginas; hambúrguer oculto a partir de 768px; media queries em 768px (2 colunas) e 1024px (3 colunas); layout lado a lado nos detalhes. |
| Parte 5 | `Parte 5/` | **Projeto final** | Portfólio finalizado com tecnologias e decisões de responsividade; formulário de contato completo (Nome, E-mail, Assunto, Mensagem); `:hover` e `:focus` com transições; revisão geral das 9 páginas e README completo. |

## Tema da loja

A **Verde Vida** é uma loja fictícia de **plantas e jardinagem** (slogan: "Cultive momentos, colha bem-estar."), com paleta em verde floresta (`#2e7d32`), verde escuro, verde claro e âmbar, e fonte Poppins.

## Produtos fictícios

| # | Produto | Preço |
|---|---------|-------|
| 1 | Monstera Deliciosa (Muda Grande) | R$ 129,90 |
| 2 | Kit Jardinagem Premium (10 peças) | R$ 89,90 |
| 3 | Vaso de Cerâmica Artesanal 20cm | R$ 59,90 |
| 4 | Substrato Orgânico Premium 5kg | R$ 34,90 |
| 5 | Lanterna de Jardim Solar LED | R$ 79,90 |

## Estrutura do diretório

```
frontend/
└── Exercicio 5/
    ├── README.md
    ├── Parte 1/   (estrutura base)
    │   ├── css/style.css
    │   ├── img/
    │   └── 9 HTMLs + README.md
    ├── Parte 2/   (home + portfólio inicial)
    ├── Parte 3/   (galeria + páginas de produto)
    ├── Parte 4/   (menu responsivo + media queries)
    └── Parte 5/   (projeto final)
```

## Regras seguidas

O projeto segue todas as regras do plano: CSS exclusivamente externo em `css/style.css` (sem `style=""` e sem tags `<style>`), meta tag viewport em todas as páginas, abordagem Mobile First com media queries `min-width`, CSS Grid com 1/2/3 colunas por breakpoint, menu responsivo via checkbox sem JavaScript, e commits padronizados a cada parte concluída.

## Como abrir

Basta abrir o arquivo `index.html` de qualquer pasta `Parte N` diretamente no navegador — não é necessário servidor nem dependências.
