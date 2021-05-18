# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

I took this socia-proof-challenge from the frontend mentor website to improve my CSS & HTML skills and get familer with Flexbox and Grid supported by CSS which makes layout in website a much easier task. This version of code is not mobile-friendly yet and still need to make it compatible either by use of Bootstrap or Media Queries.

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![image](https://user-images.githubusercontent.com/42742924/118594059-805f3f00-b7c8-11eb-9662-70450e6ccb78.png)

This is the desktop compatible version by using  plain CSS & HTML.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

The process of building this site social-proof-section was starting with the heading-section CSS class as per my styles.css, then leading towards the rating section and finally the cards at the bottom of the pages. Here, each section is divided into different class which makes it easier to style when it comes in different class with different Elements. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

The main knowledge I gained in this challenge is the use of CSS flexbox which makes it easier to layout the components and style them accordingly. Nevertheless, CSS grid has also been used but the primary focus of use was CSS flexbox where elements stacked in row can easily be changed into columms with few lines of code. 

Also, another thing I learned was the flexbox are applied in the parent elements not the element themselves.



```css
.container {
  padding: 7% 7% 10% 7%;
  display: grid;
  grid-template-columns: auto auto;
  grid-template-rows: 150px;
  gap: 70px;
}
/* Specifying two auto in grid-template-colums makes two colums & specifying 3 auto in the same place will make 3 colums easily.*/
```

```css
.cards-section {
  grid-column: span 2;
  margin-top: 50px;
  display: flex;
}
```

![image](https://user-images.githubusercontent.com/42742924/118597526-848d5b80-b7cc-11eb-9ddc-606a95cbd754.png)

![image](https://user-images.githubusercontent.com/42742924/118597542-8a833c80-b7cc-11eb-916f-c564f31e9f4e.png)

The above mentioned cards-section code magically changed the row lined components to colums with few lines of code which makes a life much easier.

### Continued development

For future development this site can be made mobile friendly via using Bootstrap or media queries.
### Useful resources

- (https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - This helped me a lot in CSS Flexbox which has been applied in the Cards section.
- (https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids) - This helped me understand the GRID system where colums can be added with only adding one more auto in the top code.


## Author

- Website - [Aakib Shah Sayed](https://www.your-site.com)

