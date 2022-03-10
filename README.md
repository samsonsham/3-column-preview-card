# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://ik.imagekit.io/c5xc1x6srka/screenshot/screen_3-column-preview-card_L8k1fAqU6.png)

### Links

- Solution URL: [https://github.com/samsonsham/3-column-preview-card](https://github.com/samsonsham/3-column-preview-card)
- Live Site URL: [https://samsonsham.github.io/3-column-preview-card/](https://samsonsham.github.io/3-column-preview-card/)

## My process

- Set up SCSS file structure. Define all the styles given by style guide, including colours and font into SCSS files.
- Define components and setup corresponding DOM elements in HTML file.
- Mobile first, build each elements by with colours, alignment, and adjusting size.
- Then add media query for desktop view.

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- transparent border to avoid layout shifting by hover border.
- SCSS variable abstraction.
- reside media query under the corresponding style block to increase readability.
- CSS relative units

```css
.btn-learn-more {
  background-color: $clr-button;
  border: 0;
  font-size: 1.1rem;
  padding: 15px 30px;
  border-radius: 25px;
  border: 2px solid transparent;
}
.btn-learn-more:hover {
  border: 2px solid $clr-button;
}
```

### Useful resources

- [Add a CSS border on hover without moving the element](https://stackoverflow.com/questions/9612758/add-a-css-border-on-hover-without-moving-the-element) - This taught me how to make add hover border to element without layout shifting by defining a transparent border.

## Author

- Website - [Samson Sham](https://samson-sham-portfolio.vercel.app)
- Frontend Mentor - [@samsonsham](https://www.frontendmentor.io/profile/samsonsham)
- Twitter - [@samson_sham](https://www.twitter.com/samson_sham)
