# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<h2 align="center">Desktop View</h2>

![](/images/screenshots/desktop.png)

<h2 align="center">Mobile View</h2>

<p align="center">
  <img src="/images/screenshots/mobile.png" alt="Mobile View" />
</p>

<h2 align="center">Active-States View</h2>

<p align="center">
  <img src="/images/screenshots/active1.png" alt="active1" />
  <img src="/images/screenshots/active2.png" alt="active2" />
  <img src="/images/screenshots/mobile.png" alt="active3" />
</p>

### Links

- Solution URL: [Github repository](https://github.com/euraye/nft-preview-card-component-euraye-solution)
- Live Site URL: [NFT Preview Card Component](https://nft-preview-card-component-euraye.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge, I learned how to use CSS Grid for layout, apply transitions for smooth effects, and use positioning to control element placement. I also practiced sizing images properly and adding hover animations to interactive elements.

Here are some code snippets that demonstrate what I learned:

```css
/* Using CSS Grid for layout */
.card-container {
  display: grid;
  gap: 1.5rem;
}
```
```css
/* Adding hover effect to show overlay and icon on the main image */
.main-image:hover .equilibrium{
  background-color: var(--cyan400);
  opacity: 0.5;
}
.main-image:hover .view{
  opacity: 1;
}
```

```css
/* Positioning elements and sizing images */
.card-image {
  width: 100%;
  height: auto;
  object-fit: cover;
  position: relative;
}
```

```css
/* Adding hover animations to interactive elements */
.button:hover {
  background-color: #00fff7;
  color: #fff;
  transition: background 0.2s, color 0.2s;
}
```

### Continued development

I want to continue practicing and deepening my understanding of Flexbox and CSS Grid, especially how to use them together for complex layouts. I also aim to improve my use of media queries for responsive design and gain a deeper knowledge of creating various hover effects. In addition, I plan to learn how to implement these techniques in different frameworks and experiment with utility-first frameworks like Tailwind CSS.

### Useful resources

- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [MDN Web Docs - CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [W3Schools - CSS Grid](https://www.w3schools.com/css/css_grid.asp)
- [W3Schools - CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)
- [W3Schools - CSS :hover Selector](https://www.w3schools.com/cssref/sel_hover.php)
- [GitHub Copilot](https://github.com/features/copilot)

## Author
- Frontend Mentor - [@euraye](https://www.frontendmentor.io/profile/euraye)
- Github - [@euraye](https://github.com/euraye)



