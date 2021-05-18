# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot](images/screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://hembar.github.io/stats-preview-frontend-mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I didn't code the mobile display.
I've learned a lot about positioning and using <div>.
For some reason setting the colors in hsl method (hsl(277, 64%, 61%)) didn't work well.
The code worked but in Atom (the text editor I'm using) this error showed up:
"Fallback background-color (hex or RGB) should precede HSL background-color."
I googled this error but couldn't understand the explanation, so I used color converter (fron hsl to hex)
and "solved" the problem.
Also, I didn't find the proper effect for the picture to look like it should in the solution,
instead I added a <div> in the same size and position of the image and colored it with the purple of the challenge, then I lowered the <div> opacity.

```html
<img src="images/image-header-desktop.jpg" alt="header">
<div class="img"></div>
```
```css
.img {
  background-color: #aa5cdb;
  opacity: 0.4;
}
```

### Continued development

This challenge made me realize I need to practice more on positioning and using <div> more.

### Useful resources

- [Overlay Effect](https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio) -
In this article I found the solution that fit me to make the image colored purple.
- [HSLA to HEX Converter](http://standardista.com/webkit/ch7/hsla.html) - This is the only website I found that converted hsla to hex. Most of the websites can convert only hsl.

## Author

- Frontend Mentor - [@hembar](hhttps://www.frontendmentor.io/profile/hembars)
