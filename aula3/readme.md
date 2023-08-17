# AULA 3 introdução a o CSS
## SINTAXE BASICA:
```css
seletor {
    propriedade: valor;
}
```

## tipos de seletores basicos:

### Tags
seleção via tag!
Exemplos
```css
p {
    color: red;
}

div {
    font-size: x-large;
}
```


### Classe

seleciona todas as tags da mesma classe
se usa um '.' seguido do nome da classe para fazer essa seleção
Exemplos:
```css
.class_name {
    color: red;
}

.teste {
    color: blue;
}
```

### Tags.class
O seletor elemento.class é usado para selecionar o elemento especificado com a classe especificada.

Exemplo:
```css

/*Seleciona e estiliza cada elemento <p> com a classe "teste":*/
p.teste {
    color: red;
}

```

### Id
O seletor #id estiliza o elemento com o id especificado.
se usa # para selecionar um id.

Exemplos:

```css
#nome_id1 {
    color: red;
}

#nome_idois {
    color: blue;
}
```
## hierarquia recomendada
1. Seletor por Tags
2. Seletor por .class
3. Seletor por elemento.class
4. Seletor por #id