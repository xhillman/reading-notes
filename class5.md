# Intro to CSS

CSS, or Cascading Style Sheets, is used to make webpages look better. It controls how the HTML elements on your page look.

CSS is a rule-based language. You define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

```html
    h1 {

        color: green;

        text-size: 5rem;

    }
```

In this example, the `h1` is the *selector* that determines which HTML element is being styled.

Inside the curly braces `{ }` we find the *declarations* which take the form of property-value pairs. We specify the property (`color` in the above example) before the colon, and we specify the value of the property after the colon (`green` in this example).

As seen in the above example, selectors can have more than one declaration applied to them.

For more information on text styling click [here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text)

## How to add CSS

### External CSS

With an external style sheet, you can change the look of an entire website by changing just one file. External styles are defined within the `<link>` element, inside the `<head>` section of an HTML page.

```html
    <head>

        <link rel="stylesheet" href="mystyle.css">

    </head>
```

External stylesheets can be written in any text editor and must be saved with a .css extension ex. mystyles.css

### Internal CSS

An internal style sheet may be used if one single HTML page has a unique style. Internal styles are defined within the `<style>` element, inside the `<head>` section of an HTML page.

```html
    <head>

        <style>
            body {

                background-color: linen;

            }

            h1 {

                color: maroon;

                margin-left: 40px;
            }

    </style>
```

### Inline CSS

An inline style may be used to apply a unique style for a single element. Inline styles are defined within the "style" attribute of the relevant element.

```html
    <body>

        <h1 style="color:blue; text-align:center;">This is a heading</h1>

        <p style="color:red;">This is a paragraph.</p>

    </body>
```

### Cascading Order

You can use more than one technique for applying CSS, however some techniques take precedents over others. The hierarchy is as follows:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

- [Home](README.md)
- [Class 1 Markdown](class1.md)
- [Class 2 The Coder's Computer](class2.md)
- [Class 3 Git & GitHub](class3.md)
- [Class 4 Wireframes and HTML](class4.md)
- [Class 5 CSS](class5.md)
- [Class 6 Javascript Basics](class6.md)
- [Class 7 Programming with Javascript](class7.md)
- [Class 8 Operators and Loops](class8.md)
