# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

# Mobile Preview 

![screenshot]()

# Desktop Preview 

![screenshot]()

### Links

 - Source code: []()
 - Live website: []()

## My process

### Built with

- Semantic HTML5 markup
- SASS (SCSS)
- Flexbox
- Grid
- Mobile-first workflow

### What I learned

For this challenge, I really improved my Grid skills as I had to rearrange the cards to make it look like the design provided. The challenging part was making my SCSS orgnised, particularly the media queries. Overall, I enjoyed completing this challenge and look foward to using Grid in my future projects.

SCSS - Grid: 

```scss

@media (min-width: 900px) {
        &:first-of-type {
            grid-column: 1/3;
            grid-row: 1/2;
        }

        &:nth-child(2) {
            grid-column: 3;
        }

        &:nth-child(3) {
            grid-row: 2;
        }

        &:nth-child(4) {
            grid-row: 2;
            grid-column: -4/-2;
        }

        &:last-of-type {
            grid-row: 3/1;
            grid-column: 4/4;
        }
    }

```

### Continued development

For future developments, I should focus on building web pages to work on my HTML and CSS skills on layouts. Also, I should focus on working with more javascript projects in the junior section. Regarding my SCSS, I am considering to create seperate SCSS files to organise my code more efficiently.


## Author

- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
- Twitter - [@romila003](https://www.twitter.com/romila003)
