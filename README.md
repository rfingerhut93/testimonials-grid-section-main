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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: (https://rfingerhut93.github.io/testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Doing this challenge allowed me to practice using flexbox properties (flex-basis being the main property used) to create layouts using CSS. Using flexboxes made for easier modifications between the mobile layout and the desktop layout. 
```css
 #testimonial-grid-container, #main-left, #top, #bottom{
        display:flex;
    }
 #main-left {
        flex-direction: column;
        flex-basis: 75%   
    }
```
After completing this challenge, I realized that I prefer designing for the mobile layout first and then later making adjustments for a desktop/browser version. 

I also tried to make specific and helpful class and id names to make writing the CSS code a smoother process. Having specific class and id names made it so I didn't have to continuously look at my html code while working in CSS.
```html
<div id="testimonial-2" class="grid-item">
          <div class="header">
            <img src="./images/image-jonathan.jpg" alt="Jonathan profile picture">
            <div class="header-text">
              <p class="name">Jonathan Walters</p>
```

### Continued development

I want to continue working on Frontend challenges in order to continue practicing with my current HTML and CSS knowdlege, but also to dive deeper into javaScript.


### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=zJSY8tbf_ys&t=19066s) - This youtube bootcamp/tutorial took my HTML and CSS skills from zero to being able to complete this challenge. 
- [Example resource 2](https://yoksel.github.io/flex-cheatsheet) - I used this resource a ton while doing this challenge. It has great visuals and pairs it with code snippets.


## Author

- Frontend Mentor - [@rfingerhut93](https://www.frontendmentor.io/profile/rfingerhut93)


## Acknowledgments

As always, thanks to Zach Gollwitzer for being an amazing teacher!
