# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

Mobile View:

<img src='assets/images/2023-03-08-17-11-20.png' width='300'>

Desktop View:

<img src='assets/images/2023-03-09-10-22-10.png' width='600'>

### Links

- Solution URL: [Link](https://github.com/jerryren527/results-summary-component)
- Live Site URL: [Link](https://jerryren527.github.io/results-summary-component)
- Custom Figma File: [Link](https://www.figma.com/file/CoyaiGK65EDfxxG6gBsYqK/results-summary-component?node-id=0%3A1&t=ymMQQHLFnNxsrOfO-1)

### My process

### Built with

- HTML
- CSS
- Flexbox

### What I learned

To make a div element's width and height shrink proportionally to the screen's width:

1. Set the `width` and height properties of the div to 100% so that it takes up the entire width and height of its parent element.
2. Set the `max-width` property of the div to a fixed value or a percentage value to set maximum width of the div element.
3. Set the `aspect-ratio` property of the div to the desired aspect ratio. For example, 1/1.

```css
.overall-score-container {
  width: 100%;
  height: 100%;
  max-width: 142px;
  aspect-ratio: 1/1;
}
```
