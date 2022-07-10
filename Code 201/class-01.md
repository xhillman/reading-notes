# Class 1

Understanding how the web works and the basic building blocks of a web page are the foundation for learning software development.

## A poem about HTTPS

### How are HTML, CSS and JS files "parsed" in the browser?

- The browser parses the HTML file first, and that leads to the browser recognizing any `<link>` element references to external CSS stylesheets and any `<script>` element references to scripts.

- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.

- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

Reference [*How the web works*](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works) from mdn web docs_.

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

### Describe the Anatomy of an HTMl element.

An HTML element begins with an opening tag 