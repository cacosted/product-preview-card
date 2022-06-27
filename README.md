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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Mobile](https://user-images.githubusercontent.com/57645180/176048664-fe7ac305-b24a-44fa-88e6-a882507aef02.png)
![Desktop](https://user-images.githubusercontent.com/57645180/176048802-1b1b5d65-d8b9-451b-b28e-514edaf5d625.png)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/product-preview-responsive-card-build-with-vanilla-css-0K32SRDl8w)
- Live Site URL: [Live Demo](https://cacosted.github.io/product-preview-card)

## My process

### Built with

- Semantic HTML5 markup
- Pseudoelements
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM naming convention

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this project I used a very interesting tag the `<picture>`, with this element I could use two different sources of images, and show on of them depending on the screen size.

I used in this way:

```html
<picture class="card__img">
  <source
    loading="lazy"
    media="(min-width: 700px)"
    srcset="./images/image-product-desktop.jpg"
    alt="Gabrielle perfume"
  />
  <img
    loading="lazy"
    class="img"
    src="./images/image-product-mobile.jpg"
    alt="Gabrielle perfume"
  />
</picture>
```

## Author

- Frontend Mentor - [@cacosted](https://www.frontendmentor.io/profile/cacosted)
- Twitter - [@cacosted](https://www.twitter.com/cacosted)
