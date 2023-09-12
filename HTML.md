# HTML for Beginners

## Table of Contents

1. [What is HTML?](#what-is-html)
2. [Basic HTML Structure](#basic-html-structure)
3. [Common HTML Tags](#common-html-tags)
4. [Attributes](#attributes)
5. [Your First Web Page](#your-first-web-page)
6. [Further Reading](#further-reading)

---

## What is HTML?

HTML is like the skeleton of a website. It gives structure to the content on the web. Imagine you're building a house; HTML would be the bricks and beams.

---

## Basic HTML Structure

Every HTML file has a basic structure. Here it is:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Your Web Page Title</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

- `<!DOCTYPE html>`: Tells the browser this is an HTML5 document.
- `<html>`: The root element.
- `<head>`: Contains meta information and links.
- `<title>`: Sets the title of your web page.
- `<body>`: Holds the content of your web page.

---

## Common HTML Tags

Here are some commonly used HTML tags:

### Headings

Headings are used to define titles and subtitles. You have six levels of headings, from `<h1>` to `<h6>`.

```html
<h1>This is a big heading</h1>
```

### Paragraph

Paragraphs are defined using the `<p>` tag.

```html
<p>This is a paragraph.</p>
```

### Links

Links are defined using the `<a>` tag.

```html
<a href="https://www.google.com">Visit Google</a>
```

### Images

Images are placed using the `<img>` tag.

```html
<img src="image.jpg" alt="A cool image">
```

### Lists

You can create lists using `<ul>` (unordered) and `<ol>` (ordered).

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

---

## Attributes

HTML tags can have attributes. Attributes provide additional information about an element.

- `href`: Specifies the URL for a link.
- `src`: Specifies the source URL of an image.
- `alt`: Specifies alternative text for an image.

Example:

```html
<a href="https://www.google.com" target="_blank">Visit Google</a>
```

---

## Your First Web Page

Time to create your first web page! Open a text editor on your phone or computer and paste the following code:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>Welcome to my website.</p>
  </body>
</html>
```

Save it as `index.html` and open it with a web browser. Ta-da!

---

## Further Reading

Ready to learn more? Check out these free resources:

- [Mozilla Developer Network's HTML Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [FreeCodeCamp's HTML Course](https://www.freecodecamp.org/)

---
