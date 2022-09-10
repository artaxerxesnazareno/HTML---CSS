# Seletores CSS

**HTML é 'id' = CSS é '#' (somente um elemento)**

```html

    <h1 id="principal">Criando Sites com HTML e CSS</h1>

```

id e class

```html

    <h1 id="principal" class="destaque">Criando Sites com HTML e CSS</h1>

```

**HTML é 'class' = CSS é  '.' (podem ser varios elementos)**

```html

     <h2 class="intermediario">HTML intermediario</h2>

```

Duas classes

```html

     <h2 class="intermediario destaque">HTML intermediario</h2>

```

## Pseudo-Class

São relacionadas ao estado de um elemento

pseudo-class = ':'

```css
* {
     div:hover>p {
            display: block;
            color: white;
            background-color: red;
        } 
}
```

## Pseudo-Element

Modificam directamente os elementos

pseudo-elementos = '::'

```css
* {
     .especial::before {
            content: '⇒';
        }
     .especial::after {
            content: '⇐ ';

        }
}
```
