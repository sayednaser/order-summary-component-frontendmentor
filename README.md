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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.[png])

### Links

- [Solution URL](https://github.com/sayednaser/order-summary-component-frontendmentor)
- [Live Site URL](https://sayednaser.github.io/order-summary-component-frontendmentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned

This is my second challenge. Overall, it wasn't so different from my first challenge. The major differences are

- I started using HTML5 semantics for better accessibility.
- I started using Flexbox for layout.

To center the card vertically in the viewport, we simply use flexbox container.

```css
.card-container {
  min-height: 100vh;
  /* margin-top: 10.15rem; */
  display: flex;
  align-items: center;
  justify-content: center;
```

---

Three background-related properties to pay attention for

```css
.card-container {
  background-image: url(images/pattern-background-desktop.svg);
  background-repeat: no-repeat;
  background-size: 100% auto;
}
```

---

When choosing between anchor tag and button tag to implement a button, the general rule is if 'href' attribute has a meaning, go for an anchor. Otherwise, implement it using a button tag.

```html
<a href="" class="card-proceed-btn btn u-margin-medium">Proceed to Payment</a>
```

---

To center the text vertically in a button, simply use a line-height with the best result. To do it accurately, choose a line-height with the same height as the button. Alternately, you could use padding.

```css
.card-proceed-btn {
  line-height: 3.3;
}
```

---

For the subsription section in the card, An alternate solution for the vertical centering is

- Display all the elements as inline or inline-block
- Make sure that the container has a proper height, if not, we can define it or use a pseudo element.
- "vertical-align: middle" for all the elements.

### Continued development

- To continue using flexbox for 1-D layouts.

- To pay more attention for HTML5 semantics.

## Author

- Github - [@sayednaser](https://github.com/sayednaser)
- Frontend Mentor - [@sayednaser](https://www.frontendmentor.io/profile/sayednaser)
