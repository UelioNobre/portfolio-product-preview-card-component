# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop version](./screenshot-desktop.png)
![Mobile version](./screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/UelioNobre/portfolio-product-preview-card-component)
- Live Site URL: [Add live site URL here](https://uelionobre.github.io/portfolio-product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

__PORTUGUESE__

Flexbox, Flexbox, Flexbox... e por ai vai...

A vida não é toda feita de Flexbox. Entender outras formas de posicionamentos de elementos também é válida. Neste projeto usei os dois, Grid para estruturar card o card em grade de linhas e colunas (é mais fácil gerencia-los) e Flexbox para alinhar os elementos dentro de cada grade.

Dessa forma, fica mais fácil posicionar os elementos no design e quando precisar, usar Flexbox para separa-los horizontalmente.

Como é um projeto de aprendizado, escolhi utilizar esta abordagem.

Como este é um projeto de estudo, aproveitei e coloquei um pouco de animação entre as transições de responsividades.

Espero que gostem!

---

__ENGLISH__

Flexbox, Flexbox, Flexbox... and so on...

Life isn't all about Flexbox. Understanding other ways of positioning elements is also valid. In this project I used both: Grid to structure each card in a grid of rows and columns (it's easier to manage them) and Flexbox to align the elements within each grid.

This way, it's easier to position the elements in the design and, when necessary, use Flexbox to separate them horizontally.

Since this is a learning project, I chose to use this approach.

As this is a study project, I took the opportunity to add some animation between the responsive transitions.

I hope you like it!

---

__PORTUGUESE__
Para resolver a responsividade entre telas, somente mudei a orientação da Grade, pois o conteúdo já estava posicionado de forma satisfatória.

---

__ENGLISH__
To resolve the responsiveness between screens, I only changed the orientation of the Grid, as the content was already positioned satisfactorily.



```css
@media screen and (min-width:1440px)
{
  .card
  {
    width: 600px;
    grid-template-columns: 50% 1fr;
    grid-template-rows: 1fr;
  }
}
```

### Continued development

__PORTUGUESE__
Por enquanto ainda estudo estudando Grid, mas pretendo seguir em frente utilizado estes dois mundos maravilhosos: Grid e Flexbox.

---

__ENGLISH__
For now I'm still studying Grid, but I intend to move forward using these two wonderful worlds: Grid and Flexbox.

--

### Useful resources

- [W3 Schools](https://www.w3schools.com/css/) - CSS content learning.

## Author

- Website - [Uélio Nobre](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/UelioNobre)

