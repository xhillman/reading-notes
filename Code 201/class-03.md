# Class 3

## HTML Lists, Control Flow with JS, and the CSS Box Model

### HTML Lists

#### When should you use an unordered list in your HTML document?

Unordered lists are useful when grouping items and the order of the list is meaningless.

#### How do you change the bullet style of unordered list items?

To change the bullet style of an unordered list, you would use the `type` attribute.

#### When should you use an ordered list vs an unorder list in your HTML document?

If changing the order of the list items changes the meaning of the information being presented, you should use an ordered list. If the order of the list items does not change the meaning of the information, an unordered list would be appropriate.

#### Describe two ways you can change the numbers on list items provided by an ordered list?

You could use the `start` attribute to start the list at a specific number or change the `type` attribute to change the numbers to letters or Roman numerals. You could also use the `reversed` attribute to reverse the order of the numbers.

### CSS Box Model

#### Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

**Margin**: The front gate guard. Margin creates space around the castle and makes sure the border doesn't get overrun by outside content.

**Padding**: Padding is the content's personal guard. Should the borders start to close in on the content, Padding helps to regulate the space between.

#### List and describe the four parts of an HTML elements box as referred to by the `box model`

> - Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
>
>- Padding box: The padding sits around the content as white space; size it using padding and related properties.
>
>- Border box: The border box wraps the content and any padding; size it using border and related properties.
>
>- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.
>

Reference: [The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) from mdn web docs_.

### JavaScript

#### What `data types` can you store inside of an `Array`?

- Strings
- Numbers
- Objects
- Other Arrays

#### Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```javascript
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

Yes, the `people` array is valid. You can access the values stored by referencing the array name followed by the index of the first array and the index of the item you are trying to access in the internal array.

`people[0][2]` would give you the value `'librarian'`

#### List five shorthand operators for assignment in javascript and describe what they do

- Addition assignment `+=` adds the value of the right operand to the value a variable already holds. `x += 5;` is the same as `x = x + 5;`
- Subtraction assignment `-=` subtracts the value of the right operand from the value a variable already holds. `x -= 5;` is the same as `x = x - 5;`
- Multiplication assignment `*=` multiplies the value of the right operand by the value a variable already holds. `x *= 5;` is the same as `x = x * 5;`
- Division assignment `/=` divides the value of the right operand by the value a variable already holds. `x /= 5;` is the same as `x = x / 5;`
- Remainder assignment `%=` divides a variable by the right operand and assigns the remainder to the variable `x %= 5;` is the same as `x = x % 5;`

#### Read the code below and evaluate the last `expression` and explain what the result would be and why

```javascript
  let a = 10;
  let b = 'dog';
  let c = false;

  // evaluate this
  (a + c) + b;
 ```

 The expression would evaluate to `10dog` because `false` evaluates to `0` in Javascript so `10` would be concatenated with `'dog'` as the expression continues.

#### Describe a real world example of when a conditional statement should be used in a JavaScript program

An `if...else` statement could be used in a script that determines whether you should buy something on Amazon.

```javascript
  if (price of item <= $20) {
    buyItem();
  } else {
    waitForPriceReduction();
  };
```

#### Give an example of when a `loop` is useful in JavaScript

Loops are useful when you need to perform a repetitive task. For example, if you needed to find half of all numbers in an array, you could use a loop to go through each item instead of doing it manually.

## Things I want to know more about
