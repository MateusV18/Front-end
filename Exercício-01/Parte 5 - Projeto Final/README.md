# PokéStarters

## Objetivo

Site desenvolvido como atividade do curso, com o propósito de aplicar na prática os conceitos de **Bootstrap 5** — grid system, componentes prontos (navbar, cards, botões), utilitários de espaçamento e responsividade — na construção de uma página de apresentação.

O tema escolhido foi uma "Pokédex" com os Pokémons iniciais de todas as gerações (I a IX), listando tipo, número na Pokédex, região de origem e uma breve descrição de cada um, com link direto para a Pokédex oficial.

## Estrutura de pastas

```
PokeStarters/
├── index.html          # Página principal do projeto
├── img/                 # Imagens dos Pokémons iniciais
│   ├── bulbasaur.jpeg
│   ├── charmander.jpeg
│   ├── squirtle.jpeg
│   └── ...              # Demais iniciais (Gerações II a IX)
└── README.md            # Este arquivo
```

Não há CSS ou JS próprios em arquivo separado: o estilo vem do Bootstrap 5.3.8 e dos ícones do Bootstrap Icons, ambos carregados via CDN direto no `<head>` e no fim do `<body>` do `index.html`.

## Como abrir o projeto

1. Baixe ou clone a pasta do projeto mantendo a estrutura acima (o `index.html` precisa estar na raiz e a pasta `img/` no mesmo nível).
2. Abra o arquivo `index.html` direto no navegador (duplo clique ou "Abrir com" o navegador de sua preferência).
3. Não é necessário servidor local nem instalação de dependências — as bibliotecas (Bootstrap e Bootstrap Icons) são carregadas via CDN, então é preciso estar conectado à internet para o site carregar corretamente.

## Validação e revisão feita

- [x] Validação do HTML no [W3C Markup Validator](https://validator.w3.org/)
- [x] Teste de responsividade em diferentes resoluções (mobile, tablet, desktop) via DevTools
- [x] Conferência dos links externos (Pokédex oficial de cada Pokémon)
- [x] Revisão cruzada entre os integrantes da dupla (Mateus e Ícaro)

## Referências

- [Documentação oficial do Bootstrap 5](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Pokédex oficial](https://www.pokemon.com/br/pokedex)

---

Pokémon é marca registrada da Nintendo / Game Freak. Projeto desenvolvido apenas para fins educacionais.
