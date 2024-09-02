# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](assets/images/screenshot.png)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/idk-if-this-is-responsive-0L_vlYbCmp
- Live Site URL: https://high-rolls.github.io/blog-preview-card-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned about the `gap` property in CSS, so instead of doing this:
```css
.card > *:not(:last-child) {
    margin-bottom: 1rem;
}
```
I could do this instead:
```css
.card {
    ...
    display: flex;
    flex-direction: column;
    gap: 1rem;
    ...
}
```

### Continued development

I would like to learn more about organizing my HTML and CSS in ways that make them reusable and flexible to changes.

### Useful resources

- [mdn web docs](https://developer.mozilla.org/en-US/docs/Web) - This is the only reference to CSS, Javascript and HTML one could ask for, it has everything written down in an easy to find way.
- [This Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a very succint guide on using flex and its various properties.

## Author

- Website - [high-rolls](https://high-rolls.github.io/)
- Frontend Mentor - [@high-rolls](https://www.frontendmentor.io/profile/high-rolls)

## Acknowledgments

I acknowledge the vast ocean of information available on the internet, in which many questions have been answered before and are still easily available by just doing a quick search.
