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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [https://github.com/gchristofferson/testimonials-grid-section](https://github.com/gchristofferson/testimonials-grid-section)
- Live Site URL: [https://gchristofferson.github.io/testimonials-grid-section/](https://gchristofferson.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM methodology


### What I learned

This was a fun testimonial section challenge that tested my CSS Grid skills.  What I found in this project was that flexbox was much better to use for mobile and tablet layouts.  For the final desktop layout, I simply switched `display: flex` to `display: grid` on the `.main` section.  The `column gap` and `row gap` properties carried over from flex.  Also, as far as naming the testimonial blocks in this project, I opted to use just one class with a hyphen and a number (i.e. `.testimonial-1`). Instead of two classes (usually a default and a modifier).  What I did instead was use an attribute selector I haven't really used before for the default styles:

```css
[class^="testimonial-"]
```
In other words, this means: "select all classes that have a substring value that begins with 'testimonial-'. By using the hyphen in my class name, I was able, in effect, to create both a default and modifier using one class name.  I'm not sure the advantage of this as opposed to using two classes, but it was fun, and I'm always looking for ways to write more concise code.

### Continued development

I liked using the attribute selector in this project, and I am going to look for other ways to incorporate this into future projects if it means making my code more concise and readable.

### Useful resources

- [MDN Web Docs - Attribute selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors) - This MDN article helped me understand more options I can put in my toolbox for selecting elements. Attribute selectors are awesome and open up ways to be more creative with CSS.

## Author

- Frontend Mentor - [@gchristofferson](https://www.frontendmentor.io/profile/gchristofferson)
- Twitter - [@GreggChristoff2](https://twitter.com/GreggChristoff2)
