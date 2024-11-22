# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

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

## Overview
Here you can see how my Social profile page component challenge looks like after finishing

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page, and corresponding links

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/social-links-profile-project-Mf5CIQEWGB)
- Live Site URL: [Live site URL here](https://jmarsic-social-links-profile.netlify.app/)

## My process
First I edited HTML and add some corresponding classes. After I download font style and implement it inside HTML head. After creating style.css I add variables to `:root` for later use. When setup was finished I first reset CSS and after that added styles that match design and given style guide. Hope you like it! 👋

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables

### What I learned

```html
<link
  rel="icon"
  type="image/png"
  sizes="32x32"
  href="./assets/images/favicon-32x32.png"
  alt="my profile picture"
/>
```
This piece of code is nothing special, but I used `alt` attribute that specifies an alternate text for an image, if the image cannot be displayed and it is good use for more and more cases where user uses `screen reader`. 


```css
:root {
  --clr-primary-400: hsl(75, 94%, 57%);
  --clr-neutral-100: hsl(0, 0%, 100%);
  --clr-neutral-300: hsl(0, 0%, 20%);
  --clr-neutral-700: hsl(0, 0%, 12%);
  --clr-neutral-900: hsl(0, 0%, 8%);

  --fs-paragraph: 0.875rem;

  --fw-regular: 400;
  --fw-semibold: 600;
  --fw-bold: 700;
}
```
Here I represent piece of code `:root` pseudo class where I globally define CSS variables.


```css
@font-face {
  font-family: "Inter";
  src: url(./assets/fonts/static/Inter-Regular.ttf);
}
```
Here I represent using of `@font-face` rules to load fonts locally.


### Continued development

This was fun project for me and also usefull for sharing my social links. In future I would like to use this learned skills and try something new like animations after hover/enter some box on page.


### Useful resources

- [Kevin Powell](https://www.youtube.com/@KevinPowell/videos) - Kevin really loves and know so many details around CSS and watching him on youtube is really helpfull with his explanations and approach. Ty Kevin.


## Author

- Frontend Mentor - [@jmarsic](https://www.frontendmentor.io/profile/jmarsic)
