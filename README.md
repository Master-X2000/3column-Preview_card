# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![view](/images/Screenshot%20.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I understood how to make use of the data- attribute in html and makeing use of it in my css

```html
<button class="button" data-type="accent-1" >Learn More</button>
<button class="button" data-type="accent-2" >Learn More</button>
<button class="button" data-type="accent-3" >Learn More</button>
```

```css
.button[data-type="accent-3"]{
    --FONT-COLOR:var(--COLUMN-THREE);
}

.button[data-type="accent-2"]{
    --FONT-COLOR:var(--COLUMN-TWO);
}

.button[data-type="accent-1"]{
    --FONT-COLOR:var(--COLUMN-ONE);
}
```

## Author
Created by Odezime Excel

- Website - [Odezime Excel](https://www.your-site.com)
- Frontend Mentor - [@Master-X2000](https://www.frontendmentor.io/profile/Master-X2000)
- Twitter - [@Odezime Excel](https://www.twitter.com/EOdezime66661)



## Acknowledgments

Thanks to Kevin Powell no a detailed explaination on how to make us ot data attributes.
