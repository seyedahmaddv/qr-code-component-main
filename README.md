# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/seyedahmaddv/qr-code-component-main)
- Live Site URL: [Live Demo](https://qr-code-component-main-steel-seven.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive design principles

### What I learned

During this project, I learned how to create a well-structured, responsive component using only HTML and CSS. One of the key learnings was how to properly center elements both horizontally and vertically using Flexbox:

```html
<main>
  <div class="qr-card">
    <img src="./images/image-qr-code.png" alt="QR code to Frontend Mentor website" class="qr-code">
    <h1>Improve your front-end skills by building projects</h1>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</main>
```

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

I also improved my understanding of designing for different screen sizes and implementing subtle but effective shadow effects:

```css
.qr-card {
  box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.05);
}
```

### Continued development

In future projects, I'd like to focus more on:

- Implementing accessibility features
- Using CSS variables more effectively
- Adding subtle animations to enhance user experience
- Practicing more with CSS Grid for complex layouts

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand the Flexbox model which was essential for centering the card.
- [Box Shadow CSS Generator](https://cssgenerator.org/box-shadow-css-generator.html) - A useful tool for generating and visualizing box shadows.

## Author

- Website - [Seyed Ahmad](https://github.com/seyedahmaddv)
- Frontend Mentor - [@Seyed Ahmad](https://www.frontendmentor.io/profile/seyedahmaddv)
- Twitter - [@Seyed Ahmad](https://www.linkedin.com/in/seyedahmaddv)

## Acknowledgments

I'd like to thank Frontend Mentor for providing this challenge that helped me practice my HTML and CSS skills. Also, thanks to the online community for sharing helpful resources about responsive design techniques.