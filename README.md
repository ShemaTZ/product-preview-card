# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
It is simple product review card challenge with responsive design
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](screenshot.png)


### Links

- Solution URL: [Github](https://github.com/ShemaTZ/product-preview-card)
- Live Site URL: [Add live site URL here](https://vercel.com/shematzs-projects/product-preview-card)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned


```html
<h1>Some HTML code I'm proud of</h1>

<div class="container">
    <div class="image">
      <picture>
        <source srcset="./images/image-product-mobile.jpg" media="(max-width: 600px)">
        <img src="./images/image-product-desktop.jpg" alt="Perfume Bottle" class="product-image">
      </picture>
    </div>
```
```css
.proud-of-this-css {
  color: papayawhip;
}

/* Responsive styles for mobile */
@media (max-width: 375px) {
    .container {
        flex-direction: column;
        max-width: 95vw;
        margin-top: 30px;
    }
    .image,
    .texts {
        width: 100%;
    }
    .image {
        height: 240px;
    }
    .product-image {
        height: 100%;
        width: 100%;
        object-fit: cover;
        border-radius: 10px 10px 0 0;
    }
    .texts {
        padding: 18px;
    }
}
```

### Useful resources

 -Github Copilot This is an amazing tool which helped me finally understand photo changing for mobile and pc. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Siket Terefe]
- Frontend Mentor - [@ShemaTZ](https://www.frontendmentor.io/profile/ShemaTZ)
