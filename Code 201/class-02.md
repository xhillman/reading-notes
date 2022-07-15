# Class 2

## Basics of HTML, CSS and JS

### HTML

#### Why is it important to use semantic elements in our HTML?

Using semantics in our HTML allows us to give meaning to the content we are displaying on the web page. It allows us to inherently know what the function of the element is. Semantic elements are also helpful in regards to search engine optimization and accessibility (screen readers).

#### How many levels of headings are there in HTML?

There are six heading levels in HTML.

#### What are some uses for the `<sup>` and `<sub>` elements?

Uses for the `<sup>` and `<sub>` elements include instances such as:

- Dates
- Chemical Formulae
- Mathematical equations

```html
  <p>My birthday is on the 5<sup>th</sup> of September, 1994.</p>
  <p>Caffeine's chemical formula is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.</p>
  <p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>
```

#### When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

To provide the full expansion of the term when using a `<abbr>` element, you must us the `title` attrinute within the opening tag.

`<p><abbr title="National Aeronautics and Space Administration">NASA</abbr> does some pretty cool work in space.<p>`

### CSS

#### What are ways we can apply CSS to our HTML?

**External stylesheets**: CSS in a seperate file with a `.css` extension within the `<link>` HTML element.

`<link rel="stylesheet" href="styles.css">`

**Internal stylesheets**: resides within the HTML document inside a `<style>` element.

```css
  <style>
        h1 {
          color: blue;
          background-color: yellow;
          border: 1px solid black;
        }

        p {
          color: red;
        }
  </style>
```

**Inline styles**: CSS declarations that affect a single HTML element, contained within the `style` attribute of that element.

`<h1 style="color: blue;background-color: yellow;border: 1px solid black;">Hello World!</h1>`

#### Why should we avoid using inline styles?

It is the least efficient implementation of CSS for maintenance and it makes everything within the HTML file harder to read and understand.

> ```css
>  h2 {
>      color: black;
>      padding: 5px;
>    }
>```

What is representing the selector above? `h2`
Which components above are the CSS declarations? `color: black;` and `padding: 5px;`
Which components above are considered properties? `color` and `padding`

### JavaScript

#### What data type is a sequence of text enclosed in single quote marks?

A string.

`let myName = 'Xavier';`

#### List 4 types of JavaScript operators

- Assignment operators
- Arithmetic operators
- Comparison operators
- Relational operators

#### Describe a real world problem you could solve with a function

If there was a function `signMyName()` in the real world, you would never have to physically write out your signature again.

#### An if statement checks a __ and if it evaluates to ___, then the code block will execute

An if statement checks an **expression** and if it evaluates to **true**, then the code block will execute.

#### What is the use of an else if?

`else if` allows for more than two outcomes of an `if...else` conditional.

#### List 3 different types of comparison operators

- less than `<`
- greater than `>`
- less than or equal `<=`

#### What is the difference between the logical operator && and ||?

`&&` stands for **and**: both expressions must evaluate to `true` to produce a `true` result.

`||` stands for **or**: at least one of the expressions must evaluate to `true` to produce a `true` result.

## Things I want to know more about

[Home](README.md)
