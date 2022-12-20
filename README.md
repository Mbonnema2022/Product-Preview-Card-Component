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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![My Solution](https://hosting.photobucket.com/images/w208/mbonnema37/Perfume_card.png)

n you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/product-preview-card-component-0LVy25u7KR)
- Live Site URL: [My GitHub Pages](https://github.com/Mbonnema2022/Product-Preview-Card-Component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

<h1>Some HTML code I'm proud of</h1>

<article>
  <h2>Perfume</h2>

  <h1>Gabrielle Essence Eau De Parfum</h1>

 <p>A floral, solar and voluptuous interpretation composed by Olivier Polge, 
  Perfumer-Creator for the House of CHANEL.</p> 

<uL>
  <li class="price"> $149.99</li>
  <li><s>$169.99</s></li>
</uL>
 
<button class="btn"><img src="./images/icon-cart.svg" alt="" />Add to Cart</button>


```css
.proud-of-this-css .container .btn{
        background-color: hsl(158,36%,37%);
        color: #fff;
        font-weight: 700;
        font-size: 1rem;
        padding: 1rem 2rem;
        width: 100%;
        border: none;
        border-radius: 0.625rem;
        outline: none;
        cursor: pointer;
        transition: 0.3s;

        display: flex;
        align-items: center;
        justify-content: center;
    }

    .container .btn:hover{
        background-color: hsl(158, 38%, 20%);
    }

    .container .btn  img{
        margin-right: 0.5rem;
    }



### Continued development

I want to take some of the feed back and add to this to improve

#Examples:

Hey there! 👋 Here are some suggestions to help improve your code:

Congrats on completing your first challenge!🎊🎆

Regarding your question,

flex is best for singles column/row. While grid is best for multiple columns/rows. For this challenge, either in would work.

To not only improve your HTML code but to also identify the main content of you page, you will want to wrap your entire component inside the main element.
More Info:📚

MDN Main Element

The image’s alt tag description needs to be improved upon to better describe what it is. You will want to assume that you are describing the image to a someone.
More Info:📚

https://www.w3.org/WAI/tutorials/images/

The only heading in this component, is the name of the perfume; “Gabrielle Essence Eau De Parfum” . The rest of the text should be wrapped in a paragraph element.
Currently, the old price (169.99) 🏷 is not being properly announced to screen readers. To fix this, you are going to wrap the the price in a del element and inside it you will add a span element with an sr-only class that will state something like “The previous price was…” and use CSS to make it only visible to screen readers.

More Info:📚

Del Element

Your CSS Reset is extremely bare and being underutilized. To fully maximize your CSS reset, you want to add more to it.
Here are few CSS Resets that you can look at and use to create your own or just copy and paste one that is already prebuilt.

https://www.joshwcomeau.com/css/custom-css-reset/

https://meyerweb.com/eric/tools/css/reset/

http://html5doctor.com/html-5-reset-stylesheet/

If you have any questions or need further clarification, feel free to reach out to me.

Happy Coding!🎄🎁

### Useful resources

- [](https://uxplanet.org/challenge-006-product-preview-card-component-2de1d66fb4f6) - This is an amazing article which helped me forhow to do this ---> Step 2.3 ➡ Use root: to declare the colours we are using
:root {
   --white: #ffffff;
   --darkgrey: #747682;
   --mediumlightgrey: #707176;
   --darkgreen: #3D8168;
   --black: #000000;
   --bluishblack: #242A31;
   --cream: #F2E9E2;
} . I really liked this pattern and will use it going forward.
- [TsbSankara](https://www.youtube.com/watch?v=BMOH4zSLTnQ) - This helped me finally understand grid. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Marisia bonnema](https://mbonnema2022.github.io/portfolio/)
- Frontend Mentor - [@Mbonnema](https://www.frontendmentor.io/profile/Mbonnema2022)
- Twitter - [@BonnemaMarissa](https://twitter.com/BonnemaMarissa)
-GitHub - [@Mbonnema2022](https://github.com/Mbonnema2022)



## Acknowledgments

I would like to acknowledge YWeb Career Academy Front End Developer Boot camp(https://www.ywcamadison.org/what-were-doing/employment-transit/yweb-career-academy/)for all they taught me in 15 weeks .I neve rthought i could get paid to learn and i am glad i did this program ,Also thank you to my instructor: Ola
[ola-show](https://github.com/ola-show) and the soft skills instructors and case managers Saul cortes(scortes@ywcamadison.org) and aurealia johnson(auralia ajohnson@ywcamadison.org ).If you want to learn coding and front end development contavt your local Ywca and see if they offer a YWeb Career Academy.It s worth it .
