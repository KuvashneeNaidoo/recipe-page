# Frontend Mentor - Recipe page solution

This is my solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### Screenshot

Large screen (desktop):
![Desktop](https://github.com/KuvashneeNaidoo/recipe-page/assets/105747929/a68f8647-8dfb-4a3c-863b-796e7cdda616)

Small screen (iPad mini - 768 x 1024)
![iPad Mini](https://github.com/KuvashneeNaidoo/recipe-page/assets/105747929/c48ed5fc-4a20-40ff-b733-13914e6c201e)

Small screen (iPhone 14 Pro - 430 x 932)
![iPhone 14 Pro Max](https://github.com/KuvashneeNaidoo/recipe-page/assets/105747929/94786dab-b938-456e-9dcb-710b36ac4dc1)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap

### What I learned

I learn't about how the marker pseudo-element can be used to target and style the numbers and bullet points
in the ordered and unordered lists.

```css
ol li::marker {
  color: hsl(14, 45%, 36%); /* The marker is the number */
  font-weight: 600;
}

ul li::marker {
  color: hsl(14, 45%, 36%); /* The marker is the bullet points */
  font-weight: 600;
}
```

### Continued development

I plan to use React.js to create the different components of this recipe page soon. I will also try using React Bootstrap to style the elements attractively.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - This helped me to learn about the ::marker CSS pseudo-element.

## Author

- Frontend Mentor - [@KuvashneeNaidoo](https://www.frontendmentor.io/profile/KuvashneeNaidoo)
