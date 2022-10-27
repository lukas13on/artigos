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
// minha string
string = 'mudou para';
// mudou para
string = `um valor`;
// um valor
string = new String('primitivo');
// primitivo
``` 

## Números

```js
var numero;
numero = 10;
// 10
numero = 10.79;
// 10.79
numero = Number("10.56");
// 10.56
numero = Number(`7,94`);
// NaN
```

### NaN
Não é um numero...

## Arrays

```js
var frutas = ["Banana", `Morango`];
// Banana, Morango
frutas = new Array("Melancia", 'Kiwi');
// Melancia, Kiwi
frutas = Array("Uva", new String(`Abacate`));
// Uva, Abacate
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

### Callback

```js

```

### Construtor

```js
function Pessoa(nome){
    this.nome = nome;
    return this;
}
```

### Generator

```js

```