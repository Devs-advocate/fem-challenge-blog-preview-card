# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This challenge was to recreate this design using HTML and CSS. The finished product includes both a desktop and mobile design, with different specifications, as well as active states.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![desktop](./screenshots/FEM%20Blog%20preview%20card%20desktop.png)
![mobile](./screenshots/FEM%20Blog%20preview%20card%20mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Github Pages](https://devs-advocate.github.io/fem-challenge-qr_code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- @font-face
- media queries

### What I learned

A trick I learn't when trying to figure out how to crop an SVG image was to crop the container it was within instead. I had tried to directly manipulate the SVG's object-fit properties, but this was unsuccessful.

```html
<div class="svg-container">
  <svg ...></svg>
</div>
```

I also learned about @font-face and incorporating the .ttf fonts contained in the source files. Below is just one example.

```css
@font-face {
  font-family: "Figtree";
  src: url("./assets/fonts/static/Figtree-SemiBold.ttf");
  font-weight: Semibold;
  font-style: normal;
}
```

Mobile specs forced me to dive into media queries to get appropriate responsiveness and results. Below is just one example.

```css
@media screen and (max-width: 395px) {
  .card-foreground {
    width: 327px;
    height: 501px;
  }
}
```

### Continued development

In future I will look to dive deeper into SVGs. Learning how to create and manipulate them as they are common place in frontend development. I'll also look more closely at Typography and try to familiarise myself with aspects of fonts. This should include it's diverse range of properties and best practices to help future-proof current stylings.

### Useful resources

- [CSS Essential Training](https://www.linkedin.com/learning/css-essential-training-22688362/getting-started-with-css) - This helped me with typography. This course is something I will use for reference in the future. It's accessible through subscription to LinkedIn Learning.

## Author

- Frontend Mentor - [@Devs-advocate](https://www.frontendmentor.io/profile/Devs-advocate)
