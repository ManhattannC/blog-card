# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements (The title changes color to Yellow).
- Experience a responsive layout optimized for all screen sizes.

### Screenshot

![Solution Design](./design/design-design.jpg)

### Links

- Solution URL: [https://github.com/ManhattannC/blog-card]
- Live Site URL: [https://manhattannc.github.io/blog-card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- Mobile-first workflow
- Local Fonts using `@font-face`

### What I learned

During this project, I improved my understanding of CSS resets to eliminate default browser margins. I also learned how to properly implement local fonts using the `@font-face` rule to ensure specific font weights (800) are rendered correctly.

One of the highlights was creating the "Hard Shadow" effect without any blur:

```css
.card {
  box-shadow: 8px 8px 0px 0px var(--black);
}
```

### AI Collaboration

This project was built with the assistance of Gemini.

- Debugging: Resolved issues where local fonts weren't loading due to incorrect path and domain naming.
- Refactoring: Optimized Flexbox structure to ensure the attribution footer remained at the bottom.
- Concepts: Gained a deeper understanding of the CSS Box Model and margin: 0 logic.

## Author

- Website - [Manhattann](https://manhattannc.github.io/blog-card/)
- Frontend Mentor - [@Manhattann](https://www.frontendmentor.io/profile/Manhattann)
