# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://jwben1.github.io/fm-product-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned:

- The use of Picture element and how I can include many srcset for responsive images.
- The hgroup element for grouping headings.
- The use of screen reader only(.visually-hidden), to improve accessibility.
- How to use BEM-style classes.
- How to inspect the reset css and see how it affects my design(I used Josh Comeau's css reset).
- To use the Custom properties.

```html
<picture class="product__image">
  <source media="(min-width: )" srcset= />
</picture>
```

```css
:root {
  --clr-dark: ;
}
```

### Continued development

I want to improve my skills on custom properties and the simplification of CSS.
I also need to stop going overboard with things

### Useful resources

- (https://fedmentor.dev/posts/html-plan-product-preview/) - This helped me for writing simple HTML. I really liked this pattern and will use it going forward.
- (https://www.youtube.com/watch?v=PHO6TBq_auI) - This is an amazing video by Kevin Powell which helped me to understand the use of custom properties.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/jwben1)

## Acknowledgments

- The Frontend Mentor Community
- Kevin Powell Solution
