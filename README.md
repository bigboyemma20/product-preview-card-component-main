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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: 
- Live Site URL: https://bigboyemma20.github.io/product-preview-card-component-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox and Grid
- Responsive design using media queries
- Mobile-first workflow
- Google Fonts (Fraunces and Montserrat)

### What I learned

While working on this project, I practiced:

- Structuring a simple responsive layout using CSS Grid.

- Using the picture element for responsive images based on screen size.

- Applying clamp() for fluid typography sizing across devices.

- Smooth hover transitions on buttons.

```css
button {
    background-color: var(--Green-500);
    color: var(--White);      
    font-weight: 600;
    padding-block: .7rem;
    border-radius: 10px;
    border: none;
    cursor: pointer;
    transition: background-color 0.4s ease-in-out;
}

button:hover {
    background-color: var(--Green-700);
}

```


### Useful resources

-(https://web.dev/learn/design) This helped me figure out how to use grid. 

- https://www.frontendmentor.io/learning-paths/building-responsive-layouts--z1qCXVqkD



## Author

- - My Github - [Emmanuel Quarm](https://github.com/bigboyemma20)
- Frontend Mentor - [@bigboyemma20](https://www.frontendmentor.io/profile/bigboyemma20)
- Twitter - [@freshmanuel11](https://www.twitter.com/freshmanuel11)


