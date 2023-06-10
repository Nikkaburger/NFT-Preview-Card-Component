# NFT-Preview-Card-Component
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This is a solution to the [Product preview card component challenge on Frontend Mentor]

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![images/screenshot.png]

### Links

- Solution URL: (https://github.com/Nikkaburger/product-preview-card-component)
- Live Site URL: (https://nikkaburger-product-preview-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned


```html
<body>
    <div class="container">
    <img src="images/image-equilibrium.jpg" alt="image image-equilibrium" class="imagebox">
    <h1>
        Equilibrium #3429
    </h1>
    <p>
        Our Equilibrium collection promotes balance and calm.
    </p>
    <div class="pricing">
    <img src="images/icon-ethereum.svg" alt="icon-ethereum"><div class="price">0.041 ETH</div>
    <div class="time"><img src="images/icon-clock.svg" alt="icon-clock"> <div class="timer"> 3 days left</div></div>
    </div>
    <hr>
    <div class="description"><img src="images/image-avatar.png" alt="image-avatar" class="circle"> <p class="author">Creation of </p><p class="name"> Jules Wyvern</p>
    </div>
    </div>
</body>

```
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap');
@media (min-width: 375px) and (max-height:667px){
    body{
        background-color: hsl(217, 54%, 11%);
        font-size: 18px;
        color: hsl(215, 51%, 70%);
        justify-content: center;
        align-items: center;
        overflow: hidden;
        font-family: 'Outfit', sans-serif;
    }

    .container {
        background-color: hsl(216, 50%, 16%);
        border-radius: 15px;
        margin: 80px 10px;
        width: 295px;
        height: 100%;
        padding: 20px;
        flex-direction: column;
    }

    .imagebox {
        width: 100%;
        border-radius: 15px;
        max-height: 250px;
        border: none;
    }

    h1 {
        color: hsl(0, 0%, 100%);
        font-size: 22px;
    }

    p {
        font-size: 18px;
        color: hsl(215, 51%, 70%);
        font-weight: 300;
    }

    .pricing {
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    .price {
        display: flex;
        flex-direction: row;
        font-size: 16px;
        font-weight: 600;
        padding-left: 10px;
        color: hsl(178, 100%, 50%);
    }

    .time {
        display: flex;
        margin-left: 100px;
        flex-direction: row;
        align-items: center;
        font-weight: 300;
        font-size: 16px;
    }

    .timer {
        padding-left: 10px;
    }

    hr {
        margin-top: 20px;
        height: 1px;
        background-color: hsl(215, 32%, 27%);
        width: 100%;
        transform: scaleY(0.1);
      }
      

    .description {
        display: flex;
        flex-direction: row;
        font-weight: 300;
        align-items: center;
    }

    .circle {
        height: 30px;
        width: 30px;
        border-radius: 50%;
        border-style: solid;
        border-color: hsl(0, 0%, 100%);
        border-width: 1px;
        float: left;
        margin-right: 10px;
    }

    .name {
        color: hsl(0, 0%, 100%);
        margin-left: 5px;
        float: right;
    }

    .name:hover {
        cursor: pointer;
        color: hsl(178, 100%, 50%);
    }

    .imagebox:hover {
        cursor: pointer;
        background-color: hsl(178, 100%, 50%);
    }

    h1:hover {
        cursor: pointer;
        color: hsl(178, 100%, 50%);
    }
}

@media (max-width: 1440px) and (max-height: 657px) {
    .container {
        justify-content: center;
        align-items: center;
        margin: 6% 35%;
    }
}

```

### Continued development

My focus is on mastering modern web design techniques through continuous learning, experimentation, and a willingness to adapt to the ever-changing web landscape. 
By focusing on responsive design using, HTML5, CSS3, JavaScript, and PHP, to be adequately equipped to create visually stunning and user-friendly websites. Embrace new technologies, stay curious, and push the boundaries of my creativity to unlock endless possibilities in the world of web development. 


### Useful resources

- [#CSSMediaQuery](https://courses.webdevsimplified.com) - This helped me to understand and fix media query for the mobile version of my design, the tutorial was direct and explanatory. I really liked this pattern and will use it going forward.
- [#HTMLFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand the functionality of #HTML5 tags. I'd recommend it to anyone still learning this concept.
-[#CSSTutorialFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand CSS tags, syntax and their functionalities. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Oluwaseun Akeju](https://www.fluxverge.com)
- Frontend Mentor - [@nikkaburger](https://www.frontendmentor.io/profile/nikkaburger)
- Twitter - [@fluxverge](https://www.twitter.com/fluxverge)

## Acknowledgments

Special thanks to Almighty God for the completion of this task, my profound gratitude to Dave Gray, Omolade Sunday, Akinola Akeem and Webdevsimplified for their immense contributions.
