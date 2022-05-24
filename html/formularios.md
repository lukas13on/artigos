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

Consectetur qui in velit pariatur adipisicing aliqua labore.

## Elementos

Os formulário HTML abrangem três elementos, sendo eles: `<form>`, `<input>`, `<select>` e `<textarea>`.

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

Voluptate cillum exercitation dolore aliquip in enim irure commodo adipisicing aliquip est occaecat.

```html
<form></form>
```

#### Principais atributos

Consequat esse excepteur id ut culpa cillum aute ut.

##### Ação (action)

Nisi veniam consectetur voluptate amet et eiusmod voluptate ex dolor enim officia.

```html
<form action=""></form>
```

##### Método (method)

Enim id duis mollit non occaecat eu.

Métodos aceitos:

- `GET`
- `POST`
- `PUT`
- `DELETE`

```html
<form method=""></form>
```

##### Tipo de compilação (enctype)

Enim eiusmod dolor non est nulla.

Tipos aceitos:

- `application/x-www-form-urlencoded`
- `multipart/form-data`
- `text/plain`

```html
<form enctype=""></form>
```

##### Tipo de codificação (accept-charset)

Reprehenderit commodo officia ad consequat ullamco aliquip non aliqua.

Tipos aceitos:

- `UTF-8`
- `ISO-8859-1`

```html
<form accept-charset=""></form>
```

#### Atributos complementares

Ullamco aliquip labore ex id deserunt tempor.

##### Não validar (novalidate)

Ex anim sint ipsum ad et ad reprehenderit commodo consequat commodo veniam.

```html
<form novalidate></form>
```

##### Auto preenchimento (autocomplete)

Laborum laborum culpa mollit id non nulla anim.

Tipos aceitos:

- `on`
- `off`

```html
<form autocomplete=""></form>
```

##### Alvo (target)

Ipsum tempor culpa elit ut dolore dolore sint.

Tipos aceitos:

- `_blank`
- `_self`
- `_parent`
- `_top`

```html
<form target=""></form>
```

##### Nome (name)

Officia enim amet eu esse exercitation.

```html
<form name=""></form>
```

##### Relativo (rel)

Est aliquip dolor irure deserunt veniam est aliquip esse aliquip ea occaecat ipsum magna in.

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
<form rel=""></form>
```

### Input

In occaecat esse minim qui aute consequat veniam proident Lorem.

```html
<input/>
```

#### Tipos de input (type)

Culpa commodo veniam Lorem ut fugiat dolor excepteur velit elit est reprehenderit.

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

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="text"/>
```

###### Input de numero

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="number"/>
```

###### Input de telefone

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="tel"/>
```

###### Input de seleção única

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="radio"/>
```

###### Input de caixa de seleção

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="checkbox"/>
```

###### Input de intervalo

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="range"/>
```

###### Input de botão

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

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

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="date"/>
```

###### Input de hora

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="time"/>
```

###### Input de semana

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="week"/>
```

###### Input de mês

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="month"/>
```

###### Input de hora e data local

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="datetime-local"/>
```

##### Outros

- **file:** input de arquivo
- **color:** input de cor

###### Input de arquivo

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="file"/>
```

###### Input de cor

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="color"/>
```

##### Controle

- **submit:** input de envio do formulário
- **reset:** input de limpeza o formulário
- **hidden:** input oculto do formulário

###### Input de envio

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="submit"/>
```

###### Input de limpeza

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="reset"/>
```

###### Input oculto

Quis commodo ut excepteur reprehenderit nisi qui adipisicing nulla incididunt culpa ullamco tempor minim.

```html
<input type="hidden"/>
```

### Select

Ex consequat elit non sunt elit elit adipisicing duis fugiat sit velit culpa ex.

```html
<select></select>
```

### Textarea

Ipsum amet dolore incididunt fugiat qui.

```html
<textarea></textarea>
```