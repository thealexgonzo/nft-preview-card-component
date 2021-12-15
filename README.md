# NFT preview card component

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
- See hover states for interactive elements

### Screenshot

![](images/desktop-design.jpg)
![](images/active-states.jpg)

### Links

- [Live Site URL](https://thealexgonzo.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS
- Flexbox
- Mobile-first workflow

### What I learned

Fun little project, finished it in a day and it pushed me to remember how to center elements on the screen and also how to create overlay effects on images.

Proud of this CSS:

```css
.image--overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgb(0, 255, 247, 0.5);
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
}
```

### Continued development

I'm very happy with how this project turned out. I managed to finish it very quickly a was able to go over some concepts which I used to struggle with in the past, such centering elements on the screen and working with images to create and overlay effect. Other than that it was all pretty straight forward.

### Useful resources

- [dcode](https://www.youtube.com/watch?v=exb2ab72Xhs&ab_channel=dcode) - This resource helped me figure out how to create the overlay effect on the image.

## Author

Jesus Alejandro González Rodríguez
