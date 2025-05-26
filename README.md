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

 

### 41. What is the `<form>` tag?

The `<form>` tag is used to **create an HTML form** that allows users to input data and send it to a server for processing.

**Syntax:**

```html
<form action="/submit" method="post">
  <!-- form elements go here -->
</form>
```

* The `<form>` element **wraps form controls** (input, textarea, button, etc.).
* Data is sent to the URL in the `action` attribute when the user submits the form.



### 42. What are different input types in HTML5?

HTML5 introduced **many input types** to improve user experience and validation:

| Input Type        | Purpose                     |
| ----------------- | --------------------------- |
| `text`            | Single-line text input      |
| `password`        | Obscured password input     |
| `email`           | Validates email format      |
| `url`             | Validates URL format        |
| `number`          | Numeric input with controls |
| `range`           | Slider for numeric range    |
| `date`, `time`    | Date/time pickers           |
| `checkbox`        | Multi-select options        |
| `radio`           | Single-select among choices |
| `file`            | Upload files                |
| `submit`, `reset` | Submit or reset form        |
| `hidden`          | Invisible input             |
| `tel`             | Telephone number            |
| `color`           | Color picker                |

**Example:**

```html
<input type="email" name="userEmail">
<input type="number" min="1" max="100">
```

 

### 43. What is the use of the `action` and `method` attributes?

* `action`: URL where form data will be **submitted**.
* `method`: HTTP method for submission (`GET` or `POST`).

**Example:**

```html
<form action="/login" method="post">
  ...
</form>
```

 

### 44. What is the difference between `GET` and `POST`?

| Feature    | GET                        | POST                      |
| ---------- | -------------------------- | ------------------------- |
| Visibility | Data in URL (query string) | Data in request body      |
| Security   | Less secure                | More secure               |
| Use Case   | Fetching data              | Sending sensitive data    |
| Limits     | Limited data size          | No size limit (practical) |

**GET Example:**

```html
<form action="/search" method="get">
  <input name="q" />
</form>
```

 

### 45. What is the `<label>` tag?

The `<label>` tag improves **accessibility** by associating text with form elements.

**Example:**

```html
<label for="email">Email:</label>
<input type="email" id="email">
```

Clicking the label focuses the input field.

 

### 46. How do you group related form elements?

Use the `<fieldset>` and `<legend>` tags to **logically group** related fields.

 

### 47. What is `<fieldset>` and `<legend>`?

* `<fieldset>`: Groups related controls
* `<legend>`: Caption/title for the fieldset

**Example:**

```html
<fieldset>
  <legend>Personal Info</legend>
  <label for="name">Name:</label>
  <input id="name" type="text">
</fieldset>
```



### 48. What is the `placeholder` attribute?

It shows **gray hint text** inside the input field, describing expected input.

**Example:**

```html
<input type="text" placeholder="Enter your name">
```

 

### 49. What is the `required` attribute?

It ensures the user **cannot submit** the form without filling the field.

**Example:**

```html
<input type="email" required>
```

 

### 50. What is the `pattern` attribute used for?

It uses **regular expressions** to define allowed input format.

**Example:**

```html
<input type="text" pattern="[A-Za-z]{3,}" title="At least 3 letters">
```



### 51. What is the use of `<select>` and `<option>`?

Used to create **dropdown lists**.

**Example:**

```html
<select name="country">
  <option value="india">India</option>
  <option value="usa">USA</option>
</select>
```



### 52. What is `<datalist>`?

`<datalist>` provides **autocomplete suggestions** while typing in an input.

**Example:**

```html
<input list="browsers">
<datalist id="browsers">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Edge">
</datalist>
```



### 53. What is the difference between `<textarea>` and `<input type="text">`?

| Feature  | `<input type="text">` | `<textarea>`       |
| -------- | --------------------- | ------------------ |
| Content  | Single-line           | Multi-line         |
| Use Case | Name, email, phone    | Messages, comments |

**Example:**

```html
<textarea rows="4" cols="50">Your feedback</textarea>
```



### 54. What are radio buttons and checkboxes?

* **Radio buttons** allow **only one** option to be selected.
* **Checkboxes** allow **multiple selections**.

**Radio Example:**

```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```

**Checkbox Example:**

```html
<input type="checkbox" name="hobby" value="reading"> Reading
<input type="checkbox" name="hobby" value="sports"> Sports
```


### 55. How can you disable a field in HTML?

Use the `disabled` attribute. Disabled fields **cannot be interacted with** and are not submitted.

**Example:**

```html
<input type="text" value="Read-only" disabled>
```


### 56. How do you create a table in HTML?

