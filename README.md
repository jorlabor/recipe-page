# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover states for interactive elements where relevant (attribution links)

### Screenshot

![Recipe page solution screenshot](./preview.jpg)

> Tip: Replace `preview.jpg` with your own screenshot (for example `screenshot.jpg`) once you capture the finished page.

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/recipe-page-using-semantic-html-and-bem-css-E1UvuxGLs1](https://www.frontendmentor.io/solutions)
- Live Site URL: [https://recipe-page-labor.netlify.app/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup (`main`, `section`, lists, `table`)
- CSS custom properties for colors, fonts, and spacing
- Flexbox for vertical section layouts
- Local `@font-face` fonts (Young Serif and Outfit)
- Mobile-first workflow with `min-width` media queries

### What I learned

- Structure the HTML before styling so sections are easier to target
- Browser defaults (heading weight, list padding, table borders) need intentional overrides
- Font size and available width both affect how a title wraps
- Full-bleed images on mobile vs inset, rounded images inside a desktop card
- CSS variables keep the style guide colors and spacing consistent
- A nutrition block is tabular data, so a `<table>` can be simpler than rebuilding it with flex or grid

### Continued development

- Practice accessible tables (`th` with `scope="row"`)
- Refine responsive breakpoints and card max-widths by eye against designs
- Explore shared layout classes to reduce repeated padding rules

### Useful resources

- [MDN - @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) - Loading local font files
- [MDN - Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) - Mobile-first breakpoints
- [MDN - CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - Reusable design tokens
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Flex layout reference

### AI Collaboration

- Used Cursor as a learning partner while building this challenge
- Focused on HTML structure first, then mobile styles, then desktop layout
- Used hints and code review instead of pasting a full finished solution, so I could practice debugging (title wrapping, list markers, full-bleed image, nutrition table)

## Author

- Frontend Mentor - [@jorlabor](https://www.frontendmentor.io/profile/jorlabor)
- GitHub - [https://github.com/jorlabor](https://github.com/jorlabor)
