# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

This is live here: https://cheery-lebkuchen-09bb94.netlify.app/

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the interface animate on the initial load

## My process

### Built with

- HTML
- CSS
- Vue.js

### What I learned

Create arrow with rounded corners using CSS only

```css
#submit .arrow::before,
#submit .arrow::after {
  content: '';
  position: absolute;
  left: 0;
  height: 100%;
  background-color: white;
}
#submit .arrow::before {
  top: 0;
  width: 3px;
  border-radius: 55px 55px 0 0;
  transform-origin: top left;
  rotate: -45deg;
}
#submit .arrow::after {
  bottom: 0;
  width: 3px;
  border-radius: 0 0 55px 55px;
  transform-origin: bottom left;
  rotate: 45deg;
}
```
