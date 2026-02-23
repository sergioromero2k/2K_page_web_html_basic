# page_web_html_basic

My first website built with HTML and CSS — made in 2021 as part of a web development course. Kept as a personal milestone.

---

## About

**RyMcQueen** is a basic static website built from scratch with pure HTML and CSS. It was my first real project learning frontend web development, covering semantic structure, navigation, multiple pages, and custom styles.

No frameworks, no libraries — just HTML and CSS as they should be learned.

---

## Structure

| File / Folder | Description |
|---------------|-------------|
| `mipagina.html` | Main page |
| `nuestratienda.html` + `nuestratienda.css` | Our store page |
| `productos.html` + `productos.css` | Products page |
| `accesorios.html` + `acessorio.css` | Accessories page |
| `contactos.html` + `conctactos.css` | Contact page |
| `quienesomos.html` + `quienessomos.css` | About us page |
| `pagina.css` | Global styles |
| `imagenes/` | General images |
| `imagenesheader/` | Header images |
| `imagenesproductos/` | Product images |
| `imagenesaccesorios/` | Accessory images |
| `imagenesbody/` | Body section images |
| `imagenessection/` | Section images |
| `imagenestitulo/` | Title images |
| `imagenesarticle/` | Article images |
| `musica/` | Audio files |
| `letras/` | Text / lyrics content |

---

## What I Learned

- Semantic HTML structure (`header`, `nav`, `main`, `section`, `article`, `footer`)
- Linking multiple HTML pages together
- Writing CSS from scratch (colors, fonts, layout, spacing)
- Organizing a project with separate pages and stylesheets
- Working with images and media files

---

## HTML + CSS Theory

### What is HTML?

HTML (HyperText Markup Language) is the skeleton of every webpage. It defines the **structure and content** using tags — elements that tell the browser what each piece of content is.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

### Semantic Structure

Semantic tags give meaning to the layout, making it readable for both humans and search engines.

| Tag | Purpose |
|-----|---------|
| `<header>` | Top section — logo, title, nav |
| `<nav>` | Navigation links |
| `<main>` | Main content of the page |
| `<section>` | A thematic group of content |
| `<article>` | Self-contained piece of content |
| `<aside>` | Side content (sidebar, tips) |
| `<footer>` | Bottom section — credits, links |

### Common HTML Tags

```html
<!-- Headings -->
<h1>Main Title</h1>
<h2>Subtitle</h2>

<!-- Text -->
<p>Paragraph</p>
<strong>Bold</strong>
<em>Italic</em>

<!-- Links and images -->
<a href="page.html">Click here</a>
<img src="photo.jpg" alt="Description">

<!-- Lists -->
<ul>
  <li>Unordered item</li>
</ul>
<ol>
  <li>Ordered item</li>
</ol>

<!-- Forms -->
<form>
  <input type="text" placeholder="Your name">
  <button type="submit">Send</button>
</form>
```

---

### What is CSS?

CSS (Cascading Style Sheets) controls the **appearance and layout** of HTML elements — colors, fonts, spacing, and positioning.

```css
/* Select an element and apply styles */
h1 {
  color: #333;
  font-size: 2rem;
  text-align: center;
}

p {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}
```

### How to Link CSS to HTML

```html
<!-- In the <head> of your HTML file -->
<link rel="stylesheet" href="pagina.css">
```

### The Box Model

Every HTML element is a box made of four layers:

```
+---------------------------+
|        MARGIN             |  <- space outside the element
|  +---------------------+  |
|  |      BORDER         |  |  <- visible border
|  |  +---------------+  |  |
|  |  |    PADDING    |  |  |  <- space inside the border
|  |  |  +---------+  |  |  |
|  |  |  | CONTENT |  |  |  |  <- text, image, etc.
|  |  |  +---------+  |  |  |
|  |  +---------------+  |  |
|  +---------------------+  |
+---------------------------+
```

```css
div {
  margin: 20px;       /* outside spacing */
  border: 1px solid #ccc;
  padding: 10px;      /* inside spacing */
  width: 300px;       /* content width */
}
```

### Common CSS Properties

```css
/* Colors and background */
color: #ff0000;
background-color: #f5f5f5;

/* Typography */
font-family: Arial, sans-serif;
font-size: 16px;
font-weight: bold;
text-align: center;
text-decoration: none;    /* removes underline from links */

/* Spacing */
margin: 10px 20px;        /* top/bottom left/right */
padding: 5px 10px 5px 10px; /* top right bottom left */

/* Sizing */
width: 100%;
max-width: 1200px;
height: auto;

/* Display */
display: block;
display: inline;
display: flex;

/* Borders */
border: 2px solid #333;
border-radius: 8px;       /* rounded corners */

/* Flexbox (basic layout) */
display: flex;
justify-content: center;  /* horizontal alignment */
align-items: center;      /* vertical alignment */
gap: 16px;
```

### CSS Selectors

```css
/* By tag */
p { color: black; }

/* By class */
.card { background: white; }

/* By ID */
#header { height: 80px; }

/* Nested */
nav a { text-decoration: none; }

/* On hover */
a:hover { color: blue; }
```

---

## How to Run

No installation needed. Just open any `.html` file in your browser:

```bash
# Clone the repo
git clone https://github.com/sergioromero2k/page_web_html_basic.git

# Open the main page
open mipagina.html
```

Or simply double-click `mipagina.html` in your file explorer.

---

## Context

This project was built in **2021** during an HTML + CSS fundamentals course. It is kept here as a personal archive and reminder of where it all started.

---

## License

Personal archive project — feel free to use it as a reference or learning template.
