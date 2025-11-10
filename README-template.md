# Frontend Mentor - Product list with cart solution

This is a solution to the [Product list with cart challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Add items to the cart and remove them
- Increase/decrease the number of items in the cart
- See an order confirmation modal when they click "Confirm Order"
- Reset their selections when they click "Start New Order"
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Live Site URL: [Live Project](https://procarts.netlify.app/)

## My process

### Built with

- [React](https://reactjs.org/) - JS library
- CSS custom properties
- Tailwind CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

With the help of this project, I was able to build more on my knowledge about React Context.

To see how you can add code snippets, see below:

```js
function handleGetImagePath(productImage) {
  let fileName = productImage.category || productImage.name;

  fileName = fileName
    .normalize("NFD") //remove accents like é, ñ, ü
    .replace(/[\u0300-\u036f]/g, "") //remove diacritics
    .replace(/\s+/g, "-") //replace spaces with hyphens
    .toLowerCase(); //converts to lower case

  return `/assets/images/image-${fileName}-thumbnail.jpg`;
}
```

### Continued development

I need to improving more on my context knowledge

## Author

- Website - [Ebhamen Joshua](https://ebhamen-joshua-portfolio.vercel.app/)
- Frontend Mentor - [@Isaacjosh23](https://www.frontendmentor.io/profile/Isaacjosh23)
- Twitter - [@codes_from_josh](https://x.com/codes_from_josh?t=0p-3oxHXbpKMiF47B1XEIg&s=09)

## Acknowledgments

I want to appreciate my mentor Damilare and a friend of mine Lucky
