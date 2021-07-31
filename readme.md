# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Sunnyside](https://sunnyside-agency-bay.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass

### What I learned
 - lazy loading images in html & javascript

```html
  <!-- visible in the viewport -->
  <img src="product-1.jpg" alt="..." width="200" height="200">
  <img src="product-2.jpg" alt="..." width="200" height="200">
  <img src="product-3.jpg" alt="..." width="200" height="200">

  <!-- offscreen images -->
  <img src="product-4.jpg" loading="lazy" alt="..." width="200" height="200">
  <img src="product-5.jpg" loading="lazy" alt="..." width="200" height="200">
  <img src="product-6.jpg" loading="lazy" alt="..." width="200" height="200">
  
  credits: https://web.dev/browser-level-image-lazy-loading/#avoid-lazy-loading-images-that-are-in-the-first-visible-viewport
```

 - CSS shorthand properties that defines both the logical (inline start and end) or (block start and end) margins and
   paddings of an
   element, which maps to physical margins/paddings depending on the element's writing mode, directionality, and text
   orientation.
   
   ```css
    margin-inline: 1rem 1rem; === margin-left: 1rem; margin-right: 1rem;
    margin-block: 1rem 1rem;  === margin-top: 1rem; margin-bottom: 1rem;

    padding-inline: 1rem 1rem;  === padding-left: 1rem; padding-right: 1rem;
    padding-block: 1rem;  === padding-top: 1rem; paddig-bottom: 1rem;
   ```

### Resouces

- [lazy loading](https://web.dev/browser-level-image-lazy-loading/#avoid-lazy-loading-images-that-are-in-the-first-visible-viewport)
- [margin-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-inline)
- [margin-block](https://developer.mozilla.org/en-US/docs/Web/CSS/margin-block)
- [padding-inline](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-inline)
- [padding-block](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-block)

