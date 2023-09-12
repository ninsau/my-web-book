# CSS for Beginners

## Table of Contents

1. [What is CSS?](#what-is-css)
2. [How to Include CSS](#how-to-include-css)
3. [Selectors, Properties, and Values](#selectors-properties-and-values)
4. [Colors](#colors)
5. [Text and Fonts](#text-and-fonts)
6. [The Box Model](#the-box-model)
7. [Flexbox and Grid](#flexbox-and-grid)
8. [Media Queries](#media-queries)
9. [Further Reading](#further-reading)

---

## What is CSS?

CSS stands for **Cascading Style Sheets**. If HTML is the skeleton of a website, think of CSS as the skin and clothes. It makes your website look pretty! 🌈

---

## How to Include CSS

There are three main ways to include CSS in your HTML files:

### Inline CSS

You can include CSS directly in your HTML tags using the `style` attribute.

```html
<p style="color: red;">This is a red paragraph.</p>
```

### Internal CSS

You can include CSS in the `<head>` section of your HTML file using the `<style>` tag.

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
```

### External CSS

You can link to an external `.css` file using the `<link>` tag.

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

---

## Selectors, Properties, and Values

In CSS, we use selectors to target HTML elements and apply styles to them.

```css
/* This is a comment */
p {
  color: red;  /* This is a property and value */
}
```

- **Selector**: `p`
- **Property**: `color`
- **Value**: `red`

---

## Colors

Colors can be defined in various ways:

- Named colors: `red`, `blue`, `green`
- Hex codes: `#FF0000`, `#0000FF`
- RGB: `rgb(255, 0, 0)`

```css
p {
  color: #FF0000;
}
```

---

## Text and Fonts

You can style text using properties like `font-family`, `font-size`, and `text-align`.

```css
p {
  font-family: 'Arial';
  font-size: 16px;
  text-align: center;
}
```

---

## The Box Model

Every HTML element is a box. The box model includes:

- Content
- Padding
- Border
- Margin

```css
div {
  padding: 10px;
  border: 2px solid black;
  margin: 20px;
}
```

---

## Flexbox and Grid

Flexbox and Grid are modern layout models in CSS.

### Flexbox

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Grid

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

---

## Media Queries

Media queries allow you to apply styles based on device characteristics.

```css
@media (max-width: 600px) {
  p {
    font-size: 14px;
  }
}
```

---

## Further Reading

Ready to dive deeper? Check out these free resources:

- [Mozilla Developer Network's CSS Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/)
- [FreeCodeCamp's CSS Course](https://www.freecodecamp.org/)

---
