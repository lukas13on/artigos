# Javascript

## Variaveis


```js
const nomeVariavel;
var nomeVariavel;
let nomeVariavel;
```

## Strings

```js
var string;
string = "minha string";
string = 'mudou para';
string = `um valor`;
string = new String('primitivo');
``` 

## Números

```js
var numero;
numero = 10;
numero = 10.79;
numero = Number("10.56");
```

### NaN
Não é um numero...

## Arrays

```js
var lista = [];
lista = new Array();
```

## Objetos

```js
var pessoa = {
    nome: `Lucas`,
    saldo: 5.43,
    altura: Number(new String('1.89')),
    bolso: [
        "borracha",
        'clips'
    ]
};
```

## Funções

### Declarativa

```js
function declarativa(a, b){
    return a + b;
}
```

### Expressiva 

```js
const expressiva = function(a, b){
    return a + b;
};
```

### Anonima

```js
const anonima = (function(a, b){
    return a + b;
});
```

### Arrow

```js
const arrow = (a, b) => {
  return a + b;
};
```

### Construtor

```js
function Pessoa(nome){
    this.nome = nome;
    return this;
}
```