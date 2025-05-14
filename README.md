# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop View](./design/desktop-preview.jpg)
![Mobile View](./design/mobile-design.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-responsive design
- Google Fonts

### What I learned

This project helped me improve my skills in creating responsive components that adapt to different screen sizes. I learned how to:

- Structure HTML semantically for better accessibility
- Use Flexbox for layout positioning
- Implement hover states for interactive elements
- Create responsive designs with media queries
- Work with SVG background patterns

Some code snippets I'm proud of:

```html
<div class="plan-container">
  <div class="plan-info">
    <img src="./images/icon-music.svg" alt="Music icon" class="music-icon">
    <div class="plan-details">
      <h2>Annual Plan</h2>
      <p>$59.99/year</p>
    </div>
  </div>
  <a href="#" class="change-link">Change</a>
</div>
```

```css
.plan-container {
  background-color: hsl(225, 100%, 98%); /* Very pale blue */
  border-radius: 12px;
  padding: 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 32px;
}

.btn-primary:hover {
  opacity: 0.8;
}
```

### Continued development

In future projects, I want to focus on:

- Improving my CSS animations and transitions
- Implementing more advanced responsive design techniques
- Exploring CSS Grid for more complex layouts
- Enhancing accessibility features

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive reference for HTML, CSS, and JavaScript.
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Excellent visual guide to Flexbox.
- [Google Fonts](https://fonts.google.com/) - For typography options.

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
