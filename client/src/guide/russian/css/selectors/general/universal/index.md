---
title: Universal
localeTitle: универсальный
---
## универсальный

Универсальный селектор (\*) выбирает все элементы. Он также выбирает все элементы внутри элемента. Вы можете подключить универсальный селектор с любым другим селектором.

### Синтаксис кода

```css
* { 
  css declarations; 
 } 
```

```css
element * { 
  css declarations; 
 } 
```

#### Пример кода

Этот селектор соответствует всем элементам и устанавливает цвет шрифта как зеленый.

```css
* { 
  color: green; 
 } 
```

Этот селектор выбирает все элементы div и устанавливает цвет шрифта как зеленый.

```css
div * { 
  color: green; 
 } 
```

Этот селектор выбирает все элементы, значение атрибута языка которых начинается с en.

```css
* [lang^=en] { 
  color: green; 
 } 

```