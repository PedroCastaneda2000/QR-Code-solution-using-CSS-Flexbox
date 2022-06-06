# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
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

1. I began with the design process. Looked where everything need to go.
2. Opened a .html file and started to layout the skeleton of the challenge.
3. Used a .css file to style and postion the commands from the .html file

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this challenge, I began to understand the necessity of planning out the design. From the sample images, I knew that a white container would always be at the center of the page. I decided to center the div that represented the white container using positioning. From there, I used flexbox to center the text and the QR image within the white container. Then I used grid and grid-template-rows to seperate the text and the QR image to their respected positions (QR image top and text bottom).

To see how you can add code snippets, see below:

```css
.proud-of-this-css {
  height: 450px;
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  display: grid;
  grid-template-rows: 1fr 1fr 1fr 1fr;
}
```

### Continued development

I want to focus a lot more on the initial planning of the design. Along with this, I want to gain more knowldge on html and css especially the CSS cascade principles.
