# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/dist/images/screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM Methology
- Mobile-first workflow
- SCSS

### What I learned

In this project I used media queerie and flex. Also using HTML 5 rule to use mark up. 

To see how you can add code snippets, see below:

```html
<footer class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">John Lois Floro</a>.
</footer>
```
```css
@media screen and (min-width: 375px) {
    .container {
        display: flex;
        flex-direction: row;
        margin: 15vh 30vh 5vh;

        .card {
            &__body {
                margin-block: 1.5rem 5rem;
            }
        }
    }
}
```

### Continued development

In future projects I really want to use flexbox and grid to responsive designs instead of media queerie. I also want to the modules of SCSS because currently Im just using @import. 


### Useful resources

- [Landmark elements](https://dequeuniversity.com/rules/axe/4.3/region?application=axeAPI) - This helped me for realizing that HTML landmarks are really important.

## Author

- Github - [loifloro](https://github.com/loifloro/)
- Frontend Mentor - [@loifloro](https://www.frontendmentor.io/profile/loifloro)
- Twitter - [@loisfloro](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Thanks to Frontend Mentor community for always giving feedback to newbie users like me. 

