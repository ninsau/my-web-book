# Bootstrap CSS for Beginners - Part 2

## Table of Contents

1. [Navigation Bars](#navigation-bars)
2. [Cards](#cards)
3. [Forms](#forms)
4. [Tables](#tables)
5. [Further Reading](#further-reading)

---

## Navigation Bars

Navigation bars are a key part of any website. Bootstrap makes it super easy to create one.

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">My Website</a>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarNav"
  >
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact</a>
      </li>
    </ul>
  </div>
</nav>
```

---

## Cards

Cards are flexible content containers. They can hold text, images, and more.

```html
<div class="card" style="width: 18rem;">
  <img src="image.jpg" class="card-img-top" alt="..." />
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">Some quick example text.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

---

## Forms

Bootstrap provides styled form elements that you can use right away.

```html
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" />
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" />
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

---

## Tables

Bootstrap offers classes to style tables.

```html
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Name</th>
      <th scope="col">Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>John</td>
      <td>30</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jane</td>
      <td>25</td>
    </tr>
  </tbody>
</table>
```

---

## Further Reading

Ready to learn more? Check out these free resources:

- [Official Bootstrap Documentation](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
- [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- [FreeCodeCamp's Bootstrap Course](https://www.freecodecamp.org/news/tag/bootstrap/)

---
