# Order summary card solution

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
- [Acknowledgments](#acknowledgments)

## Overview
You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size ✔

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [Click here for source code](https://github.com/UbaidRussell/Order-summary-component)
- Live Site URL: [Add live site URL here](https://ubaidrussell.github.io/Order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Developing a media query specifically for this website was a great learning experience. I learned how to use the @media rule to define different style rules for different media types/devices. I also learned how to use the @media rule along with the and operator to define a media query that consists of more than one part.

```css
@media only screen and (min-width:200px) and (max-width:500px){
    .container {
        width: 350px;
      } 
      .illustration-image{
        width: 350px;
    }
    .inner-container{
        width: 300px;
    }
    .music-icon{
        margin-right: 10px;
    }
    a{
        display: none;
    }
}
```

### Continued development
We're planning to add some cool features in the future. Stay tuned!

### Useful resources

- [Example resource 1](https://fonts.google.com/specimen/Red+Hat+Display) - This helped me for the font. I really liked this pattern and will use it going forward.

## Author

- Website - [Ubaid Russell](https://ubaidrussell.com/)
- Frontend Mentor - [@ubaidrussell](https://www.frontendmentor.io/profile/ubaidrussell)
- Twitter - [@UbaidRusell](https://www.twitter.com/UbaidRusell)

## Acknowledgments
Shout out to the team at Frontend Mentor for creating such a great platform for developers to learn and grow!
