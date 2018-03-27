# Code Style Guide
Guia de estilo de código - Padrões para codificação de Code Ui

1. [Sintaxe](#)
1. [Declaração](#)
1. [Comentários](#)

### Sintaxe

Use soft-tabs com dois espaços:

```css
/* bom */
.btn {
	color: #000;
}

/* ruim */
.btn{
		color: #000;
}
```

Use sempre aspas duplas:

```css
/* bom */
.btn {
	background-image: url("imagem.jpg");
	font-family: "Arial Black", sans-serif;
}

/* ruim */
.btn {
	background-image: url('imagem.jpg');
	font-family: 'Arial Black', sans-serif;
}
```

Não esqueça de incluir um espaço antes de abrir as chaves da regra:

```css
/* bom */
.btn {
	color: #000;
}

/* ruim */
.btn{
	color: #000;
}
```

Fecha as chaves em uma nova linha:

```css
/* bom */
.btn {
	color: #000;
}

/* ruim */
.btn {
	color: #000;}
```

Depois do : da declaração: Inclua um espaço 

```css
/* bom */
.btn {
	color: #000;
}

/* ruim */
.btn {
	color:#fff;
}
```

No fim da declaração: use um ;

```css
/* bom */
.btn {
	color: #000;
}

/* ruim */
.btn {
	color: #000
}
```

Mantenha uma declaração por linha:

```css
/* bom */
.nav,
.footer,
.btn {
	color: #000;
}

/* ruim */
.nav, .footer, .btn {
	color: #000;
}
```

As regras deve ser separadas por uma linha em branco:

```css
/* bom */
.btn {
	color: #000;
}

.nav-item {
	color: #000;
}

/* ruim */
.btn {
	color: #000;
}
.nav-item {
	color: #000;
}
```

Utilize caixa baixa:

```css
/* bom */
.nav-item {
	color: #000;
}

/* ruim */
.Nav-item {
	color: #000;
}
```

Utilize hífens ao separar os nomes:

```css
/* bom */
.nav-item {
	color: #000;
}

/* ruim */
.nav_item {
	color: #000;
}
```

Ao utilizar valores hexadecimais escreva de forma reduzida:

```css
/* bom */
.nav-item {
	color: #000;
}

/* ruim */
.nav-item {
	color: #000;
}
```

Não especifique unidades quando o valor for igual a zero:

```css
/* bom */
.nav-item {
	padding: 0;
}

/* ruim */
.nav-item {
	padding: 0px;
}
```

Não use valores iniciados com zero:

```css
/* bom */
.nav-item {
	transition: color .3s;
}

/* ruim */
.nav-item {
	transition: color 0.3s;
}
```

### Declarações

As declarações devem estar em ordem alfabética.

```css
/* bom */
.btn {
	background: #000;
	color: #fff;
	display: inline-block;
	margin: 0;
	padding: 10px;
}
a
/* ruim */
.btn {
	color: #fff;
	background: #000;
	margin: 0;
	padding: 10px;
	display: inline-block;
}
```

### Comentários

```css
/* Bloco de comentário de seção
======================================== */

/* Bloco de comentário de sub-seção
==================== */

/* Comentário básico */
```
