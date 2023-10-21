# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/Solution%20Screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj/hub?share=true]
- Live Site URL: [https://awitmer1.github.io/Frontend-Mentor-Order-Summary-Component/]

## My process

I began by creating the CSS variables from the style guide and then worked on converting the boilerplate html into appropriate elements. Then I worked on creating the main card component and getting every element in an appropriate div container and in the correct order vertically. After that came the image imports, adjusting the sizing of the elements to the appropriate height/width, centering using Flexbox, and adding the background. The final piece was adding the appropriate colors and styling, followed by resizing the elements for the mobile screen size. This was my first time using media queries and I found it both interesting and challenging.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS custom variables
- Flexbox

### What I learned

I learned how to use CSS custom variables. I also learned how to use media queries, but understood the principle of 'mobile-first design' as I found shrinking my design down from a desktop resolution to be particularly tedious and challenging.

This was also my first time using blending a background color and gradient together:

```css
.body {
  background-color: var(--Pale-blue);
  background-image: url("./images/pattern-background-desktop.svg");
}
```

### Continued development

I want to continue to use media queries for more responsive layouts, but in a more efficient way to where I am not spending as much time in developer tools trying to achieve the desired outcome.

## Author

- Frontend Mentor - [@awitmer1](https://www.frontendmentor.io/profile/awitmer1)