You use the `<table>` element along with `<tr>` (table row), `<td>` (table data), and `<th>` (table header).

**Example:**

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Vikash</td>
    <td>22</td>
  </tr>
</table>
```



### 57. What is the `<thead>`, `<tbody>`, and `<tfoot>`?

These tags are used to **semantically separate** different parts of the table.

* `<thead>`: Groups header rows
* `<tbody>`: Groups the body (main content)
* `<tfoot>`: Groups the footer rows (e.g., summary, totals)

**Example:**

```html
<table>
  <thead>
    <tr><th>Product</th><th>Price</th></tr>
  </thead>
  <tbody>
    <tr><td>Apple</td><td>$1</td></tr>
    <tr><td>Banana</td><td>$0.5</td></tr>
  </tbody>
  <tfoot>
    <tr><td>Total</td><td>$1.5</td></tr>
  </tfoot>
</table>
```



### 58. What is the purpose of `colspan` and `rowspan`?

These attributes are used to **merge cells**.

* `colspan`: Merges cells **horizontally** (across columns)
* `rowspan`: Merges cells **vertically** (across rows)

**Example:**

```html
<td colspan="2">Merged Column</td>
<td rowspan="2">Merged Row</td>
```



### 59. What is the difference between `<td>` and `<th>`?

| Tag    | Purpose           | Appearance                 |
| ------ | ----------------- | -------------------------- |
| `<td>` | Table Data Cell   | Normal text                |
| `<th>` | Table Header Cell | Bold & centered by default |

**Example:**

```html
<tr>
  <th>Name</th>
  <td>Vikash</td>
</tr>
```



### 60. How do you apply a border to a table?

Use the `border` attribute (HTML) or better with **CSS**.

**HTML (not recommended in modern use):**

```html
<table border="1">
```

**CSS (preferred):**

```html
<style>
  table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
  }
</style>
```



### 61. How can you merge cells in a table?

Use `colspan` (horizontal merge) or `rowspan` (vertical merge).

**Example:**

```html
<tr>
  <td colspan="2">Merged across 2 columns</td>
</tr>
```



### 62. How do you align content in a table?

Use the `text-align` (horizontal) and `vertical-align` (vertical) CSS properties.

**Example:**

```html
<td style="text-align:center; vertical-align:middle;">Centered Cell</td>
```





### 63. What are the types of lists in HTML?

There are **three main types**:

* **Ordered List** (`<ol>`) – numbered
* **Unordered List** (`<ul>`) – bulleted
* **Description List** (`<dl>`) – term-definition



### 64. What is the `<ol>` tag?

* Stands for **Ordered List**
* Creates a numbered list

**Example:**

```html
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```



### 65. What is the `<ul>` tag?

* Stands for **Unordered List**
* Creates a bulleted list

**Example:**

```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>
```



### 66. What is the `<li>` tag?

* Stands for **List Item**
* Used inside `<ol>` and `<ul>` to define items

**Example:**

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

 
### 67. What is a description list?

A **description list** is used to define **terms and their descriptions**, like a glossary.

 

### 68. What is the `<dl>`, `<dt>`, and `<dd>` tags?

* `<dl>`: Description List (wrapper)
* `<dt>`: Definition Term
* `<dd>`: Definition Description

**Example:**

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

 





### 69. How do you create a hyperlink?

You use the `<a>` (anchor) tag.

**Example:**

```html
<a href="https://www.google.com">Visit Google</a>
```



### 70. What is the `href` attribute?

* **`href`** stands for **Hypertext Reference**.
* It specifies the **URL** of the page the link goes to.

**Example:**

```html
<a href="https://example.com">Click Here</a>
```

 

### 71. What is the `target="_blank"` attribute?

* Opens the link in a **new browser tab or window**.
* Prevents users from losing their current page.

**Example:**

```html
<a href="https://example.com" target="_blank">Open in New Tab</a>
```

 

### 72. What is the difference between absolute and relative URLs?

| Type         | Description                       | Example                             |
| ------------ | --------------------------------- | ----------------------------------- |
| Absolute URL | Full path including domain name   | `https://example.com/about.html`    |
| Relative URL | Path relative to current location | `about.html` or `../images/pic.png` |



### 73. How do you create an email link?

Use the `mailto:` scheme inside `href`.

**Example:**

```html
<a href="mailto:someone@example.com">Send Email</a>
```



### 74. How do you link to a section on the same page?

1. Give the target element an `id`.
2. Use `href="#id"` in the anchor.

**Example:**

```html
<a href="#contact">Go to Contact Section</a>

...

<h2 id="contact">Contact Us</h2>
```



### 75. How do you create a download link?

Use the `download` attribute in the `<a>` tag.

**Example:**

