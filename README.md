# Frontend Mentor - Ricky's Blog Preview Card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

First and foremost, all Glory to my Lord and Savior, Jesus Christ, for another day and opportunity to code. 

I'm supre proud of this project. Didn't use any resources other than searching how to hide the scrollbar with 'Overflow: hidden;. Other than that, This project defintely was a lot easier to complete and along the same lines as the QR Code project. 

### The challenge

Users should be able to:

- achieve a similar look as the example

### Screenshot

<img src="./My Desktop Design.png" />
<img src="./My Mobile Design.png" />
### Links

- Live Site URL: https://riickyriick.github.io/Blog-Card/

## My process

My process was a lot more organized this time around. 

Even before I began to code out my design, I plannend out the way I was going execute the strucutre of my code for better readability. 

Started with placing .card-container in the center of the Viewport.

Next I needed to fix the sizing of the images
in order to better see the sizing of the card.

The sizing and positioning of this profile image 
with the h4 was the only one I could find, since I 
groupd them together into a flex container and 
proceeded to adjust the image so the words, "Greg
Hooper" was aligning next to the image at a horizonatally 
center position, if that makes sense.

I then proceeded to design the card. 

After the card design and before proceeding with the rest of the design, I made sure to add the font-weights and it was easier to group them instead of writing a font-weight for each of the tags.

I added a span with a class .Learning in order to 
target the h2 with a yellow background 

p:first-of-type - with this selector I was able to select the first p tag in order to change it's color, while not changing the other p tag color.

I then changed the color of the bottom p tag.

 I used the .greg-container in order to adjust
the image with the p tag. It was easier to execute, but at 
first I was trying to see if I could float it to the 
right. However, I felt that flex-box was better, 
especailyl considering overall responsiveness.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

This project was a lot more enjoyable due to the fact that I confidently completed it all by myself, giving me a real sense of accomplishment. However, there were still some struggles regarding: 

- Font sizing without @media query. I had a diffcult time trying to fix the font-sizing. At 375px for mobile responsivness, my sizing kept pushing my .text paragraph down even before I got to a width of 375px. The only way that I knew for now was thorught media query. I'm sure there is a way using vw or rem within the body but I'm still not sure how they work. 



### Continued development

Again, Responsive design with a clear and concise strcutre that can be reusable. 

Also, approaching how the sizing works, specifically, how the units work with one another. 

## Author

<a href="https://www.rarroyoharo.com">rarroyoharo.com</a>
- Frontend Mentor - [@RiickyRiick](https://www.frontendmentor.io/profile/RiickyRiick)

