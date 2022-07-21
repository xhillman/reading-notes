# Class 9

## Forms and JS Events

### HTML Forms

#### Why are forms so important in web development?

Forms are one of the main ways users interact with websites and applications. They allow user to enter data which is then sent to a server for processing or storage, or used to dynamically update the frontend interface in some way.

#### When designing a form, what are some key things to keep in mind when it comes to user experience?

When designing a form, it's important to keep in mind the right set of data you are asking the user for and the size of the form. It's key to keep the form simple and ask only for the data you need.

#### List 5 form elements and explain their importance

- The `<form>` element is used to formally define a form. It is a container element specifically for forms.
- The `<label>` element is used to define a label for an HTML form widget. It is especially useful in terms of accessibility.
- The `<input>` element is where the user provides the requested data.
- The `<textarea>` element is used for multi-line text input.
- The `<button>` element is used to invoke some sort of action by the program. Typically submitting the form data.

### JS Events

#### How would you describe events to a non-technical friend?

An event is something that happens within the program that the program can then react to and perform some other function based on the event.

#### When using the `addEventListener()` method, what 2 arguments will you need to provide?

`addEventListener` takes in the name of the event and a function to handle that event.

#### Describe the event object. Why is the target within the event object useful?

The event object is a parameter that can be automatically passed to the event handler to provide extra features or information. The target within the event object is useful because it allows the event listener to listen to events on itself.

#### What is the difference between event bubbling and event capturing?

Event capturing is when the browser check to see if an elements outermost ancestor has an event handler on it and runs it if so. Then it moves on to the next outer element and does the same thing. Being the exact opposite, event bubbling is when nested elements all have event handlers placed on them causing all events to occur when the innermost child element is clicked.

## Things I want to know more about

[Home](README.md)
