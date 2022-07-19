# Class 8

## CSS Layout

### Flexbox

#### Flexbox is designed for one-dimensional content. Explain what this means

Being designed for one-dimensional content means that flexbox is made to deal with layouts in a single direction (rows or columns). It is used to provide greater control over alignment and space distribution of items within a container.

#### Explain the difference between the main axis and cross axis

Flex items move as a group along the main axix, which is set by the `flex-direction` property. The cross axis runs opposite the main axis so if `flex-direction` is `row`, the cross axis would run along the column.

#### How can using certain properties of flexbox negatively impact accessibility?

When using `row-reverse` and `column-reverse`, you are only changing the visual order, not the logical order. You have to keep in mind that screen readers will read out content in the logical order, and the user will follow, which may not match the intended functionality.

#### What are some advantages of using flexbox over float?

With flexbox, you can easily achieve the following which are very difficult or impossible with float:

- Vertically centering a block of content inside its parent.
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

Reference: [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) from mdn web docs_.

#### How does this topic connect with your long term goals?

If I hope to gain the skills needed to build web apps of all kinds, flexbox will most definitely be required to learn. Not every concept for a web app will be able to fit into the same layout. Because of this, it is very important that I learn to manipulate the layout so that it is best suited for the task at hand.

## Things I want to know more about

[Home](README.md)
