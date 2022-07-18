# Class 6

## Problem Domain, Objects, and the DOM

### Objects

#### How would you describe an object to a non-technical friend you grew up with?

An object is a collection of related data and functionality. You can think of them like any other "object" in the physical world. For example, a house is an object. It has a foundation, floor, walls, rooms and a roof. All of these can be defined with metrics like square footage and color. You can even use the same properties to describe different houses but with different values for each property.

#### What are some advantages to creating object literals?

Using object literals is more efficient when you want to transfer a series of structured and related data. They are also easier to work with when you want to identify specific data points by name.

#### How do objects differ from arrays?

Objects use the value's property name to identify that value as opposed to arrays that use the value's index within the array.

#### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

You would need to use bracket notation if an object property name is defined at runtime.

#### Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

```javascript
  const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
      console.log(`${this.name} is ${this.age*7} in human years`);
    }
  }
```

In the code above, `this` refers to the current object the code is being written inside of. Using `this` enables you to use the same method definition for every object that is created.

### The DOM

#### What is the DOM?

The Document Object Model (DOM) is the data representation of the objects that make up the structure and content of a web page. It is a programming interface that allows programs to change the structure, style and content of a web document.

#### Briefly describe the relationship between the DOM and JavaScript

The DOM is a collection of objects which allow JavaScript to be able to recognize and manipulate elements within a document. If the DOM was not made up of object, JavaScript would have no notion of what a web page or HTML document is. However, the DOM is not specific to JavaScript and can be be implemented for any programming language.

## Things I want to know more about

[Home](README.md)
