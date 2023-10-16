# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges helps us improve our coding skills by building realistic projects.

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

![](/screenshots/desktop-design.jpeg)

### Links

- Solution URL: [https://github.com/MikSanty/product-preview-card-component-main](https://github.com/MikSanty/product-preview-card-component-main)
- Live Site URL: [miksanty-product-preview-card.netlify.app](miksanty-product-preview-card.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I guess using the srcset to change the image shown depending on the view is very eye-opening to me HAHA.

```
<picture class="product__image">
  <source srcset="images/image-product-mobile.jpg" media="(max-width: 600px)">
  <img src="images/image-product-desktop.jpg" alt="Product image">
</picture>
```

### Continued development

The concept of 'Grid' is actually something that I am not comfortable with and I want to learn more.
I am probably never not going to use srcset in my whole life. #CoolSh!t

### Useful resources

- [A (more) Modern CSS Reset](https://andy-bell.co.uk/a-more-modern-css-reset/) - I found his reset css online. I just removed things that I did not need.
- [Kevin Powell Solution to this Challenge](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - His solution really opened my eyes, this is where I learned to use srcset. HAHAHA

## Author

- Frontend Mentor - [@MikSanty](https://www.frontendmentor.io/profile/MikSanty)

## Acknowledgments

Special thanks to Kevin Powell and Andy Bell
