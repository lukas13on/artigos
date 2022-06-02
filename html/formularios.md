# Lucas de Oliveira Neitzke: Artigos - HTML | Formulários

<img src="./img/header.jpg"/>

[Retornar: HTML](../html.md)

Esse é um artigo de HTML.

## Sumário

- [Introdução](#teste)
- [Elementos](#teste)
- [Input](#teste)
- [Select](#teste)
- [Textarea](#teste)

## Introdução

Os formulários são elementos do HTML que permitem ao usuário interagir com o site e enviar dados coletados pela interação para um servidor interno ou externo.

## Elementos

Os formulários em HTML abrangem três elementos, sendo eles: `<form>`, `<input>`, `<select>` e `<textarea>`. Esses elementos são essenciais para a interação com o usuário. Não é necessário utilizar todos os elementos, mas é importante que seja utilizado o `<form>` e ao menos um `<input>`, `<select>` ou `<textarea>` para que o usuário possa preencher e enviar os dados.

### Atributos dos elementos de formulário

- **accept:** aceita um tipo de arquivo específico
- **alt:** descrição do input
- **autocomplete:** indica se o input deve ser preenchido automaticamente
- **autofocus:** indica que o input deve ser focado automaticamente
- **checked:** indica que o input deve ser marcado por padrão
- **dirname:** indica o diretório do input
- **disabled:** indica que o input deve ser desabilitado por padrão
- **form:** indica o formulário do input
- **formaction:** indica a ação do formulário
- **formenctype:** indica o tipo de envio do formulário
- **formmethod:** indica o método de envio do formulário
- **formnovalidate:** indica que o formulário não deve ser validado 
- **formtarget:** indica o destino do formulário
- **height:** indica a altura do input
- **list:** indica a lista de valores do input
- **max:** indica o valor máximo do input
- **maxlength:** indica o tamanho máximo do input
- **min:** indica o valor mínimo do input
- **minlength:** indica o tamanho mínimo do input
- **multiple:** indica que o input aceita múltiplos valores
- **name:** indica o nome do input
- **pattern:** indica o padrão de regex do input
- **placeholder:** indica o texto de descrição flutuante do input
- **readonly:** indica que o input não deve ser editado por padrão
- **required:** indica que o input é obrigatório por padrão
- **size:** indica o tamanho do input
- **src:** indica o caminho do input
- **step:** indica o passo do input
- **type:** indica o tipo do input

### Form

O `<form>` é o elemento de formulário mais importante do HTML. Ele é utilizado para enviar dados para um servidor interno ou externo.

```html
<form></form>
```

#### Principais atributos

Os principais atributos do `<form>` são:

##### Ação (action)

A ação do formulário é o caminho relativo ou absoluto para o servidor interno ou externo.

```html
<form action="https://google.com.br"></form>
<form action="caminho/pagina.php"></form>
```

##### Método (method)

O método do formulário é o tipo de método utilizado na requisição.

Métodos aceitos:

- `GET`
- `POST`
- `PUT`
- `DELETE`

Somente é aceito um tipo por vez.

```html
<form method="GET"></form>
<form method="POST"></form>
```

##### Tipo de midia (enctype)

Define o tipo de mídia utilizado na requisição do formulário.

Tipos aceitos:

- `application/x-www-form-urlencoded` (padrão)
- `multipart/form-data` (formulário com envio de arquivos)
- `text/plain`

```html
<form enctype="application/x-www-form-urlencoded"></form>
<form enctype="multipart/form-data"></form>
```

##### Tipo de codificação (accept-charset)

Define o tipo de codificação aceita pelo servidor.

Tipos aceitos:

- `UTF-8`
- `ISO-8859-1`

```html
<form accept-charset="UTF-8"></form>
<form accept-charset="ISO-8859-1"></form>
```

#### Atributos complementares

Existem alguns atributos complementares que podem ser utilizados no `<form>`:

##### Não validar (novalidate)

Isso indica que o formulário não deve ser validado.

```html
<form novalidate></form>
```

##### Auto preenchimento (autocomplete)

Ao preencher o formulário, os campos serão preenchidos automaticamente conforme, depende da compatibilidade do navegador.

Tipos aceitos:

- `on`
- `off`

```html
<form autocomplete="on"></form>
<form autocomplete="off"></form>
```

##### Alvo (target)

Determina se o formulário abrirá em uma nova janela, ou se abrirá na mesma janela.

Tipos aceitos:

- `_blank` (abrirá em uma nova janela)
- `_self` (abrirá na mesma janela)
- `_parent` (abrirá na janela pai)
- `_top` (abrirá na janela superior)

```html
<form target="_self"></form>
<form target="_blank"></form>
```

##### Nome (name)

Nome do formulário.

```html
<form name="cadastro"></form>
<form name="acesso"></form>
```

##### Relação (rel)

Define a relação entre o formulário e a página atual.

Tipos aceitos:

- `alternate`
- `author`
- `bookmark`
- `help`
- `license`
- `next`
- `nofollow`
- `noreferrer`
- `prefetch`
- `prev`
- `search`
- `tag`

```html
<form rel="search"></form>
<form rel="tag"></form>
```

### Input

O `<input>` é o elemento de entrada mais importante do HTML. Ele é utilizado para criar formulários, preencher dados, etc. O `<input>` não possui fechamento de tag como os demais elementos do HTML como o `<form>`.


```html
<input/>
```

#### Tipos de input (type)

Há uma variedade de diferentes tipos de entrada que podem ser utilizada no input, sendo elas:

##### Principais

- **text:** input de texto
- **number:** input de número
- **tel:** input de telefone
- **password:** input de senha
- **radio:** input de radio
- **checkbox:** input de checkbox
- **range:** input de intervalo
- **button:** input de botão

###### Input de texto

O tipo de texto é utilizado para preencher dados que contenham qualquer texto (numeros, caracteres especiais e etc).

```html
<input type="text"/>
```

###### Input de numero

O tipo de numero é utilizado para preencher dados que contenham apenas números.

```html
<input type="number"/>
```

###### Input de telefone

O tipo de telefone é utilizado para preencher dados que contenham apenas números de telefones ou celulares.

```html
<input type="tel"/>
```

###### Input de seleção única

O tipo de seleção única é utilizado para preencher dados que contenham apenas uma opção.

```html
<input type="radio"/>
```

###### Input de caixa de seleção

O tipo de caixa de seleção é utilizado para preencher dados que contenham mais de uma opção.

```html
<input type="checkbox"/>
```

###### Input de intervalo

O tipo de intervalo é utilizado para preencher dados que contenham apenas números de intervalo.

```html
<input type="range"/>
```

###### Input de botão

O tipo de botão é utilizado para criar botões.

```html
<input type="button"/>
```

##### Data e hora

- **datetime-local:** input de data e hora
- **date:** input de data
- **time:** input de hora
- **week:** input de semana
- **month:** input de mês

###### Input de data

O tipo de data é utilizado para preencher dados que contenham apenas datas.

```html
<input type="date"/>
```

###### Input de hora

O tipo de hora é utilizado para preencher dados que contenham apenas horas.

```html
<input type="time"/>
```

###### Input de semana

O tipo de semana é utilizado para preencher dados que contenham apenas semanas.

```html
<input type="week"/>
```

###### Input de mês

O tipo de mês é utilizado para preencher dados que contenham apenas meses.

```html
<input type="month"/>
```

###### Input de hora e data local

O tipo de hora e data local é utilizado para preencher dados que contenham apenas horas e datas.

```html
<input type="datetime-local"/>
```

##### Outros

- **file:** input de arquivo
- **color:** input de cor

###### Input de arquivo

O tipo de arquivo é utilizado para preencher dados que contenham apenas arquivos.

```html
<input type="file"/>
```

###### Input de cor

O tipo de cor é utilizado para preencher dados que contenham apenas cores.

```html
<input type="color"/>
```

##### Controle

- **submit:** input de envio do formulário
- **reset:** input de limpeza o formulário
- **hidden:** input oculto do formulário

###### Input de envio

o tipo de envio é utilizado para enviar dados do formulário.

```html
<input type="submit"/>
```

###### Input de limpeza

O tipo de limpeza é utilizado para limpar dados do formulário.

```html
<input type="reset"/>
```

###### Input oculto

O tipo de oculto é utilizado para preencher dados que não serão exibidos.

```html
<input type="hidden"/>
```

### Select

Elit ex in irure in aliquip.

```html
<select></select>
```

### Textarea

Ipsum amet dolore incididunt fugiat qui.

```html
<textarea></textarea>
```