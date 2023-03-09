# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Testimonial-Grid-Section](https://https://github.com/Denaro13/Testimomials-Grid-Section)
- Live Site URL: [Testimonial-grid-display](https://https://testimonial-grid-display.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt how to use grid areas to provide a custom layout of item:

```css
.section-center {
  max-height: 90vh;
  grid-template-columns: repeat(4, 1fr);
  grid-template-areas: "a a b c" "d e e c";
  gap: 1.5rem;
}
.card-1 {
  grid-area: a;
}
.card-2 {
  grid-area: b;
}
.card-3 {
  grid-area: d;
}
.card-4 {
  grid-area: e;
}
.card-5 {
  grid-area: c;
}
```

### Continued development

I intend to improve my skill set in understanding a deeper concept of CSS and also learn how to use other frame works to improve productivity.

## Author

- Frontend Mentor - [@Denaro13](https://www.frontendmentor.io/profile/Denaro13)
- Twitter - [@thecapguy\_](https://www.twitter.com/thecapguy_)
