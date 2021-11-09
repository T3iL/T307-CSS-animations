# T307-CSS-animations

1. events :hover
2. CSS transitions
3. CSS animations

### transition
- transition
- transition-delay
- transition-duration
- transition-property
- transition-timing-function

```css
div{transition: <width/color/background/all> 2s;}
```

### animation
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
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

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
