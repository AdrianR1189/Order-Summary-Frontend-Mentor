# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

Desktop
![Desktop Screenshot](<Order-Summary-Frontend-Mentor(Desktop-1440w).png>)

Mobile
![Mobile Screenshot](<img src="Order-Summary-Frontend-Mentor(Mobile-375w).png" width="375">)

### Links

- [Solution URL](https://order-summary-adrianr1189.pages.dev/)
- [Frontend Mentor Challenge URL](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS media queries

### What I learned

I learned about using srcset to make responsive images. This is what I did to change the background for mobile and desktop.

```html
<picture class="backgroundImg">
  <source
    srcset="components/images/pattern-background-mobile.svg"
    media="(max-width: 500px)"
  />
  <source srcset="components/images/pattern-background-desktop.svg" />
  <img
    class="backgroundImg"
    src="components/images/pattern-background-desktop.svg"
    alt="background image"
  />
</picture>
```

### Useful resources

- [MDN Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - Great resource overall but this really helped on this project with responsive images.
- [Drop Shadow CSS Generator](https://webcode.tools/css-generator/drop-shadow) - Drop shadow generator that I used for the "Proceed to Payment" button.

## Author

- My Github - https://github.com/AdrianR1189
- Frontend Mentor - [@AdrianR1189]https://www.frontendmentor.io/profile/AdrianR1189
