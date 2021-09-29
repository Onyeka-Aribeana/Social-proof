# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

This was a bit of a challenge because I was torn on whether I should use grid or flex-box. I eventually settled on grid for the cards and the overview and made them responsive (no need for media queries 🎉). Like so:

.testimonials {
margin-top: 40px;
display: grid;
grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); this helped the cards and the overview fit in any viewport
align-items: center;
justify-items: center;
grid-gap: .5rem;
grid-auto-flow: dense;
}

### Continued development

This project was a helpful remainder of the things I had forgotten. Like how to use grid layout for responsiveness. And also need to improve on my media queries and do more projects to improve my skills

### Useful resources

- (https://www.css-tricks.com/look-ma-no-media-queries-responsive-layouts-using-css-grid/) - This helped me with grid responsiveness. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Onyeka-Aribeana](https://www.frontendmentor.io/profile/Onyeka-Aribeana)
- Github - [Onyeka-Aribeana](https://www.github.com/Onyeka-Aribeana)
