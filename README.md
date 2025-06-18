# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [solution URL here](https://www.frontendmentor.io/solutions/huddle-landing-page-mobile-first-VTd_DoB9q3)
- Live Site URL: [live site URL here](https://ttar007.github.io/Huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have added an animation to CTA button.

```css
.CTA-register:hover {
  background-color: var(--Soft-Magenta);
  color: var(--white);
  animation-name: padding-increase;
  animation-duration: 500ms;
  animation-fill-mode: forwards;
}

@keyframes padding-increase {
  from {
    padding: 0.8rem 4.8rem;
  }
  to {
    padding: 0.8rem 6rem;
  }
}
```

### Continued development

Next project, I will focus on writing the html and css more organized and easy to understand.

## Author

- Website - [Not available]()
- Frontend Mentor - [@TTAR007](https://www.frontendmentor.io/profile/TTAR007)
- Twitter - [@T_TAR_007](https://www.twitter.com/T_TAR_007)
