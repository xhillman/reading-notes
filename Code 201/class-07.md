# Class 7

## Object-Oriented Programming, HTML Tables

### Domain Modeling

#### Explain why we need domain modeling

>A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

Reference: [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling) from Code Fellows.

### HTML Table Basics

#### Why should tables not be used for page layouts?

1. They reduce accessibility because they do not follow the same semantic rules as a standard HTML file as a whole.
2. They make HTML files harder to read, write, maintain and debug because they involve more complex markup than the accepted layout techniques.
3. They decrease repsonsiveness because tables do not follow the same sizing rules.

#### List and describe 3 different semantic HTML elements used in an HTML `<table>`

- The `<table>` tag is used to enclose everything that will go inside the table.
- The `<td>` tag is used to create a cell. Each `<td>` (table data) tag creates a single sell and together they make up a row of a table.
- The `<tr>` (table row) is used to end the growth of a row and start putting subsequent `<td>` tags into the next row.

>```html
>  <table>
>    <tr>
>      <td>Hi, I'm your first cell.</td>
>      <td>I'm your second cell.</td>
>      <td>I'm your third cell.</td>
>      <td>I'm your fourth cell.</td>
>    </tr>
>  </table>
>```

### Introducing Constructors

#### What is a constructor and what are some advantages to using it?

A constructor is a function called using the `new` keyword and is useful for creating multiple related objects because they acts like a template. The new objects are given the same properties as the contructor but can then be given new properties individually as needed.

#### How does the term `this` differ when used in an object literal versus when used in a constructor?

When used in an object literal, `this` refers to the current object after it has already been created. In a constructor, `this` referes the current object as it is being created.

### Object Prototypes Using A Constructor

#### Explain prototypes and inheritance via an analogy from your previous work experience

In my time as a real estate agent, we used the same form every time to submit offers for our clients. There were sections with information about our team and brokerage that needed to be filled out. The document with our team information filled in would be considered the prototype with those values preset. Each time we submitted a new offer, the form would inherit the information about our team and the rest of the form would be assigned values for that specific house.

## Things I want to know more about

[Home](README.md)
