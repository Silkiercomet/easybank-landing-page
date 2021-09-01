# Frontend Mentor - Easybank landing page solution

This is a solution to the [Easybank landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/easybank-landing-page-WaUhkoDN). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/easybank-landing-page-html-and-css-only-EO3GRtWGe)
- Live Site URL: [Add live site URL here](https://silkiercomet.github.io/easybank-landing-page/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
  Spanish/español.

 Aprendi a usar la propiedad position:relative junto con z-index:99; para ordenar las capaz de la 
layout correctamente, en ocasiones la propiedad z-index por default unicamente se aplica a los
elementos ubicados en la caja que se aplica, con el uso de position:relative se ordenaran en base a todos los elementos del body y de la poscion definida en z-index

  English/ingles.

 I learned to use the position property together with the z-index; to order elements in the full scope of the layout, sometimes the use of the z-index only applies to the container that you applied to, this can be enough for the mayority of cases but in this occasion we needed it to overflow the content of other 
container, thats when the use of position:relative; comes to play a role, because now the index is over the entire body

```css
  .hero .right figure img {
    position: relative;
    transform: translateY(-120px);
    z-index: 2;
    width: 100%;
  }
```


### Continued development

i would love to add more animations to this layout the puse use of CSS for the navbars 

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Comet466)


## Acknowledgments

to absolutly F****** nobody

