# news-homepage-main
A responsive news homepage solution built with HTML, CSS Grid, Flexbox, and JavaScript for the Frontend Mentor challenge.
# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot


![](./assets/images/image.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/aliluya669-lgtm/news-homepage-main)
- Live Site URL: [Add live site URL here](https://aliluya669-lgtm.github.io/news-homepage-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- CSS Grid (`grid-template-areas`)
- Mobile-first responsive design
- Vanilla JavaScript (for mobile menu naviagtion)


### What I learned

During this project, I gained a much deeper understanding of **CSS Grid**, particularly how to structure complex layouts using `grid-template-areas`. I also learned how to build an interactive mobile drawer menu using simple JavaScript class toggling and how to use root coloring.


```css
/* Layout map using grid-template-areas */
.news-main {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  grid-template-areas: 
    "img   img   side"
    "title desc  side"
    "card1 card2 card3";
}
```
```js
function openMenu() {
  nav.classList.add('is-active');
  overlay.classList.add('is-active');
  document.body.style.overflow = 'hidden';
}
```

### Continued development

In future projects, I want to keep practicing:

- Creating more complex dynamic CSS Grid layouts.

- Enhancing accessibility (a11y) for interactive elements like mobile modals and navigation menus.

- Adding smooth CSS animations and micro-interactions.

### AI Collaboration

I collaborated with ChatGPT to speed up my learning process during this challenge:

Tools used: Gemini / ChatGPT

How I used it: Understood how CSS Grid mapping (grid-template-areas) works, set up responsive layout rules, and debugged mobile menu overlay behavior.

Key benefits: Allowed me to quickly learn CSS Grid visually and structure clean CSS and JS code efficiently.

## Author

- Frontend Mentor - [@aliluya669-lgtm](https://www.frontendmentor.io/profile/aliluya669-lgtm)
- GitHub - [@aliluya669-lgtm](https://github.com/aliluya669-lgtm)
