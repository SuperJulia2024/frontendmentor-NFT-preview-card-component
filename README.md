# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/SuperJulia2024/frontendmentor-NFT-preview-card-component](https://github.com/SuperJulia2024/frontendmentor-NFT-preview-card-component)
- Live Site URL: [https://superjulia2024.github.io/frontendmentor-NFT-preview-card-component](https://superjulia2024.github.io/frontendmentor-NFT-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Putting a semi-transparent layer over an image

```html
<div class="img-container">
  <div class="transparent-layer"><img src="./images/icon-view.svg" alt="View icon"></div>
</div>
```
```css
main .img-container {
  width: 330px;
  height: 330px;
  background-position: center;
  background-size: cover;
  background-image: url("../images/image-equilibrium.jpg");
  position: relative;
}

main .img-container .transparent-layer {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  visibility: hidden;
  background-color: var(--cyan-color-t);
}

main .img-container:hover .transparent-layer {
  visibility: visible;
  
```

## Author

- Frontend Mentor - [@SuperJulia2024](https://www.frontendmentor.io/profile/SuperJulia2024)

## Acknowledgments

Thanks to FrontEndMentor for this amazing challenge
