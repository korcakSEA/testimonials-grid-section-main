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
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](![alt text](image.png))


### Links

- Solution URL: (https://github.com/korcakSEA/testimonials-grid-section-main.git)
- Live Site URL: (https://korcaksea.github.io/testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I really enjoyed while doing this project. Because seeing the result after the thought process is made me happy. 
I did not know anything couple of months ago. And and repetition and process satisfy.

Here in this project I had a chance to use grid property while placing the cards: grid-template-areas and grid-template-columns/spans

To see how, may see the code snippet below:


```css
@media (min-width: 1024px) {
    .testimonial{
      /* grid-template-columns: repeat(4, 1fr); Grid template columns with span  */
      
      
      /* with grid-template-area */
      grid-template-areas:
      'one one two five'
      'three four four five';
     
    }

    /* .span-column{
        grid-column: span 2;
    }

    .span-row{
        grid-column: 4/5;
        grid-row: 1/3;
    } */

}
```




### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Frontend Mentor - [@korcakSEA](https://www.frontendmentor.io/profile/korcakSEA)


