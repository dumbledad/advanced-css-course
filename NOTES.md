# Links

- Finished: [file:///Users/timregan/src/acss/Natours/after-S05/index.html#section-tours](file:///Users/timregan/src/acss/Natours/after-S05/index.html#section-tours)
- WiP: [file:///Users/timregan/src/acss/Natours/starter/index.html](file:///Users/timregan/src/acss/Natours/starter/index.html)

# Tim's Notes for Jonas's Udemy  Advanced CSS course

- fonts in body not universal 
- reset margin and padding in universal `* { }`
- first background image is on top
- Clip path, percentages are useful
- Clippy, the CSS path maker https://bennettfeely.com/clippy/ 
- Position absolute is measured from the first parent container which is position relative
- Don't forget span for styling different bits of text in a (semantic) block
- block elements take entire width and have newline before and after
- keyframes are best animating just two properties, and browsers are optimised for them to be opacity and translation
- animation-fil-mode will automatically apply the styling that starts the animation (avoid present, disappear, slowly appear)
- pseudo
  - classes are like `btn:hover`
  - elements are like `btn::after`
- Three Pillars of Writing Good HTML & CSS
    1. Responsive Design
        - He assumes we know
            - [fluid layouts](https://support.google.com/webdesigner/answer/7002913?hl=en-GB#percentage-based)
            - [media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
        - Responsive images
        Correct units
        - Desktop 1st vs. mobile-first
    1. Maintainable & Scalable Code
        - File organisation
        - Naming classes
        - Structure HTML
    1. Web Performance
        - Faster & smaller
        - Fewer smaller images
        - Compress
- 10px font size in the root (i.e. the `html` element) makes `rem` calculations easy
    - Or even better, 62.5% which gets us from 16px to 10px
- BEM: Block Element Modifier
  - A _block_ is reusable within a site or page, it is modular
  - An _element_ makes no sense outside of its block
  - BEM leads to declarations with _'low specificity score'_ and so they are unlikely to mess with anything else. This is part of the popularity of BEM syntax

## Up to ...

https://www.udemy.com/course/advanced-css-and-sass/learn/lecture/8312900#overview