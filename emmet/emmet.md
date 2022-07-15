# Emmet

# HTML

## Вложенность тегов

```html
nav>ul>li

<nav>
  <ul>
    <li></li>
  </ul>
<nav>
```

## Соседние теги

```html
div+b+bq

<div></div>
<b></b>
<blockquote></blockquote>
```

## Выход на один уровень выше в DOM дереве

```html
div>p^p

<div>
  <p></p>
</div>
<p></p>
```

## Классы и айди

```html
.one
.two#info

<div class="one"></div>
<div class="two" id="info"></div>
```

## Знак $

```html
ul>li.sample$*3

<ul>
  <li class="sample1"></li>
  <li class="sample2"></li>
  <li class="sample3"></li>
</ul>
```

## Атрибуты

```html
p[title="text"]

<p title="text"></p>
```

## Фигурные скобки 

```html
a{click me}

<a href="">click me</a>
```

## Тег а 

```html
a
a:link
a:mail

<a href=""></a>
<a href="http://"></a>
<a href="mailto"></a>
```

## Тег br, hr

```html
br
hr

<br>
<hr>
```

## Тег link

```html
link
link:css
link:favicon

<link rel="stylesheet" href="">
<link rel="stylesheet" href="style.css">
<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
```

## Тег meta

```html
meta
meta:utf
meta:vp

<meta>
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
<meta name="viewport" content="width=device-width, user-scalable=no,
initial-scale=1.0,maximum-scale=1.0, minimum-scale=1.0">
```

## Тег form

```html
form
form:get
form:post

<form action=""></form>
<form action="" method="get"></form>
<form action="" method="post"></form>
```

## Тег input

```html
input
input:h
input:email
input:url
input:p
input:datetime
input:date
input:s
input:c
input:r
input:reset

<input type="text">
<input type="hidden" name="">
<input type="email" name="" id="">
<input type="url" name="" id="">
<input type="password" name="" id="">
<input type="datetime" name="" id="">
<input type="date" name="" id="">
<input type="submit" value=""> 
<input type="checkbox" name="" id="">
<input type="radio" name="" id="">
<input type="reset" value="">
```

## Тег button

```html
btn
btn:s
btn:r
btn:d

<button></button>
<button type="submit"></button>
<button type="reset"></button>
<button disabled></button>
```

## Структурные теги

```html
bq
hdr
ftr
adr

<blockquote></blockquote>
<header></header>
<footer></footer>
<address></address>
```

## Списки

```html
ol
ul
dl

<ol></ol>
<ul></ul>
<dl></dl>
```

## Таблицы

```html
table
tr
td

<table></table>
<tr></tr>
<td></td>
```








# CSS


## position

```css
pos
pos:s
pos:a
pos:r
pos:f

position: relative;
position: static;
position: absolute;
position: relative;
position: fixed;
```

## Coordinates

```css
t
r
b
l

top;
right;
bottom;
left;
```

## z-index

```css
z

z-index
```

## display

```css
d:none

display: none;
```

## cursor

```css
cur:ha
cur:he
cur:p
cur:t

cursor: hand;
cursor: help;
cursor: pointer;
cursor: text;
```

## Margin

```css
m
mt
mr
mb
ml


margin
margin-top
margin-right
margin-bottom
margin-left
```

## Padding

```css
p
pt
pr
pb
pl

padding
padding-top
padding-right
padding-bottom
padding-left
```

## box-shadow

```css
bxsh

box-shadow
```

## Ширина и высота

```css
w
h
maw
mah
miw
mih

width
height
max-width
max-height
min-width
min-height
```


## Text

```css
fw:n
fw:b
ff
fz

font-weight: normal;
font-weight: bold;
font-family
font-size

tar
taj
tal
tac

text-align: right;
text-align: justify;
text-align: left;
text-align: center;

tdn
tdu
tdo
tdl

text-decoration: none;
text-decoration: underline;
text-decoration: overline;
text-decoration: line-through;

ttn
ttc
ttu
ttl

text-transform: none;
text-transform: capitalize;
text-transform: uppercase;
text-transform: lowercase;

tsh
lh
lts

text-shadow
line-height
letter-spacing

c
c:r
c#f

color
color: rgb(0, 0, 0);
color: #fff;

@f
@f+

@font-face {
  font-family: ;
  src: url();
}

@font-face {
  font-family: 'FontName';
  src: url(...);
  src: url(...).format(),
      url(...).format(),
      url(...).format(),
      url(...).format();
  font-style: normal;
  font-weight: normal;
}


@i
@m

@import url();

@media screen {
  
}
```


## Фоны

```css
bg
bgn
bgc
bgi

background
background: none;
background-color
background-image
```


## Рамки

```css
bd
bd:n
bd+
bdrs

border
border: none;
border: 1px solid #000;
border-radius
```
