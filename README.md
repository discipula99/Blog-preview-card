# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%20Solution%20Blog%20Card.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

My mistakes and how I resolved them, see below:

#### ==In HTML==
In the snippet below the code help me with having the boder-radius functioning correctly, because without it my code didn't work, even on the tag img itself. So the only way that it could work without having a cascade of problems was this

```html
    <div class="card-image">
        <img src="assets/images/illustration-article.svg" alt="illustration" class="blog-image">
    </div>
```

#### ==In CSS==

```css
.blog-preview-card {
  width: 384px; /*This is the width of the container*/
  max-width: 90%; /*This rapresent the width in which if the screen become smaller and smaller the size of the container will only take 90% of the screen*/
}
```

### Useful resources

- [nekoCalc](https://nekocalc.com/) -This is an amazing site to help you to calculate much faster the size fonts, from px to em and viceversa and much more. 

## Author

- Frontend Mentor - [@discipula99](https://www.frontendmentor.io/profile/discipula99)


