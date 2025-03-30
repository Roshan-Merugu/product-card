# Frontend Mentor - Product Preview Card Component Solution

This is my solution to the [Product Preview Card Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). This challenge helped me improve my skills in responsive design and CSS layout techniques.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (mobile and desktop).
- See hover and focus states for interactive elements like buttons.

### Screenshots

#### Desktop Version

![Desktop Version](./screenshots/desktop-version.png)

#### Mobile Version

![Mobile Version](./screenshots/mobile-version.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Roshan-Merugu/product-preview-card)
- Live Site URL: [Live Demo](https://your-live-site-url.com)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I Learned

This project helped me solidify my understanding of responsive design using media queries and Flexbox. Below is an example of how I used media queries to adjust the layout for mobile devices:

```css
@media (max-width: 576px) {
    .perfume-container {
        flex-direction: column;
        width: 300px;
        align-items: center;
    }

    .perfume-image {
        width: 100%;
        height: auto;
    }

    .info-card {
        text-align: center;
    }
}
```

### Continued Development

I plan to continue improving my skills in responsive design and CSS layout techniques. I also aim to explore CSS Grid for more complex layouts in future projects.

### Useful Resources

- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This resource helped me understand Flexbox better and apply it effectively in this project.
- [MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries) - This article provided a clear explanation of media queries and their usage.

## Author

- Website - [Roshan Merugu](https://www.your-site.com)
- Frontend Mentor - [@Roshan-Merugu](https://www.frontendmentor.io/profile/Roshan-Merugu)
- Twitter - [@RoshanMerugu](https://www.twitter.com/RoshanMerugu)
