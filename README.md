# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



### Links

- Solution URL: https://github.com/Anubliss-0/Meet-Landing-Page
- Live Site URL: https://anubliss-0.github.io/Meet-Landing-Page/


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

unless placed in a div, content below an SVG will cover the SVG when there is no avaialbe space.

The grid-gap property does not accept the minmax() function, but an empty grid column can be used to create a working gap whic resizes to a minimum and maximum.


```css
.photos {
  display: grid;
  grid-template-columns:
    minmax(39px, 165px) minmax(163.9998px, 280px) minmax(11px, 30px)
    minmax(163.9998px, 280px) minmax(11px, 30px) minmax(163.9998px, 280px) minmax(
      11px,
      30px
    )
    minmax(163.9998px, 280px) minmax(35px, 165px);

  width: 100%;
}
```

### Useful resources

- [Example resource 1] https://marketplace.visualstudio.com/items?itemName=cipchk.cssrem
- [Example resource 2] https://www.calculator.net/percent-calculator.html?c22par1=165&c22par2=1440&ctype=22&x=60&y=32#pctcommon


## Author
Anubliss_


