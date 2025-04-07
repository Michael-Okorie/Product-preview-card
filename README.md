# Product-preview-card

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot of the finished product preview card component](./screenshot/screenshot.png)

### Links

- Solution URL: [View solution on Frontend Mentor](https://www.frontendmentor.io/solutions/product-preview-card-vanilla-html-css-flexbox-BESTEXAMPLE)
- Live Site URL: [Live demo on GitHub Pages](https://michael-okorie.github.io/Product-preview-card/)
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- Mobile-first workflow
- Responsive layout with media queries

### What I learned

This project helped reinforce my understanding of **responsive design with Flexbox**, especially how to:

- Switch from column to row layouts at different screen sizes
- Use `object-fit` and `background-image` correctly inside Flexbox
- Use `flex: 1` and `align-self: stretch` to eliminate unwanted white space

#### CSS Example:
```css
.card {
  display: flex;
  flex-direction: row;
  height: 400px;
}

.product-img {
  flex: 1;
  object-fit: cover;
  height: 100%;
}
```

This layout helped me eliminate awkward whitespace that appeared when using standard `<img>` elements.

### Continued development

In the future, I want to:

- Get more comfortable with `object-fit`, `align-self`, and `background-image` usage
- Practice building more components with reusable CSS architecture
- Learn how to convert this design into a reusable component in React or another JS framework

### Useful resources

- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Always my go-to reference for Flexbox behavior
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - For checking HTML/CSS syntax and browser support
- [Frontend Mentor community](https://www.frontendmentor.io/) - Super helpful for reviewing others' code and learning different ways to approach layout problems

## Author

- Github - [Michael Okorie](github.com/Michael-Okorie)
- Frontend Mentor - [@Michael-Okorie](https://www.frontendmentor.io/profile/Michael-Okorie)
- Twitter - [@Dev_Michael_](https://x.com/Dev_Michael_)

## Acknowledgments

Huge thanks to the Frontend Mentor Discord community for always sharing tips and reviewing solutions.