```html
<a href="file.pdf" download>Download PDF</a>
```




### 76. How do you embed an image in HTML?

Use the `<img>` tag with `src` and `alt` attributes.

**Example:**

```html
<img src="logo.png" alt="Website Logo">
```



### 77. What is the `alt` attribute?

* Provides **alternative text** for the image.
* Used by **screen readers** and when the image fails to load.

**Example:**

```html
<img src="dog.jpg" alt="A cute dog">
```



### 78. What is the use of `srcset`?

* Allows browsers to choose the **best image** for the screen resolution or size.
* Improves performance on different devices.

**Example:**

```html
<img src="small.jpg" 
     srcset="large.jpg 1024w, medium.jpg 640w, small.jpg 320w" 
     alt="Responsive Image">
```



### 79. How do you embed a video in HTML?

Use the `<video>` tag with `controls`, `src`, and optional `poster`.

**Example:**

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```



### 80. What are the attributes of the `<video>` tag?

* `controls`: Shows video controls (play, pause, etc.)
* `autoplay`: Plays automatically
* `muted`: Starts muted
* `loop`: Repeats the video
* `poster`: Shows an image before the video loads



### 81. How do you embed audio?

Use the `<audio>` tag with `controls`.

**Example:**

```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```



### 82. What is the difference between `<embed>`, `<object>`, and `<iframe>`?

| Tag        | Use Case                        | Common Uses                  |
| ---------- | ------------------------------- | ---------------------------- |
| `<embed>`  | Embeds external content         | PDFs, videos, Flash (legacy) |
| `<object>` | Embeds external files & plugins | Multimedia, Flash, PDFs      |
| `<iframe>` | Embeds another HTML page        | YouTube videos, Maps         |



### 83. How do you embed a YouTube video?

Use an `<iframe>` with the video URL from YouTube’s "Share → Embed" option.

**Example:**

```html
<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
  title="YouTube video" frameborder="0" 
  allowfullscreen>
</iframe>
```





### 84. What are semantic elements?

**Semantic elements** are HTML5 elements that **describe their content's meaning** or **role** within a page.

🟢 Examples:

* `<header>` – represents the top section of a page or section.
* `<footer>` – defines the bottom section or conclusion.
* `<article>` – a self-contained piece of content.
* `<nav>` – for navigation links.

🟥 **Non-semantic**: `<div>`, `<span>` – give no meaningful information about their content.

 

### 85. What is the use of `<header>`?

* The `<header>` element represents **introductory content** for a page or a section.
* Typically contains a logo, title, navigation menu, or introductory text.

**Example:**

```html
<header>
  <h1>My Blog</h1>
  <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
  </nav>
</header>
```



### 86. What is the `<footer>` tag?

* Represents the **footer** for a page or a section.
* Common content: contact info, copyright, links.

**Example:**

```html
<footer>
  <p>&copy; 2025 Vikash Kumar. All rights reserved.</p>
</footer>
```



### 87. What is the `<nav>` tag?

* Represents a section of the page **dedicated to navigation**.
* Typically contains links to other sections of the site.

**Example:**

```html
<nav>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="/projects">Projects</a></li>
  </ul>
</nav>
```


### 88. What is the `<main>` tag?

* Specifies the **main content area** of the page.
* Should be unique and **not repeated** across pages (unlike headers or footers).

**Example:**

```html
<main>
  <h2>Welcome to My Portfolio</h2>
  <p>This is the core content of the page.</p>
</main>
```



### 89. What is the `<section>` tag?

* Groups related content into **thematic blocks**.
* Useful for splitting pages into meaningful parts.

**Example:**

```html
<section>
  <h2>Services</h2>
  <p>We offer web development and design services.</p>
</section>
```



### 90. What is the `<article>` tag?

* Represents a **self-contained** piece of content.
* Often used for blog posts, news articles, or comments.

**Example:**

```html
<article>
  <h2>10 Tips to Learn HTML</h2>
  <p>Start by mastering the basics...</p>
</article>
```



### 91. What is the `<aside>` tag?

* Represents **secondary content** or sidebars that are indirectly related to the main content.

**Example:**

```html
<aside>
  <h3>Recent Posts</h3>
  <ul>
    <li>Understanding CSS Grid</li>
    <li>JavaScript ES6 Features</li>
  </ul>
