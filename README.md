# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

In this challenge, I was tasked to mirror the design of a QR code using html and css.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. I began with the design process and formulating a plan. 
2. Opened a .html file and started to layout the skeleton of the challenge.
3. Used a .css file to style and postion the commands from the .html file

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this challenge, I began to understand the necessity of planning out the design. First, I needed to set a background. Second, I needed to set a white container at the center of the page. Third, I needed to correctly position the images and text. From the challenge, I learned how to properly use flex box to position a white container at the center of the page. To begin, the html and body were indicated to have a height of 100%. Then the background (div classed main) would be indicated to have a width and height of 100% and flexbox would be established. This would center the white container (div classed container) toward the center of the page. 

```css
html,
body {
  height: 100%;
}

.main {
  width: 100%;
  height: 100%;
  background-color: hsl(212, 45%, 89%);

  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Continued development

I want to focus a lot more on the initial planning of the design. Along with this, I want to gain more knowldge on html and css especially using flexbox.
