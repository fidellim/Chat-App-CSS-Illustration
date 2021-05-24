# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

![Solution PC](./images/Solution%20PC.png)
![Solution Mobile](./images/Solution%20Mobile.png)

### Links

- Solution URL: [Solution](https://github.com/fidellim/Chat-App-CSS-Illustration)
- Live Site URL: [Live Site](https://eager-johnson-149938.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

To be able to apply SCSS for the first time. As well as learn some simple animation for the chat app.

```css
@media (min-width: 910px) {
	.cp-content-container {
		gap: 8rem;
		.content-container {
			.content-para {
				width: 28rem;
			}
		}
	}
}

@keyframes text-from-down {
	0% {
		transform: translate(0%, 150%);
	}
	100% {
		transform: translate(0%, 0%);
	}
}
```

### Continued development

To be learn other concepts of SASS as well as learn more animations in CSS.

### Useful resources

- [CSS Animations](https://www.w3schools.com/css/css3_animations.asp) - To be able to familiarize myself with some animations.
- [Custom Radio Button](https://www.w3schools.com/howto/howto_css_custom_checkbox.asp) - To be able to customize a radio button.
- [Different Angle for Linear Gradient](https://www.w3schools.com/css/css3_gradients.asp) - To be able to change the angle of linear gradient.
- [SASS Documentation](https://sass-lang.com/documentation) - Documentation of SASS
- [Animations](https://css-tricks.com/css-animation-libraries/) - Helped me get an idea of animations to use for the chat bubbles in chat ap illustration.

## Author

- Website - [Fidel Lim](https://fidellim-portfolio.netlify.app/)
- Frontend Mentor - [@fidellim](https://www.frontendmentor.io/profile/fidellim)
- Github - [@fidellim](https://github.com/fidellim)