</aside>
```



### 92. Why should you use semantic HTML?

✅ **Benefits of Semantic HTML:**

* **Improved accessibility**: Screen readers can understand the structure better.
* **Better SEO**: Search engines can index your content more accurately.
* **Easier maintenance**: Developers can understand and edit code more efficiently.
* **Cleaner code structure**: Improves collaboration and debugging.





### 93. What is Web Storage API?

The **Web Storage API** allows you to store data in the browser **locally** and **persistently**, without using cookies.

✅ **Two types of Web Storage:**

* `localStorage` – Data persists even after the browser is closed.
* `sessionStorage` – Data persists only during the session.

🔐 It stores data in **key/value** pairs as strings.

**Example:**

```javascript
localStorage.setItem('name', 'Vikash');
console.log(localStorage.getItem('name')); // Vikash
```



### 94. What is `localStorage`?

* Stores data **permanently** in the browser.
* Survives page refresh and browser restart.
* Can store up to **5-10MB** depending on the browser.

**Example:**

```javascript
localStorage.setItem('theme', 'dark');
const theme = localStorage.getItem('theme'); // "dark"
```

Use case: Remembering user preferences like theme, language, etc.



### 95. What is `sessionStorage`?

* Stores data **temporarily** for the duration of a **page session**.
* Data is cleared when the page/tab is closed.

**Example:**

```javascript
sessionStorage.setItem('cartItem', 'Laptop');
const item = sessionStorage.getItem('cartItem'); // "Laptop"
```

Use case: Shopping cart, quiz progress, session-specific values.


### 96. What is Geolocation API?

* Allows websites to **access the geographical location** of the user (with permission).
* Works via **GPS**, **Wi-Fi**, or **IP address**.

**Example:**

```javascript
navigator.geolocation.getCurrentPosition(function(position) {
  console.log(position.coords.latitude);
  console.log(position.coords.longitude);
});
```

Use case: Map apps, food delivery apps, nearby search features.


### 97. What is the Drag and Drop API?

* Enables **dragging and dropping** elements on a web page.
* Requires using the `draggable` attribute and handling `dragstart`, `drop`, and `dragover` events.

**HTML:**

```html
<div id="drag" draggable="true">Drag me</div>
<div id="drop-zone">Drop here</div>
```

**JS:**

```javascript
const drag = document.getElementById("drag");
drag.addEventListener("dragstart", (e) => e.dataTransfer.setData("text", "Hello"));

const dropZone = document.getElementById("drop-zone");
dropZone.addEventListener("dragover", (e) => e.preventDefault());
dropZone.addEventListener("drop", (e) => {
  const data = e.dataTransfer.getData("text");
  dropZone.innerText = data;
});
```



### 98. What is the `<canvas>` element?

* `<canvas>` provides a **drawable region** in HTML for rendering **graphics on the fly** using JavaScript.

Use case: Games, charts, image editing tools, animations.

**Example:**

```html
<canvas id="myCanvas" width="200" height="100"></canvas>

<script>
  const canvas = document.getElementById('myCanvas');
  const ctx = canvas.getContext('2d');
  ctx.fillStyle = 'blue';
  ctx.fillRect(20, 20, 150, 50);
</script>
```



### 99. What is the difference between `<canvas>` and `<svg>`?

| Feature         | `<canvas>`                            | `<svg>`                            |
| --------------- | ------------------------------------- | ---------------------------------- |
| Type            | Immediate Mode (bitmap-based)         | Retained Mode (vector-based)       |
| DOM Integration | Doesn't store elements in DOM         | Every shape is part of DOM         |
| Interactivity   | Manual via coordinates                | Built-in via event listeners       |
| Use Cases       | Games, visual effects, dynamic charts | Diagrams, icons, charts, UI vector |



### 100. What is the `<template>` tag?

* The `<template>` tag defines **HTML that is not rendered** when the page loads but can be **cloned and used later** via JavaScript.
* Useful for rendering dynamic content like cards, modals, etc.

**Example:**

```html
<template id="cardTemplate">
  <div class="card">
    <h2></h2>
    <p></p>
  </div>
</template>

<script>
  const template = document.getElementById('cardTemplate');
  const clone = template.content.cloneNode(true);
  clone.querySelector('h2').textContent = "Dynamic Title";
  clone.querySelector('p').textContent = "This was loaded dynamically!";
  document.body.appendChild(clone);
</script>
```



### 101. What is accessibility in HTML?

Accessibility refers to **making web content usable for everyone**, including:

* People with **visual, auditory, motor, or cognitive impairments**.
* Users using **assistive technologies** like screen readers.

🔍 It ensures:

* Keyboard navigation is possible.
* Screen readers can read elements clearly.
* Proper **semantic HTML** is used.



### 102. What is ARIA?

**ARIA (Accessible Rich Internet Applications)** is a set of attributes that make dynamic content and custom UI elements accessible.

✅ Common ARIA roles and properties:

* `role="button"` – defines a custom element as a button.
* `aria-label="Close menu"` – labels an unlabeled button for screen readers.
* `aria-hidden="true"` – hides elements from assistive technologies.

> ⚠️ ARIA is a fallback. Always prefer **native HTML** elements first.



### 103. What is the `role` attribute?

The `role` attribute explicitly defines the **type of element** for assistive technologies.

**Example:**

```html
<div role="navigation">
  <ul>
    <li><a href="/">Home</a></li>
  </ul>
