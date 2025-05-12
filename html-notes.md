# 🌐 Introduction to HTML

HTML (**HyperText Markup Language**) is the standard markup language used to create and structure content on the web. It tells the browser **what each part of a webpage is** — whether it's a heading, a paragraph, an image, or a link.

### 🔎 Key Points:
- HTML uses **tags** (like `<p>`, `<h1>`, `<img>`) to define elements.
- It's the **foundation** of every webpage.
- Works hand-in-hand with **CSS** (for styling) and **JavaScript** (for interactivity).
- HTML is **not a programming language** — it's a **markup language**.

### 📘 Example:
```html
<h1>This is a Heading</h1>
<p>This is a paragraph of text.</p>
# 🧱 Basic HTML Document Structure (with Comments)

Every HTML document begins with a standard structure that helps browsers interpret and render the content properly.

---

## 📄 Standard HTML Template with Detailed Comments

```html
<!DOCTYPE html>
<!-- Declares that this is an HTML5 document -->

<html lang="en">
<!-- The root element of the HTML document; 'lang="en"' sets the page language to English -->

  <head>
    <!-- Contains meta-information about the page (not displayed to users) -->

    <meta charset="UTF-8" />
    <!-- Sets character encoding to UTF-8 to support all major characters/symbols -->

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Ensures responsive design; scales properly on all device widths -->

    <title>Document</title>
    <!-- Sets the title shown in the browser tab -->
  </head>

  <body>
    <!-- Contains all visible content of the web page -->

    <!-- Your page content goes here -->

  </body>

</html>
<!-- End of HTML document -->
