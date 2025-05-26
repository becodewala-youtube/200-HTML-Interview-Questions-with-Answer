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



