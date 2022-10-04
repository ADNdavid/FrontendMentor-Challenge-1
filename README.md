# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/product-preview-card-component-using-responsive-design-and-css-grid-8korZ7xBPV)
- Live Site URL: [GitHub Pages](https://adndavid.github.io/FrontendMentor-Challenge-1/)

## My process

### Built with

- Media Queries
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- Use the properties **grid-template-areas** and **grid-area** to center a tag that contains the card.

```css
.container{
    display:grid;
    grid-template-areas:
        ". . ."
        ". card ."
        ". . .";
    }
.item {
    grid-area: card;
    }
```

- How to use **Media Queries** to make a webpage responsive for different types of devices: 

```css
@media (max-width: 768px) {
    /** Mobile design **/
    {styles}
```

## Author

- GitHub - [@ADNdavid](https://github.com/ADNdavid)
- Frontend Mentor - [@ADNdavid](https://www.frontendmentor.io/profile/ADNdavid)
- LinkedIn - [Anderson Sepúlveda](https://www.linkedin.com/in/adndavid/)

## Acknowledgments

I want to give a special thanks to [@DanielMejiaB](https://github.com/DanielMejiaB) for supporting me with a lot of doubts that I had been solving this challenge. And of course, all the people that give feedback on Frontend Mentor.
