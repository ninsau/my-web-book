# HTML Basics Expanded

## Table of Contents

1. [HTML Comments](#html-comments)
2. [HTML Entities](#html-entities)
3. [HTML Links](#html-links)
4. [HTML Tables](#html-tables)
5. [HTML Forms](#html-forms)
6. [Further Reading](#further-reading)

---

## HTML Comments

Comments are not displayed in the browser but can be useful for leaving notes in your code.

```html
<!-- This is a comment -->
```

---

## HTML Entities

Entities are used to display reserved characters in HTML.

```html
<!-- Display less than and greater than signs -->
&lt; &gt;
```

---

## HTML Links

You can create different types of links in HTML.

```html
<!-- Basic link -->
<a href="https://www.google.com">Visit Google</a>

<!-- Open link in a new tab -->
<a href="https://www.google.com" target="_blank">Visit Google</a>

<!-- Link to an email address -->
<a href="mailto:example@email.com">Send Email</a>
```

---

## HTML Tables

Tables are used to display data in a tabular format.

```html
<table border="1">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```

---

## HTML Forms

Forms are used to collect user input.

```html
<form action="/submit" method="post">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password">
  
  <input type="submit" value="Submit">
</form>
```

---

## Further Reading

Ready to learn more? Check out these free resources:

- [Mozilla Developer Network's HTML Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [FreeCodeCamp's HTML Course](https://www.freecodecamp.org/)

---
