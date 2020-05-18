# Lesson 09

## Metatags:

https://getbootstrap.com/

metadata - is the data (information) about the data.
`<meta>` tags always go inside the `<head></head>` element.

- **Viewport** - The viewport is the user's visible area of the web page. It varies with the device. and will be smaller on a mobile-phone, than on a regular computer.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

# Bootstrap:

Bootstrap is a free and open-source CSS framework, that makes websites to be responsive.

- **Responsive web design** - is about using HTML and CSS to automatically resize, hide, shrink, or enlarge a website, to make it look good on all devices (desktop, tablet, phone..)

### use bootsrapt in out app:

```html
<!--CSS only-->
<link
  rel="stylesheet"
  href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
  integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
  crossorigin="anonymous"
/>
```

### Full guide:

##### 1. container

Containers are used to pad the content inside of them. and there are 2 container classes available:

1. The `container` class provides a responsive fixed width container.
2. The `container-fluid` class provides a full width container, spanning the entire width of the viewport.

examples:

```html
<div class="container"></div>
<div class="container-fluid"></div>
<div class="container pt-3"></div>
<!--pt = padding top 3 spaces -->
```

---

# Bootstrap grid

The grid system is responsive, and the columns will re-arrange automatically depending on the screen size.
<img src="https://www.c-sharpcorner.com/article/bootstrap-grid-system/Images/1.png"/>

### Grid classes:

1. `.col` extra small devices.
2. `.col-sm` - small devices.
3. `col-md` - medium devices.
4. `col-lg` - large devices.
5. `col-xl` - extra large devices.

- Bootstrap changes automatically the width to each div.

```html
<div class="row">
  <div class="col"></div>
  <div class="col"></div>
  <div class="col"></div>
  <div class="col"></div>
</div>
```

- Bootstrap changes automatically the width to each div.

```html
<div class="row">
  <div class="col-8"></div>
  <div class="col-4"></div>
</div>


<div class="row">
  <div class="col-8"></div>
  <div class="col-4"></div>
</div>
```
---

# Text
1. `display-1` class changes the font-size, and the font-weight. 
