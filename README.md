# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](assets\images\screenshot.png)

### Links

- [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/frontend-mentor---faq-accordion-solution-nlwZfB7mda)
- [live site URL](https://alaa-mekibes.github.io/faq-accordion-frontend-mentor)

## My process

### What I learn

- Using **logical properties** (`block-start`, `block-end`, `inline-left`, `inline-right`) to replace physical properties (`top`, `bottom`, `left`, `right`), e.g:
```css
.ele {
    margin-block-end: 1rem; /* margin-bottom: 1rem */
    padding-inline-start: 2rem; /* padding-left: 2rem */
    border-block-start: 1px; /* border-top: 1px */
}
```  
**But what is the goal?** Internationalization: They support languages that are right-to-left (RTL) like Arabic, or vertical writing systems like Japanese. So it's more flexible.

- Using **`prefers-reduced-motion: reduce`** for users who prefered reduced motion. e.g:
```css
@media (prefers-reduced-motion: reduce) {
  * {
    transition: none !important;
    animation: none !important;
  }
}
``` 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
