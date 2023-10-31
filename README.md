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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![screenshot](./Product%20Preview%20Screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/product-preview-card-with-html-and-css-C1VzfDzXE6](https://www.frontendmentor.io/solutions/product-preview-card-with-html-and-css-C1VzfDzXE6)
- Live Site URL: [https://grunt395.github.io/Product-Preview-Card-Component/](https://grunt395.github.io/Product-Preview-Card-Component/)

## My process

### Built with

- HTML5 markup
- CSS Properties
- Flexbox

### What I learned

This is the first project I utilized flexboxes in, so it was a major learning curve to get the page layout how I wanted it. I was finally able to center the main content of the page using flexbox with the following CSS code:

```css
html,
body {
  height: 100%;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Continued development

I want to potentially use more flexbox properties in the page layout to align elements better, and potentially play around with the dimensions of elements to adjust the final size.

### Useful resources

- [StackOverflow page wrap](https://stackoverflow.com/questions/32978584/css-wrapper-is-not-taking-100-height-of-whole-page) - This helped me find a way to wrap the whole page in a div so that flexbox could center the page content.
- [W3Schools Mobile Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This helped me learn about media queries and showed how to specify a mobile page layout.

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/Grunt395](https://www.frontendmentor.io/profile/Grunt395)
