# Bootstrap CSS for Beginners - Part 3

## Table of Contents

1. [Modals](#modals)
2. [Carousels](#carousels)
3. [Utilities](#utilities)
4. [Further Reading](#further-reading)

---

## Modals

Modals are dialog boxes or pop-up windows that are used to provide additional information or options.

```html
<!-- Button trigger modal -->
<button
  type="button"
  class="btn btn-primary"
  data-toggle="modal"
  data-target="#myModal"
>
  Open Modal
</button>

<!-- Modal -->
<div class="modal fade" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Modal title</h5>
        <button type="button" class="close" data-dismiss="modal">
          <span>&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <p>Modal body text goes here.</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

---

## Carousels

Carousels are slideshows for cycling through a series of content.

```html
<div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
  </ol>

  <!-- Slides -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="image1.jpg" alt="Image 1" />
      <div class="carousel-caption">
        <h3>Image 1</h3>
      </div>
    </div>
    <div class="carousel-item">
      <img src="image2.jpg" alt="Image 2" />
      <div class="carousel-caption">
        <h3>Image 2</h3>
      </div>
    </div>
  </div>

  <!-- Controls -->
  <a
    class="carousel-control-prev"
    href="#myCarousel"
    role="button"
    data-slide="prev"
  >
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a
    class="carousel-control-next"
    href="#myCarousel"
    role="button"
    data-slide="next"
  >
    <span class="carousel-control-next-icon"></span>
  </a>
</div>
```

---

## Utilities

Bootstrap provides various utility classes for spacing, coloring, and more.

- Spacing: `.m-*`, `.p-*`
- Text color: `.text-primary`, `.text-secondary`
- Background color: `.bg-primary`, `.bg-secondary`

```html
<div class="m-3 p-2 text-primary bg-secondary">This is a utility example.</div>
```

---

## Further Reading

Ready to learn more? Check out these free resources:

- [Official Bootstrap Documentation](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
- [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- [FreeCodeCamp's Bootstrap Course](https://www.freecodecamp.org/news/tag/bootstrap/)

---
