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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/screenshot.jpeg)

### Links

- Solution URL:
- Live Site URL: https://github.com/Joseevb/NFT-preview-card-component

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
  **Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This challenge has helped me learn more about how to properly style images with CSS and how to add different styles when hovering on elements.

Here is some CSS that I'm proud off:

```css
.nft {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.nft:hover .view {
  display: block;
  cursor: pointer;
}

.nft img {
  border-radius: 0.5rem;
}

.nft-img {
  position: relative;
}

.view {
  background-color: rgb(var(--clr-primary-accent) / 0.5);
  padding: 42%;
  position: absolute;
  display: none;
}
```

## Author

- Frontend Mentor - [@Joseevb](https://www.frontendmentor.io/profile/Joseevb)
- LinkedIn - [Jose Vasquez](https://www.linkedin.com/in/jose-vasquez-874a05153/)
