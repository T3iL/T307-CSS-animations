# T307-CSS-animations

1. events :hover
2. CSS transitions
3. CSS animations



###
- @keyframes
- animation-name
- animation-duration
- animation-delay
- animation-iteration-count
- animation-direction
- animation-timing-function
- animation-fill-mode
- animation

```css
/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}

----

{animation: example 5s linear 2s infinite alternate;}
```

https://3dtransforms.desandro.com/card-flip