</div>
```

🟢 Use case:
If you're using non-semantic tags (like `<div>`), `role` helps screen readers identify their purpose.



### 104. What is the use of `aria-label`?

The `aria-label` provides an **invisible label** that screen readers will announce.

**Example:**

```html
<button aria-label="Close">✖</button>
```

Even though the button only has an icon (`✖`), screen readers will announce it as “Close”.



### 105. What are best practices for accessible forms?

✅ Use `<label>` for each input:

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email">
```

✅ Group related fields with `<fieldset>` and `<legend>`.

✅ Use `aria-required="true"` or native `required` attribute.

✅ Provide clear error messages with `aria-describedby`.

✅ Ensure all inputs are **keyboard navigable**.






### 106. What is the `<meta>` tag?

The `<meta>` tag defines **metadata** like character encoding, page description, author, keywords, etc.

**Example:**

```html
<meta name="author" content="Vikash Kumar">
<meta name="description" content="A guide to learning HTML and web development.">
```



### 107. What is the viewport meta tag?

The **viewport meta tag** helps make web pages **responsive** on mobile devices.

**Example:**

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

🧠 This ensures:

* The page scales properly on different screen sizes.
* Improves mobile usability and SEO.



### 108. How do you set `charset` in HTML?

The `charset` attribute defines the **character encoding** used in the document.

**Example (UTF-8, most common):**

```html
<meta charset="UTF-8">
```

Ensures support for **all languages and symbols**.



### 109. What is the use of `<meta name="description">`?

This meta tag gives a **short summary** of the page content (used in search engine results).

**Example:**

```html
<meta name="description" content="Learn HTML5 from beginner to advanced with examples.">
```

🔍 Google often displays this in search snippets, which affects **click-through rates** (CTR).



### 110. How does HTML help in SEO?

HTML plays a **critical role** in SEO (Search Engine Optimization):

✅ Use of:

* `<title>` for page titles.
* `<h1> to <h6>` for headings.
* `<a href>` for internal/external linking.
* `<meta>` for descriptions and keywords.
* Semantic elements like `<article>`, `<nav>`, `<section>` for structure.

✅ Helps:

* Search engines understand page structure and content.
* Improve indexing and visibility in search results.





### 111. How do you link a CSS file in HTML?

You use the `<link>` tag inside the `<head>` of your HTML document:

```html
<link rel="stylesheet" href="styles.css">
```

* `rel="stylesheet"` specifies the relationship.
* `href="styles.css"` points to the CSS file.



### 112. What are inline, internal, and external CSS?

✅ **Inline CSS**
Applied directly on an element using the `style` attribute:

```html
<p style="color: red;">Inline styled text</p>
```

✅ **Internal CSS**
Placed inside a `<style>` tag within the `<head>`:

```html
<head>
  <style>
    p { color: blue; }
  </style>
</head>
```

✅ **External CSS**
Linked using a separate `.css` file:

```html
<link rel="stylesheet" href="styles.css">
```

**Best Practice:** Use **external CSS** for maintainability.



### 113. How do you add JavaScript in HTML?

You use the `<script>` tag:

✅ **Internal JS** (inside HTML):

```html
<script>
  alert("Hello from JavaScript!");
</script>
```

✅ **External JS** (from a file):

```html
<script src="script.js"></script>
```



### 114. What is the `defer` and `async` attribute in scripts?

✅ `defer`:

* Loads script **in the background** while parsing HTML.
* Executes **after HTML is fully parsed** (in order).

```html
<script src="main.js" defer></script>
```

✅ `async`:

* Loads and executes script **as soon as it’s ready** (not in order).

```html
<script src="analytics.js" async></script>
```

> Use `defer` for scripts that manipulate DOM. Use `async` for independent scripts (like ads/analytics).



### 115. Can we add multiple CSS and JS files in HTML?

Yes ✅

**Multiple CSS:**

```html
<link rel="stylesheet" href="reset.css">
<link rel="stylesheet" href="main.css">
```

**Multiple JS:**

```html
<script src="jquery.js"></script>
<script src="app.js" defer></script>
```

> Order matters for both: load dependencies first.





### 116. What is responsive web design?

It’s a design approach where:

* Layouts **adapt** to screen size.
* Text and images **resize** automatically.
* Content is easily readable and usable on any device.

