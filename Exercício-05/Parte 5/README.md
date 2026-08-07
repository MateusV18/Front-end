# Verde Vida — Loja de Plantas e Jardinagem (Parte 5)

## Nome e tema da loja
**Verde Vida** — loja virtual de **plantas e jardinagem**. Slogan: *"Cultive momentos, colha bem-estar."*

## Objetivo do projeto
Desenvolver, do zero, uma loja virtual **responsiva** utilizando apenas **HTML5** e **CSS3 externo**, seguindo a abordagem **Mobile First**. O projeto evoluiu em 5 partes: estrutura base com identidade visual, home e portfólio, galeria com páginas individuais, menu responsivo sem JavaScript e, por fim, interações visuais (`:hover`, `:focus`), formulário de contato e revisão geral.

## Lista de páginas
| Página | Descrição |
|--------|-----------|
| `index.html` | Página inicial com hero, destaques e chamada para ação |
| `produtos.html` | Galeria completa com os 5 produtos (CSS Grid) |
| `produto-item1.html` | Detalhe: Monstera Deliciosa (Muda Grande) |
| `produto-item2.html` | Detalhe: Kit Jardinagem Premium (10 peças) |
| `produto-item3.html` | Detalhe: Vaso de Cerâmica Artesanal 20cm |
| `produto-item4.html` | Detalhe: Substrato Orgânico Premium 5kg |
| `produto-item5.html` | Detalhe: Lanterna de Jardim Solar LED |
| `portfolio.html` | Portfólio com tecnologias e decisões de responsividade |
| `contato.html` | Formulário de contato com Nome, E-mail, Assunto e Mensagem |

## Estrutura de arquivos (Parte 5)
```
frontend/
└── Exercicio 5/
    └── Parte 5/
        ├── index.html
        ├── produtos.html
        ├── produto-item1.html ... produto-item5.html
        ├── portfolio.html
        ├── contato.html
        ├── README.md
        ├── css/
        │   └── style.css
        └── img/
```

## Produtos fictícios
| # | Produto | Preço imaginário |
|---|---------|------------------|
| 1 | Monstera Deliciosa (Muda Grande) | R$ 129,90 |
| 2 | Kit Jardinagem Premium (10 peças) | R$ 89,90 |
| 3 | Vaso de Cerâmica Artesanal 20cm | R$ 59,90 |
| 4 | Substrato Orgânico Premium 5kg | R$ 34,90 |
| 5 | Lanterna de Jardim Solar LED | R$ 79,90 |

## Paleta de cores utilizada
| Variável | Cor | Uso |
|----------|-----|-----|
| `--cor-primaria` | `#2e7d32` (verde floresta) | Marca, botões, títulos |
| `--cor-primaria-escura` | `#1b5e20` | Hover de botões, rodapé |
| `--cor-secundaria` | `#a5d6a7` (verde claro) | Fundos suaves, destaques |
| `--cor-accent` | `#f9a825` (âmbar) | Destaques, CTAs e foco |
| `--cor-fundo` | `#f5f7f5` | Fundo geral |
| `--cor-texto` | `#2c3e2d` | Texto principal |
| `--cor-texto-claro` | `#6b7a6c` | Texto secundário |
| `--cor-branco` | `#ffffff` | Branco puro |

**Tipografia:** Poppins (Google Fonts), com pesos 400, 500, 600 e 700.

## Tecnologias utilizadas
- **HTML5** — estrutura semântica com `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` e `<footer>`.
- **CSS3 externo** — todo o estilo centralizado no arquivo `css/style.css`, sem uso de CSS inline ou interno.
- **Variáveis CSS**, **Flexbox**, **CSS Grid**, **Media Queries** e **transições**.

## Como abrir o projeto localmente
1. Baixe ou clone a pasta `Exercicio 5/Parte 5/` do repositório `frontend`.
2. Navegue até o diretório `Parte 5/`.
3. Abra o arquivo `index.html` diretamente no navegador (duplo clique ou arraste para o navegador).
4. Nenhum servidor ou dependência é necessário: basta o navegador.

## Regras seguidas no projeto
- Todo o CSS fica no arquivo `css/style.css` (proibido CSS inline e interno).
- Todas as páginas contêm a meta tag `viewport`.
- Estilização seguindo a abordagem Mobile First.
- Menu responsivo sem JavaScript (checkbox + `:checked`).
- Galeria em 1 coluna (mobile), 2 colunas (768px) e 3 colunas (1024px).
- Commits a cada parte concluída, com mensagens padronizadas.
