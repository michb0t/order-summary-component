# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![Desktop-preview](https://user-images.githubusercontent.com/81781093/132121502-842482fa-db8a-48e4-a4ee-fa40939c7f87.PNG)
![Desktop-active](https://user-images.githubusercontent.com/81781093/132121503-f97736eb-42be-4d4c-8db4-7732a3d514c4.PNG)

### Links

- Solution URL: https://github.com/michb0t/order-summary-component
- Live Site URL: https://michb0t.github.io/order-summary-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- Setting a background image using CSS. I also added a background color which I initially thought wouldnt be possible since there is a background image but it worked! 

      body {
          background-image: url(images/pattern-background-mobile.svg);
          background-repeat: no-repeat;
          background-size: cover;
          background-color: hsl(225, 100%, 94%);
          text-align: center;
      }

- Adding a flex display to the pricing section which worked out well. I'm getting used to applying flexboxes.

      .annual-plan {
          display: flex;
          justify-content: space-evenly;
          background-color: hsl(225, 100%, 98%);
          border-radius: 0.625rem;
          align-items: center; 
          margin: 1.25rem 0.9375rem;
      }

### Continued development

Some areas that I feel need more improvement:
- Centering the container to the page. I know it's generally setting the margin to 0:auto, but sometimes I still have trouble understanding how to center my divs.

### Useful resources

-https:/https://developer.mozilla.org//stackoverflow.com/
-https://developer.mozilla.org/

## Author

- Website - https://github.com/michb0t
- Frontend Mentor - https://www.frontendmentor.io/profile/michy-p
- Twitter - https://twitter.com/michbot7

