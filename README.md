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
- [Author](#author)
- [Acknowledgement](#acknowledgement)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot](./screenshot.jpg)
[Screenshot-mobile](./screenshot-mobile.jpg)

### Links

- Live Site URL: [Link](https://marucheto.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```css
/* CSS :hover Pseudo-class */
h1:hover {
  color: hsl(47, 88%, 63%);
}
.container-inner {
  /* border: size style color; */
  border: 1px solid hsl(0, 0%, 7%);
}
.illustration-photo {
  /* object-fit: cover; - the image keeps its aspect ratio and fills the given dimension. */
  object-fit: cover;
  height: 200px;
  margin: 20px;
  border-radius: 10px;
}
/* clamp(min, preferred, max) - Responsive */
p {
  font-size: clamp(0.875rem, 0.8123rem + 0.2086vw, 1rem); /* 16px / 14px */
}
.container-inner {
  width: clamp(327px, 18.6507rem + 5.9437vw, 384px);
  height: clamp(501px, 30.6542rem + 2.1898vw, 522px);
}
```
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

## Author

- Frontend Mentor - [@MaruchetO](https://www.frontendmentor.io/profile/MaruchetO)

## Acknowledgement
I really appriciate this tool [Font-size Clamp Generator](https://clamp.font-size.app/). I use it for responsive font-size, and adapt it for image and div size. 