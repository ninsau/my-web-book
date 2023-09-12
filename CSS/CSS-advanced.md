# Advanced CSS Topics

## Table of Contents

1. [CSS Animations](#css-animations)
2. [CSS Transitions](#css-transitions)
3. [Pseudo-classes](#pseudo-classes)
4. [CSS Variables](#css-variables)
5. [Responsive Design](#responsive-design)
6. [Further Reading](#further-reading)

---

## CSS Animations

CSS animations make it possible to animate transitions from one CSS style to another.

```css
@keyframes my-animation {
  from {
    background-color: red;
  }
  to {
    background-color: yellow;
  }
}

.animate {
  animation: my-animation 4s infinite;
}
```

---

## CSS Transitions

Transitions provide a way to control animation speed when changing CSS properties.

```css
.transition {
  transition: background-color 0.5s ease;
}

.transition:hover {
  background-color: green;
}
```

---

## Pseudo-classes

Pseudo-classes are used to define the special state of an element.

```css
/* Hover state */
a:hover {
  color: red;
}

/* First child of a parent */
p:first-child {
  font-weight: bold;
}
```

---

## CSS Variables

CSS variables, also known as custom properties, allow you to store reusable values.

```css
:root {
  --main-color: blue;
}

.element {
  background-color: var(--main-color);
}
```

---

## Responsive Design

Responsive design aims to make websites look good on all devices.

```css
/* Mobile-first approach */
@media only screen and (min-width: 600px) {
  .container {
    width: 80%;
  }
}
```

---

## Further Reading

Ready to dive deeper? Check out these free resources:

- [Mozilla Developer Network's Advanced CSS Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [W3Schools Advanced CSS Tutorial](https://www.w3schools.com/css/)
- [CSS-Tricks](https://css-tricks.com/)

---