✅ Achieved using:

* CSS media queries
* Flexbox/Grid
* Percentage-based widths



### 117. What is the `<meta viewport>` tag?

It tells the browser **how to control the page's dimensions and scaling**.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

* `width=device-width`: Matches screen width.
* `initial-scale=1.0`: Default zoom level.

🔍 Without it, mobile browsers may render pages too zoomed out.



### 118. How do you make images responsive in HTML?

Use CSS to ensure images scale within containers:

```html
img {
  max-width: 100%;
  height: auto;
}
```

🔄 This ensures the image resizes proportionally to the parent container.


### 119. What is the role of media queries?

Media queries apply different CSS rules based on:

* Screen width
* Device type
* Orientation

**Example:**

```css
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```

📱 When the screen is 768px or smaller, the background changes.


### 120. How do you make a layout responsive using only HTML and CSS?

✅ Use **semantic HTML structure**.

✅ Use **CSS Flexbox** or **CSS Grid**:

```css
.container {
  display: flex;
  flex-wrap: wrap;
}
.item {
  flex: 1 1 100%;
}
@media (min-width: 768px) {
  .item {
    flex: 1 1 50%;
  }
}
```

✅ Combine with:

* `%` or `vw` units for width
* `max-width`, `min-width`
* Media queries


### 121. **Is HTML case-sensitive?**

**No**, HTML is **not case-sensitive**.
This means that `<DIV>`, `<div>`, and `<Div>` are interpreted the same way by the browser.

✅ However, it's a **best practice** to use **lowercase** for tags, attributes, and values (especially in HTML5) for consistency and readability:

```html
<!-- Recommended -->
<div class="example">Hello</div>

<!-- Not recommended -->
<DIV CLASS="example">Hello</DIV>
```



### 122. **Can you nest block-level elements inside inline elements?**

**No**, block-level elements **should not** be nested inside inline elements.
It goes against HTML rules and may lead to **unexpected rendering** or **browser correction**.

❌ Invalid:

```html
<span><div>Invalid Nesting</div></span>
```

✅ Valid:

```html
<div><span>Correct Nesting</span></div>
```

> Browsers might auto-correct, but it’s bad practice.



### 123. **What happens if you forget to close a tag?**

If you forget to close a tag:

* The browser tries to auto-correct the markup.
* It may **break layout or styling**.
* It can also cause **JavaScript errors** or affect screen readers.

❌ Bad:

```html
<p>This is a paragraph
<p>This is another
```

✅ Good:

```html
<p>This is a paragraph</p>
<p>This is another</p>
```



### 124. **Can you put multiple `<head>` or `<body>` tags?**

❌ No, an HTML document **should only have one** `<head>` and one `<body>`.

```html
<!-- Correct -->
<html>
  <head></head>
  <body></body>
</html>
```

> Having multiple `<head>` or `<body>` tags can **break your page** and cause **validation errors**.



### 125. **What are custom data attributes?**

Custom attributes prefixed with `data-`, used to store extra info on elements **without using classes or ids**.

✅ Example:

```html
<button data-user-id="123" data-role="admin">Click Me</button>
```

Access in JavaScript:

```js
const button = document.querySelector('button');
console.log(button.dataset.userId); // "123"
console.log(button.dataset.role); // "admin"
```



### 126. **What is the use of `<noscript>`?**

The `<noscript>` tag provides fallback content for users with **JavaScript disabled**.

✅ Example:

```html
<noscript>
  <p>Please enable JavaScript to use this site.</p>
</noscript>
```



### 127. **What is the `<base>` tag used for?**

Sets the **base URL** for all relative URLs in a document.

✅ Example:

```html
<base href="https://example.com/">
<a href="about.html">About</a> <!-- Resolves to https://example.com/about.html -->
```

> Should be placed **inside `<head>`**, and only one `<base>` tag is allowed.



### 128. **What is a favicon and how to set it?**

A **favicon** is the small icon that appears in the browser tab.

✅ Example:

```html
<link rel="icon" href="/images/favicon.ico" type="image/x-icon">
```

It can also use `.png`, `.svg`, etc.

Place it in the `<head>` section.



### 129. **What are void elements?**

Void elements are **self-closing** tags that **do not have closing tags**.

Examples include:

* `<img>`
* `<br>`
* `<hr>`
* `<meta>`
* `<link>`
* `<input>`

✅ Example:

```html
<img src="logo.png" alt="Logo">
```

> Don't try to use a closing tag like `</img>`—it’s invalid.



### 130. **What is the difference between `innerHTML` and `textContent`?**

