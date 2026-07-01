# DIV X Tags Semânticas

O elemento `<div>` no HTML é uma tag não semântica usada como um container genérico ele agrupa também outros elementos na página quando não tem outro significado para aquela seção.

Já as tags semânticas trazem um significado para a página comunicando claramente o contexto do seu conteúdo tanto para os navegadores quanto para os desenvolvedores e mecanismos de busca melhorando a página e proporcionando acessibilidade.

As principais tags semânticas no HTML5 são:

- `<header>` - Representa um elemento de cabeçalho na página, normalmente agrupa outros elementos como titulo, barra de navegação e logo.
- `<nav>` - Representa um elemento de navegação entre seções ou páginas diferentes, normalmente agrupa outros elementos html como link de navegação, logo.
- `<main>` - Representa um elemento de conteúdo principal da página, normalmente agrupa varios elementos html como título, páragrafo, imagens, diferentes seções da página etc. 
- `<footer>` - Representa um elemento de rodapé de uma seção ou de toda a página. Contém informações como direitos autorais, links de contato ou mapas do site

## Exemplo de tags não semânticas

```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <div>
            <h1>Meu Site</h1>
            <img src="#" alt="logo">
            <div>
                <ul>
                    <li>Home</li>
                    <li>Sobre</li>
                    <li>Contato</li>
            </div>
        </div>
        <div>
            <div>
                <h2>Seção 1</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </div>
            <div>
                <h2>Seção 3</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </div>
        </div>
        <div>
            <div>
                <h2>Sobre</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </div>
        </div>
    </body>
</html>
```

## Exemplo de tags semânticas

```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <header>
            <h1>Meu Site</h1>
            <img src="#" alt="logo">
            <nav>
                <ul>
                    <li>Home</li>
                    <li>Sobre</li>
                    <li>Contato</li>
            </nav>
        </header>
        <main>
            <section>
                <h2>Seção 1</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </section>
            <section>
                <h2>Seção 3</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </section>
        </main>
        <footer>
            <section>
                <h2>Sobre</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </section>
        </footer>
    </body>
                </html>
```
