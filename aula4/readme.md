```css
seletor {
    propriedade: valor;
}
```

# AULA 4 - CSS basico
## Color

Muda a cor do texto, a cor pode ser selecionada via RGB(), HEX, ou HSL

```css
#rgb {
    color: rgb(255, 0, 0);
}

#hex {
    color: #0000FF;
}

#hsl{
    color: hsl(100, 100%, 50%);
}
```

## backgound
Muda o fundo do elemento selecionado.
`background-color` muda a cor do fundo
`background-image` coloca uma imagem como fundo
`background-repeat` diz se a imagem de fundo vai se repetir
```css
/*muda a cor do fundo*/
#bg-color{
    background-color: #8a2be2;
}

/*coloca uma imagem de fundo*/
#bg-img {
    width: 1000px;
    height: 668px;
    padding-top: 334px;
    background-image: url("photo.jpg");
    background-repeat: no-repeat;
}
```

## border
Permite estilizar a borda de um elemento
`border` tamanho |se a borda é visivel(solid) ou transparente | cor
```css
#border{
    border: 10px solid #000000;
}
```

## margin
Adciona distancia entre os elementos
`margin` Adciona espaço nos 4 lados do elemento
`margin-top` Adciona espaço apenas no topo
`margin-bottom` Adciona espaço apenas no fundo
`margin-left` Adciona espaço apenas na esquerda
`margin-right` Adciona espaço apenas na direita

```css
#margin{
    margin-top: 500px;
}
```

## padding
Adciona espaço entre o texto e a borda
`padding` Adciona espaço nos 4 lados do elemento
`padding-top` Adciona espaço apenas no topo
`padding-bottom` Adciona espaço apenas no fundo
`padding-left` Adciona espaço apenas na esquerda
`padding-right` Adciona espaço apenas na direita

```css

#pend{
    padding-left: 500px;
}

#pbegin{
    padding-left: 50px;
}
```

## width & height
define o tamanho do elemento

width = horizontal
height = vertical

```css
#teste{
    width: 500px;
    height: 500px;
    border: 50px solid black;
}```