| Feature         | `innerHTML`                         | `textContent` |
| --------------- | ----------------------------------- | ------------- |
| Returns         | HTML with tags                      | Only text     |
| Interprets HTML | Yes                                 | No            |
| Security        | Risk of XSS if used with user input | Safer         |
| Editable HTML   | Yes                                 | No            |

✅ Example:

```html
<div id="demo"><b>Hello</b></div>
```

```js
// innerHTML:
console.log(demo.innerHTML); // "<b>Hello</b>"

// textContent:
console.log(demo.textContent); // "Hello"
```


### 131. **How would you create a multi-step form in HTML?**

A multi-step form breaks a long form into several "steps" using `<fieldset>` and controlled visibility via CSS/JavaScript.

✅ Basic Structure (with JavaScript for step control):

```html
<form id="multiForm">
  <fieldset>
    <h2>Step 1</h2>
    <input type="text" placeholder="Name" required>
    <button type="button" onclick="next()">Next</button>
  </fieldset>

  <fieldset style="display:none;">
    <h2>Step 2</h2>
    <input type="email" placeholder="Email" required>
    <button type="submit">Submit</button>
  </fieldset>
</form>

<script>
  let current = 0;
  const steps = document.querySelectorAll('fieldset');
  function next() {
    steps[current].style.display = 'none';
    current++;
    steps[current].style.display = 'block';
  }
</script>
```



### 132. **How would you make a responsive navbar?**

Use **Flexbox**, **media queries**, and a **hamburger menu** for mobile view.

```html
<nav class="navbar">
  <div class="logo">Brand</div>
  <input type="checkbox" id="toggle">
  <label for="toggle" class="menu">&#9776;</label>
  <ul class="nav-links">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
  </ul>
</nav>

<style>
.navbar { display: flex; justify-content: space-between; align-items: center; }
.nav-links { display: flex; list-style: none; }
.menu { display: none; }

@media (max-width: 600px) {
  .nav-links { display: none; flex-direction: column; }
  #toggle:checked + .menu + .nav-links { display: flex; }
  .menu { display: block; cursor: pointer; }
}
</style>
```



### 133. **How can you validate a form without JavaScript?**

Use **HTML5 validation attributes**:

```html
<form>
  <input type="email" required>
  <input type="password" pattern=".{6,}" title="6 characters minimum" required>
  <input type="submit">
</form>
```

* `required`
* `pattern`
* `min`, `max`
* `type=email`, `type=number`, etc.



### 134. **How do you implement tabs using only HTML and CSS?**

Use **radio buttons or checkboxes**:

```html
<input type="radio" name="tab" id="tab1" checked>
<label for="tab1">Tab 1</label>
<input type="radio" name="tab" id="tab2">
<label for="tab2">Tab 2</label>

<div class="tab-content" id="content1">Content 1</div>
<div class="tab-content" id="content2">Content 2</div>

<style>
#tab1:checked ~ #content1 { display: block; }
#tab2:checked ~ #content2 { display: block; }
.tab-content { display: none; }
</style>
```



### 135. **How do you embed a Google Map?**

Use an `<iframe>`:

```html
<iframe
  src="https://www.google.com/maps/embed?pb=YOUR_MAP_QUERY"
  width="600"
  height="450"
  style="border:0;"
  allowfullscreen=""
  loading="lazy">
</iframe>
```

You can generate the link from Google Maps → Share → Embed a map.



### 136. **How do you make a modal using HTML and CSS?**

```html
<a href="#modal">Open Modal</a>

<div id="modal" class="modal">
  <div class="modal-content">
    <a href="#" class="close">&times;</a>
    <p>This is a modal!</p>
  </div>
</div>

<style>
.modal { display: none; position: fixed; top: 0; left: 0; background: rgba(0,0,0,0.6); width: 100%; height: 100%; }
.modal:target { display: block; }
.modal-content { background: white; margin: 10% auto; padding: 20px; width: 300px; }
.close { float: right; text-decoration: none; }
</style>
```



### 137. **How do you display a loading spinner?**

Use CSS animation:

```html
<div class="spinner"></div>

<style>
.spinner {
  border: 6px solid #ccc;
  border-top: 6px solid #3498db;
  border-radius: 50%;
  width: 40px; height: 40px;
  animation: spin 1s linear infinite;
}
@keyframes spin {
  0% { transform: rotate(0); }
  100% { transform: rotate(360deg); }
}
</style>
```



### 138. **How do you create a file upload form?**

```html
<form action="/upload" method="POST" enctype="multipart/form-data">
  <input type="file" name="myfile" required>
  <button type="submit">Upload</button>
</form>
```

> Use `enctype="multipart/form-data"` to handle file uploads.



