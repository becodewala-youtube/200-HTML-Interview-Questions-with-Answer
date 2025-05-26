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






### 21. What is the use of `<br>` and `<hr>` tags?

* `<br>` inserts a **line break** within text without creating a new paragraph.
* `<hr>` inserts a **horizontal rule** (a thematic break or divider) between sections of content.


### 22. What are self-closing tags?

* Tags that **do not have a closing tag** and end with a slash inside the tag, e.g., `<br />`, `<img />`.
* They represent empty elements that don’t enclose any content.



### 23. What is the `<pre>` tag?

* The `<pre>` tag displays text **preformatted**, preserving spaces, tabs, and line breaks exactly as in the source.
* Used for code blocks or text where formatting matters.



### 24. What is the `<code>` tag?

* The `<code>` tag represents a fragment of **computer code** or programming language.
* Typically styled with a monospace font.



### 25. What is the `<mark>` tag?

* The `<mark>` tag highlights or **marks** text as relevant or important, usually with a yellow background.



### 26. What is the `<blockquote>` tag?

* The `<blockquote>` tag is used for **long quotations** from other sources.
* Usually indents the text to show it is a block quote.



### 27. What is the `<cite>` tag?

* The `<cite>` tag defines the **title of a work** (e.g., book, article, website) or the source of a quotation.
* Typically italicized.



### 28. What is the `<abbr>` tag?

* The `<abbr>` tag is used for **abbreviations or acronyms**.
* When hovered, it can display the full phrase using the `title` attribute.

```html
<abbr title="HyperText Markup Language">HTML</abbr>
```



### 29. What is the `<address>` tag?

* The `<address>` tag contains **contact information** for the author or owner of a document or article.
* Usually displayed in italic by browsers.



### 30. What is the `<time>` tag?

* The `<time>` tag represents a **specific time or date**.
* It can include a machine-readable `datetime` attribute for better SEO and accessibility.

```html
<time datetime="2025-05-24">May 24, 2025</time>
```



### 31. What are attributes in HTML?

Attributes are **key-value pairs** added to HTML tags that provide **additional information** about an element.
They are always written in the opening tag and affect how the element behaves or displays.

**Example:**

```html
<a href="https://example.com">Visit</a>
```

Here, `href` is an attribute that tells where the link goes.

 

### 32. What is the `title` attribute?

The `title` attribute specifies **extra information** about an element, which is often displayed as a tooltip when the user hovers over the element.

**Example:**

```html
<p title="Hello there!">Hover over me</p>
```

 

### 33. What is the difference between `id` and `class`?

* `id` is a **unique identifier** for a single HTML element. It should not be repeated in a page.
* `class` is used to group multiple elements and apply **shared styles or behaviors**.

**Example:**

```html
<div id="header"></div>
<div class="card"></div>
<div class="card"></div>
```

 

### 34. What is the `style` attribute used for?

The `style` attribute allows **inline CSS styling** of individual elements.

**Example:**

```html
<p style="color: blue; font-size: 18px;">Styled Text</p>
```

 

### 35. What are `data-*` attributes?

Custom attributes used to store **extra data** in HTML elements. They do not affect layout or style but are often used by JavaScript.

**Example:**

```html
<div data-user-id="1234" data-role="admin">User</div>
```

In JavaScript:

```js
element.dataset.userId  // "1234"
element.dataset.role    // "admin"
```

 

### 36. What is the use of the `alt` attribute in images?

The `alt` (alternative text) attribute is used with `<img>` tags to describe the **image content**. It is important for accessibility and shown if the image fails to load.

**Example:**

```html
<img src="logo.png" alt="Company Logo" />
```

 

### 37. What is the difference between `readonly` and `disabled`?

* `readonly` allows users to **see and copy the value**, but not change it.
* `disabled` **disables** the element entirely — users cannot interact with it, and it won't be submitted in a form.

**Example:**

```html
<input type="text" value="Read Only" readonly>
<input type="text" value="Disabled" disabled>
```

 

### 38. What is the `tabindex` attribute?

The `tabindex` attribute defines the **tab order** of elements when navigating with the `Tab` key.

* A positive value sets a specific order.
* `0` follows natural flow.
* `-1` makes it **focusable by JavaScript only**.

**Example:**

```html
<button tabindex="1">First</button>
<button tabindex="2">Second</button>
```

 

### 39. What is the `contenteditable` attribute?

This attribute allows the content of the element to be **editable directly in the browser**.

**Example:**

```html
<div contenteditable="true">Click and edit this text</div>
```

 

### 40. What is the `hidden` attribute?

The `hidden` attribute makes an element **invisible** on the page. It behaves like `display: none` in CSS.

**Example:**

```html
<p hidden>This paragraph is hidden.</p>
```

 
