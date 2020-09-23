# homework2
Code repository for Homework 2

Description and instructions can be found at: https://docs.google.com/document/d/1DNXt4zdudBvAgjGNyeW5RZLXl2NrwvN5SHspXzr6eTc/edit?usp=sharing

# Backlog
This hw create a new .css file to offer more styles to html. `style.css` is created, link to `index.html` is added.
1. Link html to css:
```html
<link rel="stylesheet" href="css/html5reset.css">
<link rel="stylesheet" href="css/style.css">
```
2. `html5reset.css` is always the deafult css the html to find. And should be put in the first line of `<link>`.

Always name your stylesheet style.css.


3. The order of selecter in css should be with the same order as in html (in case of some abnormal stuffs appear).

4. 
```css
img {
    display: block;   /* On their own line */
    /* center */
    margin-left: auto;
    margin-right: auto;
    height: auto;
    width: 525px;
}
```

5. `padding` properties are used to generate space around an element's content, inside of any defined borders.

[padding - w3school](https://www.w3schools.com/css/css_padding.asp)
```css
div {
  border: 1px solid black;
  background-color: lightblue;
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left:
  ```
  
  ```css
  div {
  border: 1px solid black;
  padding: 25px 50px 75px 100px;
  background-color: lightblue;
}
```
  
6. The `overflow` property specifies what should happen if content overflows an element's box.

[overflow - w3school](https://www.w3schools.com/cssref/pr_pos_overflow.asp) 
```css
div.ex1 {
  overflow: scroll;
}

div.ex2 {
  overflow: hidden;
}

div.ex3 {
  overflow: auto;
}

div.ex4 {
  overflow: visible;
}
```
