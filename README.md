# NFT-Card-Component

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

- Create the basic HTML framework for an NFT product card component 
- Use CSS to style the page to match the design spec and make responsive

## My process

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

Another great challenge, I found my skills had improved when building out the card component and it's separate elements, but began to need assistance when I was trying to figure out some of the hover effects and also making sure the component was responsive when used on a phone. I was able to better utilise relative sizing rather than relying on pixels, I also found my understanding of positioning on a page has greatly improved, especially when using flex capabilities. 


CSS Hover issue
```css
.nft {
    height: auto;
    width: auto;
    max-width: 21.875rem;
    max-height: 21.875rem;
    border-radius: 0.625rem;
}

.nft:after {
    position:absolute;
    width:100%; height:100%;
    top:0; left:0;
    background:hsl(178, 100%, 50%, .5);
    opacity:0;
    transition: all 0.5s;
    -webkit-transition: all 0.5s;
}
.nft:hover:after {
    opacity:1;
}

h3 {
    color: hsl(0, 0%, 100%);
    font-family: "Outfit";
    font-weight: 600;
}

h3:hover {
    color: hsl(178, 100%, 50%);
    font-family: "Outfit";
    font-weight: 600;
}
```

