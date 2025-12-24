# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

---

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

- **Desktop preview:**  
  ![](./desktop.png)

- **Mobile preview:**  
  ![](./mobile.png)

### Links

- **Repository URL:** [https://github.com/ParthaDey5/loopstudios-landing-page-main]

- **Live Site URL:** [https://loopstudios-landing-page-main-xi-sage.vercel.app]

---

## My process

### Built with

- Semantic **HTML5** markup
- **SCSS** (mixins, nesting, responsive breakpoints)
- **Tailwind CSS** (utility‑first styling, responsive prefixes, arbitrary values)
- **BEM methodology** for class naming
- Flexbox and CSS Grid for layout
- Mobile‑first workflow
- Vanilla JavaScript for mobile menu toggle

### What I learned

- How to combine SCSS mixins with Tailwind utilities for both **reuse** and **raw speed**.  
- Overlay effects can be achieved with Tailwind only (`relative` + `absolute inset-0` + `bg-black/50`).  
- BEM naming layered alongside Tailwind utilities keeps the project **semantic and maintainable**.  

Example SCSS mixin I used for padding:
```scss
@mixin pad($top: 0, $right: $top, $bottom: $top, $left: $right) {
  padding: $top $right $bottom $left;
}
```

### Continued development

- Explore more **fluid sizing** with `clamp()` and Tailwind arbitrary values.  
- Refine **SCSS mixin library** for consistency across projects.  
- Push further into **componentization** and reusable patterns.  

### Useful resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs) – invaluable for responsive utilities and arbitrary values.  
- [Sass Guidelines](https://sass-guidelin.es/) – helped structure SCSS partials and mixins.  
- [BEM Methodology](http://getbem.com/) – reinforced semantic class naming discipline.  

---

## Author

- Website – [Partha](https://portfolio-delta-ten-55.vercel.app)  
- Frontend Mentor – [@ParthaDey5](https://www.frontendmentor.io/profile/ParthaDey5)  
- GitHub – [@ParthaDey5](https://github.com/yourusername)  


---

## Acknowledgments

Thanks to **Frontend Mentor** for the challenge and community feedback.  
Special credit to documentation resources (Tailwind, Sass, BEM) that guided the build.  
```
