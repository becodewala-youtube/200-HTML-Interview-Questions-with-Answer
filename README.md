# 200-HTML-Interview-Questions-with-Answer🔥

### 1. What is HTML?

**HTML (HyperText Markup Language)** is the **standard markup language** used to create and structure content on the web. It defines the skeleton of a webpage, organizing text, images, links, and other media.



### 2. What does HTML stand for?

**HTML** stands for **HyperText Markup Language**.

* **HyperText** means the text contains links to other texts (webpages).
* **Markup Language** means it uses tags to mark elements in a document.



### 3. What are HTML tags?

**HTML tags** are special keywords wrapped in angle brackets `< >` that tell the browser how to display content.

* Tags usually come in pairs: an opening tag `<p>` and a closing tag `</p>`.
* Some tags are self-closing like `<br>` or `<img>`.



### 4. What is the role of HTML in web development?

* HTML **structures** the content of web pages (headings, paragraphs, lists, images, links).
* It works with CSS (styling) and JavaScript (functionality) to create rich web experiences.
* HTML provides the **foundation** for websites and web apps.



### 5. Who created HTML?

* HTML was created by **Tim Berners-Lee** in **1991** while working at CERN (European Organization for Nuclear Research).
* It was designed to help share and link scientific documents.



### 6. What is the difference between HTML and HTML5?

* **HTML** refers to the original markup language version.
* **HTML5** is the **latest version** standardized in 2014, introducing:

  * New semantic tags (like `<article>`, `<section>`)
  * Multimedia support (audio, video)
  * Canvas for drawing
  * Improved form controls
  * APIs for web storage, geolocation, etc.



### 7. How do you write a basic HTML page?

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My First Page</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>Welcome to my webpage.</p>
</body>
</html>
```



### 8. What is the purpose of `<!DOCTYPE html>`?

* Declares the **document type** and version of HTML being used.
* Informs browsers to render the page in **standards-compliant mode** rather than quirks mode.



### 9. What are semantic tags in HTML?

* Semantic tags clearly describe the **meaning** of the content.
* Examples: `<header>`, `<footer>`, `<article>`, `<nav>`, `<section>`.
* They improve **SEO** and accessibility.



### 10. What are the main components of an HTML document?

1. `<!DOCTYPE html>` – document type declaration
2. `<html>` – root element
3. `<head>` – meta info (title, charset, styles, scripts)
4. `<body>` – visible content





### 11. What is the `<html>` tag?

* The **root element** wrapping the entire HTML document.
* Contains the `<head>` and `<body>` tags.



### 12. What is the `<head>` tag used for?

* Holds **metadata** and resources like:

  * `<title>` of the page
  * Character encoding (`<meta>`)
  * Links to CSS files
  * Scripts
  * SEO tags



### 13. What is the `<body>` tag used for?

* Contains the **visible content** of the webpage like text, images, links, buttons, etc.



### 14. How do you insert comments in HTML?

* Comments are inserted between `<!--` and `-->` and are **not displayed** in the browser.

```html
<!-- This is a comment -->
```



### 15. What is the use of the `lang` attribute in HTML?

* Specifies the **language** of the document for accessibility and SEO.
* Helps browsers and screen readers select the correct language settings.

```html
<html lang="en"> <!-- English -->
```



### 16. What is the difference between block and inline elements?

* **Block elements** take up the full width available and start on a new line. Examples: `<div>`, `<p>`, `<h1>`.
* **Inline elements** take only the width they need and do not start on a new line. Examples: `<span>`, `<a>`, `<strong>`.



### 17. What is the `<div>` tag used for?

* The `<div>` tag is a **block-level container** used to group other HTML elements.
* It has **no semantic meaning** by itself but is used to apply CSS styles or manipulate groups of elements with JavaScript.



### 18. What is the `<span>` tag used for?

* The `<span>` tag is an **inline container** used to group inline elements.
* Like `<div>`, it has no semantic meaning but is useful for styling or scripting parts of text without breaking the flow.



### 19. What is the difference between `<b>` and `<strong>`?

* `<b>` **bolds text** without implying any extra importance.
* `<strong>` **indicates strong importance** or emphasis, and browsers usually render it as bold by default.



### 20. What is the difference between `<i>` and `<em>`?

* `<i>` italicizes text without adding emphasis. Often used for terms or foreign words.
* `<em>` means **emphasis** on the content, usually rendered in italics but with semantic meaning useful for accessibility.