### 139. **How do you make a sticky header?**

Use `position: sticky;`

```html
<header class="sticky">This is sticky</header>

<style>
.sticky {
  position: sticky;
  top: 0;
  background: white;
  z-index: 1000;
  padding: 10px;
  border-bottom: 1px solid #ccc;
}
</style>
```



### 140. **How do you add tooltips using HTML?**

Use the `title` attribute:

```html
<button title="Click to submit the form">Submit</button>
```

Or create custom tooltips with CSS:

```html
<span class="tooltip">Hover me
  <span class="tooltip-text">Tooltip info</span>
</span>

<style>
.tooltip { position: relative; cursor: pointer; }
.tooltip-text {
  visibility: hidden;
  background: black; color: #fff;
  position: absolute; top: -30px; left: 0;
  padding: 5px; border-radius: 5px;
}
.tooltip:hover .tooltip-text {
  visibility: visible;
}
</style>
```





### ✅ 141. **HTML vs XHTML**

| Feature            | HTML                                  | XHTML                                 |
| ------------------ | ------------------------------------- | ------------------------------------- |
| Syntax Flexibility | Less strict                           | Very strict (must be well-formed)     |
| Case Sensitivity   | Not case-sensitive                    | Tags and attributes must be lowercase |
| Closing Tags       | Optional for some tags (e.g., `<br>`) | Mandatory for all tags                |
| Parsing            | Tolerant of errors                    | Requires strict XML parsing           |
| MIME Type          | `text/html`                           | `application/xhtml+xml`               |



### ✅142 **HTML vs XML**

| Feature            | HTML                                 | XML                                |
| ------------------ | ------------------------------------ | ---------------------------------- |
| Purpose            | Structure and display of web content | Data transport and storage         |
| Predefined Tags    | Yes                                  | No (you define your own tags)      |
| Browsers           | Render HTML                          | Don't render XML, used in backend  |
| Syntax Flexibility | More lenient                         | Strict, well-formed documents only |



### ✅ 143 **HTML vs CSS**

| Feature        | HTML                  | CSS                            |
| -------------- | --------------------- | ------------------------------ |
| Role           | Structure and content | Style and presentation         |
| Syntax         | Tag-based             | Selector and declaration-based |
| Example        | `<p>Hello</p>`        | `p { color: red; }`            |
| Responsibility | What is on the page   | How it looks                   |



### ✅144. **HTML vs Markdown**

| Feature        | HTML                 | Markdown                         |
| -------------- | -------------------- | -------------------------------- |
| Complexity     | Verbose but powerful | Simple and minimal               |
| Learning Curve | Moderate             | Easy                             |
| Flexibility    | Highly customizable  | Limited styling capabilities     |
| Use Case       | Full web pages       | Writing blog posts, README files |



### ✅ 145. **HTML vs JavaScript**

| Feature       | HTML                     | JavaScript                         |
| ------------- | ------------------------ | ---------------------------------- |
| Purpose       | Structure and content    | Logic, behavior, interactivity     |
| Language Type | Markup Language          | Programming Language               |
| Example       | `<button>Click</button>` | `button.addEventListener("click")` |
| Runs In       | Browser                  | Browser or server (Node.js)        |



### ✅ 146 **Can we use emoji in HTML?**

Yes! Emojis are just Unicode characters. You can:

```html
<p>I ❤️ HTML! 🚀</p>
```

Or use Unicode code:

```html
<p>&#128512; (😀)</p>
```



### ✅ 147. **What are HTML entities?**

HTML entities represent reserved or special characters in HTML.

| Entity   | Meaning            |
| -------- | ------------------ |
| `&lt;`   | `<`                |
| `&gt;`   | `>`                |
| `&amp;`  | `&`                |
| `&nbsp;` | Non-breaking space |



### ✅ 148. **How do you escape characters in HTML?**

Use **entities** to prevent HTML parsing:

* `<` → `&lt;`
* `>` → `&gt;`
* `&` → `&amp;`
* `"` → `&quot;`
* `'` → `&apos;`



### ✅ 149. **What is the difference between `&nbsp;` and a regular space?**

| Character | Behavior                               |
| --------- | -------------------------------------- |
| Space     | Can collapse or break in lines         |
| `&nbsp;`  | Non-breaking space (won’t break lines) |

Example:

```html
<p>Hello&nbsp;World</p>
```



### ✅ 150 **What is the use of `&lt;`, `&gt;`, `&amp;`?**

These are **HTML entities** to display symbols:

* `&lt;` = `<` (less than)
* `&gt;` = `>` (greater than)
* `&amp;` = `&` (ampersand)

They are useful when you need to **display code** or **avoid parsing** by the browser.



