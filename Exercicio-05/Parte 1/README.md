# Verde Vida — Loja de Plantas e Jardinagem (Parte 1)

## Nome da loja
**Verde Vida**

## Tema escolhido
Loja virtual de **plantas e jardinagem**, com foco em trazer a natureza para a casa dos clientes. Slogan: *"Cultive momentos, colha bem-estar."*

## Objetivo do projeto
Desenvolver, do zero, uma loja virtual **responsiva** utilizando apenas **HTML5** e **CSS3 externo**, seguindo a abordagem **Mobile First**. O projeto evolui em 4 partes, implementando progressivamente a base do projeto, a página inicial, a galeria de produtos com páginas individuais e o menu responsivo sem JavaScript.

## Produtos fictícios (Parte 1)
| # | Produto | Preço imaginário |
|---|---------|------------------|
| 1 | Monstera Deliciosa (Muda Grande) | R$ 129,90 |
| 2 | Kit Jardinagem Premium (10 peças) | R$ 89,90 |
| 3 | Vaso de Cerâmica Artesanal 20cm | R$ 59,90 |
| 4 | Substrato Orgânico Premium 5kg | R$ 34,90 |
| 5 | Lanterna de Jardim Solar LED | R$ 79,90 |

## Estrutura de arquivos (Parte 1)
```
frontend/
└── Exercicio 5/
    └── Parte 1/
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

## Paleta de cores utilizada (variáveis CSS)
| Variável | Cor | Uso |
|----------|-----|-----|
| `--cor-primaria` | `#2e7d32` (verde floresta) | Marca, botões, títulos |
| `--cor-primaria-escura` | `#1b5e20` | Hover de botões, rodapé |
| `--cor-secundaria` | `#a5d6a7` (verde claro) | Fundos suaves, destaques |
| `--cor-accent` | `#f9a825` (âmbar) | Destaques e CTAs secundários |
| `--cor-fundo` | `#f5f7f5` | Fundo geral |
| `--cor-texto` | `#2c3e2d` | Texto principal |
| `--cor-texto-claro` | `#6b7a6c` | Texto secundário |
| `--cor-branco` | `#ffffff` | Branco puro |

**Tipografia:** Poppins (Google Fonts), com pesos 400, 500, 600 e 700.

## Regras seguidas
- Todo o CSS fica no arquivo `css/style.css` (proibido CSS inline e interno).
- Todas as páginas contêm a meta tag `viewport`.
- Estilização seguindo a abordagem Mobile First.
