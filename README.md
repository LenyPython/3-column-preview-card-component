# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Flexbox flex-flow: row wrap;

```css
$colors:(
	orange:hsl(31,77%,52%),
	cyan:hsl(184,100%,22%),
	darkCyan:hsl(179,100%,13%)
);

@each $name, $color in $colors {
	div.#{$name} {
		background: #{$color};
		button {
			color:#{$color};
		}
		:hover {
				background:#{$color};
				color:$lightGray;
				cursor: pointer;
			}
	}
}
```

### Continued development

SASS functions

## Author

- Website - 404
- Frontend Mentor - [@LenyPython](https://www.frontendmentor.io/profile/LenyPython)


