# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/jayrnoel/results-summary-component](https://github.com/jayrnoel/results-summary-component)
- Live Site URL: [https://venerable-klepon-f565aa.netlify.app/](https://venerable-klepon-f565aa.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This practice is a small project to help me practice flexbox again. I applied `flex-basis` because I don't think that the results and summary are equal.

My first impression on the project was how to make the results div bleed to the viewport on top. I have forgotten that I can control individal corners of the box.
The syntax goes:

```css
border-radius: 0 0 3rem 3rem;
/* top left, top right, bottom right, bottom left */
```

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius) - This helped understand controlling the border-radius for each corner of the box.
- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is the resource I always go to whenever I get stuck on flexbox.
- [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies) - A fun and free resource for practicing flexbox. This helped me with the concepts of flexbox stick.

## Author

- Frontend Mentor - [@jayrnoel](https://www.frontendmentor.io/profile/jayrnoel)
