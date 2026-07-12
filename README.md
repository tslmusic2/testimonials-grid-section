# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size


### Links

- Solution URL: [Add solution URL here](https://github.com/tslmusic2/testimonials-grid-section)
- Live Site URL: [Add live site URL here](https://tslmusic2-tesimonial-grid-section.netlify.app/)

## My process

1. global styles
2. typography
3. layout
4. I went back and update all the different fonts.  did this because it was easier once the layout was better setup and I knew it would be a lotd of CSS
5. media queries for tablet then desktop
6. added the background quote marks

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Positioning
- Mobile-first workflow

### What I learned

I learned that my understanding of grid is pretty good however I need to learn the syntax for certain properties better.  I was writing grid-template-columns: 4 1fr;  which isnt vaild  rather than doing 1fr 1fr 1fr 1fr or repeat(4 1fr)
samefor rows I had put grid-template-rows: 2;   thinking it would do 2 rows auto width.
So my grid was kind of in place and kind of working most of the time until I fixed that then it worked very well.

I had some issues trying to properly layout the img and cite section.  I tried various things such as using flexbox but with using a div in the htmlit wasnt working so I went width grid and used fixed widths

### Continued development

I need to make sure im using the correct symantex for my grid attributes going forward.
More grid practice will help getting used to how margins affect it and which properties to use on which elements

### AI Collaboration

My grid layout was close but I was having some spacing issues inside of the grid.  AI helped me realize that I was inputting the correct data but that my syntax was wrong so it wasnt working properly.  This fixed most of my issues with the spacing inside the cards.
I always ask AI if theres any errors or issues it sees in my code and this one was pretty clean.  just some minor issues

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/tslmusic2)

