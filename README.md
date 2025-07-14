# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-  [Overview](#overview)
   -  [The challenge](#the-challenge)
   -  [Screenshot](#screenshot)
   -  [Links](#links)
-  [My process](#my-process)
   -  [Built with](#built-with)
   -  [What I learned](#what-i-learned)
   -  [Useful resources](#useful-resources)
-  [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-  View the optimal layout depending on their device's screen size
-  See hover and focus states for interactive elements

### Screenshot

![Desktop Design](<screenshot/AJ - Desktop Design.png>)
![Mobile Design](<screenshot/AJ - Mobile Design.png>)

### Links

-  Solution URL: [GitHub Repository](https://github.com/AJ-Tan/5.-Frontend-Mentor---Product-Preview-Card-HTML-SASS-.git)
-  Live Site URL: [GitHub Live Page](https://aj-tan.github.io/5.-Frontend-Mentor---Product-Preview-Card-HTML-SASS-/)

## My process

### Built with

-  Semantic HTML5 markup
-  CSS custom properties
-  CSS Grid
-  CSS SASS/SCSS

### What I learned

For this project, I decided to try something new, using SASS/SCSS. Right now, I'm just getting comfortable with it. So far, I'm loving the experience! It’s allowed me to write CSS in a much cleaner and more organized way.

```css
.product-card {
   ... &__content,
   &__header,
   &__footer,
   &__price {
      ...;
   }

   &__content,
   &__header {
      ...;
   }

   &__footer {
      ...;
   }

   &__tag {
      ...;
   }

   &__title,
   &__current {
      ...;
   }

   &__description {
      ...;
   }

   &__content {
      ...;
   }

   &__price {
      ...;
   }

   &__current {
      ...;
   }

   &__original {
      ...;
   }

   &__button {
      ... &:hover {
         ...;
      }
   }
}
```

### Useful resources

-  [SASS](https://sass-lang.com/) - SASS Documentation

## Author

-  GitHub - [AJ-Tan](https://github.com/AJ-Tan)
-  Frontend Mentor - [@AJ-Tan](https://www.frontendmentor.io/profile/AJ-Tan)
