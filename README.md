# Frontend Mentor - Product Preview solution

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

Build a responsive product preview card component that matches the provided Frontend Mentor design for both desktop and mobile layouts.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover-ready button styling and a polished product card presentation

### Screenshot

I have both desktop and mobile versions working in the browser. I may add an embedded screenshot here.

### Links

- Solution URL: https://github.com/Hermit-commits-code/Product-Preview-Card
- Live Site URL: Not deployed yet

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive media queries
- Google Fonts
- Font Awesome

### What I learned

This project helped me practice structuring a card layout with Flexbox and then adapting that layout for smaller screens with a media query. I also got a better understanding of when to use `object-fit: cover` to control image cropping inside a fixed image area.

I also learned that responsive design is not just about shrinking sizes. On desktop, the card works best as a two-column layout, while on mobile it needs to stack vertically and use a different image crop.

### Continued development

I want to keep improving how I approach responsive layouts, especially by making the desktop layout first and then writing cleaner mobile overrides. I also want to refine the image swapping approach by using a `picture` element so mobile devices load the mobile-specific image asset.

### Useful resources

- Frontend Mentor - https://www.frontendmentor.io/ helps me practice working from real UI designs.
- MDN Web Docs - https://developer.mozilla.org/ is useful for checking CSS behavior, especially media queries, flexbox, and image sizing.

## Author

- GitHub - https://github.com/Hermit-commits-code
