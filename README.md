# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./designs/Desktop%20Design.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I was able to center my work properly and also able to fit an image perfectly within a div.
Also learnt how to work well with a project when two sizes of pictures are required.

```html
<picture>
    <div class="photo">
        <div class="desktop-photo"><img src="/images/image-product-desktop.jpg" alt="perfume picture"  class="desktop"></div>
    
        <div class="mobile-photo"><img src="images/image-product-mobile.jpg" alt=""    class="mobile"></div>
    </div>
</picture>```

```css
main {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
```

### Continued development
I'd continue learning ways to properly center elements and also how to fit images perfectly within divs.

## Author

- Website - [Tbahd](https://olukolejames.netlify.app)
- Frontend Mentor - [@tbahd](https://www.frontendmentor.io/profile/tbahd)
- Twitter - [@tbahd](https://www.twitter.com/tbahd2)
