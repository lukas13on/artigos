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
expressiva(5, 5);
// 10
```

### Anonima

```js
const anonima = (function(a, b){
    return a + b;
})(2, 2);
// 4
```

### Arrow

```js
const arrow = (a, b) => {
  return a + b;
};
arrow(1, 2)
// 3
```

### Callback

```js
function callback(texto){
    console.log('Olá ' + mundo)
}
const executar = (callback) => {
    callback('mundo')
}
executar(callback)
// ola mundo

```

### Generator

```js

```

### Classes

```js
class Pessoa {
    nome = 'Lucas'
    sobrenome = 'Neitzke'

    getNome(){
        return this.nome;
    }

    getSobrenome(){
        return this.sobrenome;
    }
}

const pessoa = new Pessoa().getSobrenome()
// neitzke
```

### Construtor

```js
class Pessoa {
    nome = '';
    sobrenome = '';

    constructor(nome, sobrenome){
        this.nome = nome;
        this.sobrenome = sobrenome;
    }

    getNomeCompleto(){
        return this.nome + ' ' + this.sobrenome;
    }
}

const pessoa = new Pessoa('lucas', 'neitzke').getNomeCompleto()
// lucas neitzke
```

### Prototipação

```js
function Pessoa(nome, sobrenome){
    this.nome = nome
    this.sobrenome = sobrenome
    return this;
}

Pessoa.prototype.getNomeCompleto = function(){
    return this.nome + ' ' + this.sobrenome;
}

pessoa = new Pessoa('lucas', 'neitzke')

```