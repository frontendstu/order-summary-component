# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- [📦 Solution:](https://github.com/frontendstu/order-summary-component/)
- [🌏 Live Site URL:](https://frontendstu.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The Order Summary Component challenge ended up being a pretty straightforward challenge. There were a couple of aspects I had to think on and that was primarily with the background image positioning. Once I got that figured out (see below snippet), I was able to breeze through the rest of the project. I am finding that working in vanilla CSS is very referring back and fourth and I found that this made me make a couple of mistakes. I will stick with using Vanilla CSS a bit more just so I can demonstrate that I’m not reliant on Sass, but honestly who wouldn’t use Sass!

```css
body {
  background: var(--body-bg) var(--body-bg-img) repeat-x top / contain;
}
```

## Author

- GitHub - [@frontendstu](https://github.com/frontendstu/)
- Frontend Mentor - [@frontendstu](https://www.frontendmentor.io/profile/frontendstu)
