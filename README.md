# Frontend Mentor <br /> Social media dashboard with theme switcher

Check out the live website [here](https://cocky-hoover-cbbd3a.netlify.app/)
![Design preview for the Social media dashboard with theme switcher coding challenge](./design/desktop-preview.jpg)

This is a solution to the [Social media dashboard with theme switcher challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-media-dashboard-with-theme-switcher-6oY8ozp_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Your challenge is to build out this Social Media Dashboard and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Toggle color theme to their preference

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Gulp Sass
- Flexbox
- CSS Grid
- Javascript
- Accessibility
- Mobile-first workflow

### What I learned

Updating a CSS Custom Properties with JavaScript

```css
:root {
  --mouse-x: 0px;
  --mouse-y: 0px;
}
```
Perhaps you use them to set a position:

```css
.mover {
  left: var(--mouse-x);
  top: var(--mouse-y);
}
```
To update those values from JavaScript, you’d:
```js
let root = document.documentElement;

root.addEventListener("mousemove", e => {
  root.style.setProperty('--mouse-x', e.clientX + "px");
  root.style.setProperty('--mouse-y', e.clientY + "px");
});
```

### Useful resources

- [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for CSS flexbox. I really liked this pattern and will use it going forward.
- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is an amazing article which helped me finally understand Grid. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Sam Bonfanti](https://sambonfanti.club/)
- Linkedin - [sambonfanti](https://www.linkedin.com/in/sambonfanti/)

## Acknowledgments

* [CSS-TRICKS](https://css-tricks.com/)
* [Netlify](https://www.netlify.com/)
* [Frontend Mentor](https://www.frontendmentor.io/challenges)
