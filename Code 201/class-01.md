# Class 1

## Foundations of a Web Page

Understanding how the web works and the basic building blocks of a web page are the foundation for learning software development.

### Ode to HTTP

From DNS server, we find true address.
To server, from browser is sent a request.

A copy is needed, to client we show.
200 is yes, 404 means no.

Bit by bit, data packets are sent.
The browser assembles, it knew what we meant.

### How are HTML, CSS and JS files "parsed" in the browser?

> - The browser parses the HTML file first, and that leads to the browser recognizing any `<link>` element references to external CSS stylesheets and any `<script>` element references to scripts.
>
> - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
>
> - The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
>
> - As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

Reference: [*How the web works*](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) from mdn web docs_.

### How can you find images to add to a website?

You can find images to add to a website by going to [Google Images](https://www.google.com/imghp?hl=en&ogbl) and searching for the desired image. Once you've found the picture you're looking for, you can right-click, *Save Image As...* and save it somewhere safe (like an img folder within your project).

### How do you create a `String` vs a `Number` in JavaScript?

If you want to create a variable with a `string` value, you would use the `let` keyword, followed by the variable name and assignment operator with the assigned value wrapped in quotation marks:

 `let x = "text"` or `let x = "5"`

To create a variable with a `number` value, you would do the same as above but simply omit the quotations marks (value must be numerical):

`let x = 5`

### What is a `Variable` and why are they important in JavaScript?

A variable is a container that stores values. They can be created using the `let` and `const` keywords followed by the name you give them.

`let myVariable;`

Variables are case sensitive. `myVariable` and `myvariable` are **NOT** the same thing.

Variables are important in Javascript because they allow you to make web pages dynamic.

### What is an HTML attribute?

Attributes contain extra information about HTML elemenets that won't be included in the content.

`<p class="editor-note">I am Xavier Hillman</p>`

In the example above, the `class` attribute is an identifying name used to target the element with style information.

### Describe the Anatomy of an HTML element

`<p>A paragraph element</p>`

An HTML element begins with an **opening tag**, which is the name of the element (p for paragraph above), wrapped in angled brackets: `<p>`
Next comes the **content**. `A paragraph element` in the example above.
Finally, there is the **closing tag** which is the same as the opening tag except there is a backslash before the element name: `</p>`

### What is the Difference between `<article>` and `<section>` element tags?

> `<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
> `<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries).

Reference: [*Document and website structure*](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#html_for_structuring_content) from mdn web docs_.

### What elements does a “typical” website include?

Typical websites contain the following elements:

- `<!DOCTYPE html>`
- `<html></html>`
- `<head></head>`
- `<meta charset="utf-8">`
- `<title></title>`
- `<body></body>`

### How does metadata influence Search Engine Optimization?

Including metadata such as the author and a description of the content with specific related keywords has the potential to help a web page appear higher in search engine relevent searches.

### How is the `<meta>` HTML tag used when specifying metadata?

The `<meta>` tag is a self-closing element that can be used to specify additional information about a page such as the character encoding (`<meta charset="utf-8">`), the page's author (`<meta name="author" content="Xavier Hillman">`) and page description (`<meta name="description" content="This is my reading notes page">`).

### What is the first step to designing a website?

The first step to designing a website is project ideation. It helps to ask the following questions:

- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

### What is the most important question to answer when designing a website?

**What exactly do I want to accomplish?**

### Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

The `<h1>` element actually gives the text it wraps around the role of "top level heading" whereas the `<span>` element does not. It simply has the ability to make it's contents *look* like a top level heading.

### What are the benefits of using semantic tags in our HTML?

> - Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
> - Screen readers can use it as a signpost to help visually impaired users navigate a page
> - Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
> - Suggests to the developer the type of data that will be populated
> - Semantic naming mirrors proper custom element/component naming

Reference: [*Semantics*](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) from mdn web docs_.

### Describe 2 things that require JavaScript in the browser?

Dynamically updating text requires Javascript in the browser because it relies on Javascript features such as `.addEventListener` and `.querySelector` to know when users are trying to interact with the page. Interacting with **Application Programming Interfaces (APIs)** also requires Javascript to access information from outside sources.

### How can you add JavaScript to an HTML document?

**Internal Javascript**: within a `<script>` tag directly in the HTML document.

```javascript
    <script>

        // JavaScript goes here

    </script>
```

**External Javascript**: within a seperate file in the same directory.

```javascript
    <script src="script.js" defer></script>
```

**Inline Javascript**: referenced directly within the HTML file.

```javascript
    <button onclick="createParagraph()">Click me!</button>
```

## Things I want to know more about

[Home](README.md)
