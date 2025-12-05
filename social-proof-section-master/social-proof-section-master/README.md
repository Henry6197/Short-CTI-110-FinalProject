# CTI-110 Final Project - Social proof section solution

![Design preview for the Social proof section coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size
- See hover states for interactive elements

### Links

- Repository URL: [https://github.com/Henry6197/Short-CTI-110-FinalProject](https://github.com/Henry6197/Short-CTI-110-FinalProject)
- Live Site URL: [Add live site URL here after GitHub Pages deployment]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox
- CSS Grid
- Mobile-first workflow
- Google Fonts (League Spartan)

### What I learned

This project helped me practice:

1. **Responsive Design**: Creating layouts that work seamlessly across mobile (375px) and desktop (1440px) breakpoints
2. **CSS Grid**: Used for the header section to create a two-column layout on desktop
3. **Flexbox**: Applied for ratings cards, testimonials, and internal card layouts
4. **CSS Custom Properties**: Organized colors and typography as reusable variables
5. **Staggered Layouts**: Created visually interesting offset patterns for rating cards and testimonials
6. **Semantic HTML**: Used appropriate elements like `<main>`, `<section>`, `<article>`, and `<blockquote>`
7. **Accessibility**: Added proper alt text, ARIA attributes, and semantic markup

Key CSS techniques used:

```css
/* CSS Variables for maintainability */
:root {
  --very-dark-magenta: hsl(300, 43%, 22%);
  --soft-pink: hsl(333, 80%, 67%);
}

/* Staggered card layout */
.rating-2 {
  margin-left: 3rem;
}

/* Background patterns with pseudo-elements */
body::before {
  content: '';
  position: absolute;
  background-image: url('./images/bg-pattern-top-desktop.svg');
}
```

### Continued development

Future improvements could include:
- Adding subtle animations on scroll or hover
- Implementing a dark mode toggle
- Enhancing accessibility features with keyboard navigation
- Optimizing performance with lazy loading for images

## Author

- GitHub - [@Henry6197](https://github.com/Henry6197)
- Project - CTI-110 Final Project

## Acknowledgments

Thanks to Wake Tech Community College and the CTI-110 course for providing this practical web development challenge.
