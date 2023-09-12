# Bootstrap CSS for Beginners - Part 1

## Table of Contents

1. [What is Bootstrap?](#what-is-bootstrap)
2. [Getting Started](#getting-started)
3. [Containers](#containers)
4. [Typography](#typography)
5. [Buttons](#buttons)
6. [Further Reading](#further-reading)

---

## What is Bootstrap?

Bootstrap is a free and open-source CSS framework that helps you design websites quickly and easily. It comes with a bunch of pre-made components that you can use right away! 🌟

---

## Getting Started

To start using Bootstrap, you need to include its CSS and JavaScript files in your HTML. You can either download them or link to them directly from a CDN (Content Delivery Network).

### Using CDN

Add these lines in the `<head>` section of your HTML file:

```html
<!-- Bootstrap CSS -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css"
  rel="stylesheet"
/>

<!-- Bootstrap JavaScript (Optional) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js"></script>
```

---

## Containers

In Bootstrap, a container is used to wrap site contents. There are two types of containers:

- `.container`: Fixed-width container
- `.container-fluid`: Full-width container

```html
<!-- Fixed-width container -->
<div class="container">
  <!-- Your content here -->
</div>

<!-- Full-width container -->
<div class="container-fluid">
  <!-- Your content here -->
</div>
```

---

## Typography

Bootstrap provides classes for styling text.

- `.h1` to `.h6`: Classes for headings
- `.lead`: Makes a paragraph stand out
- `.text-muted`: Mutes the text color

```html
<h1 class="h1">This is a large heading</h1>
<p class="lead">This paragraph will stand out.</p>
<p class="text-muted">This text is muted.</p>
```

---

## Buttons

Bootstrap comes with pre-styled button classes.

- `.btn`: Basic button class
- `.btn-primary`, `.btn-secondary`: Button themes

```html
<!-- Basic button -->
<button class="btn">Click Me!</button>

<!-- Themed buttons -->
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
```

---

## Further Reading

Ready to learn more? Check out these free resources:

- [Official Bootstrap Documentation](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
- [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- [FreeCodeCamp's Bootstrap Course](https://www.freecodecamp.org/news/tag/bootstrap/)

---
