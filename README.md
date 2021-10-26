# Frontend Mentor <br /> Social media dashboard with theme switcher

Site URL: [Live Site here](https://hungry-hugle-940d05.netlify.app)
![Design preview for the Social media dashboard with theme switcher coding challenge](./design/desktop-preview.jpg)

This is a solution to the [Social media dashboard with theme switcher challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-media-dashboard-with-theme-switcher-6oY8ozp_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [solution URL here](https://www.frontendmentor.io/solutions)
<!-- - Live Site URL: [live site URL here](https://youthful-northcutt-b93b58.netlify.app/) -->

## My process

### Built with

- Semantic HTML5 markup
- SCSS - For styles
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

@mixin and @include

```scss
@mixin square($size, $radius: 0) {
  width: $size;
  height: $size;

  @if $radius != 0 {
    border-radius: $radius;
  }
}

.avatar {
  @include square(100px, $radius: 4px);
}
```
css
```css
.avatar {
  width: 100px;
  height: 100px;
  border-radius: 4px;
}
```

### Useful resources

- [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for CSS flexbox. I really liked this pattern and will use it going forward.
- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is an amazing article which helped me finally understand Grid. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Sam Bonfanti](https://sambonfanti.club/)
- Frontend Mentor - [@CodeMaster7](https://www.frontendmentor.io/profile/CodeMaster7)
- Linkedin - [sambonfanti](https://www.linkedin.com/in/sambonfanti/)

## Acknowledgments

* [CSS-TRICKS](https://css-tricks.com/)
* [Netlify](https://www.netlify.com/)
* [Frontend Mentor](https://www.frontendmentor.io/challenges)
