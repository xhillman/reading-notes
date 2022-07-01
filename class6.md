# Dynamic web pages with Javascript

## What is Javascript?

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions.

It's a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

The standards for JavaScript are the ECMAScript Language Specification (ECMA-262) and the ECMAScript Internationalization API specification (ECMA-402). The JavaScript documentation throughout MDN is based on the latest draft versions of ECMA-262 and ECMA-402.

Javascript and Java are **NOT** the same language.

### What are variables?

Variables are containers for storing data (data values).

In this example, `x`, `y`, and `z`, are variables, declared with the `var` keyword:

```javascript
    var x = 5;

    var y = 6;

    var z = x + y;
```

In this example, `x`, `y`, and `z`, are variables, declared with the `let` keyword:

```javascript
    let x = 5;

    let y = 6;

    let z = x + y;
```

In this example, `x`, `y`, and `z`, are undeclared variables:

```javascript
    x = 5;

    y = 6;

    z = x + y;
```

Always declare JavaScript variables with `var`,`let`, or `const`.

The `var` keyword is used in all JavaScript code from 1995 to 2015.

The `let` and `const` keywords were added to JavaScript in 2015.

If you want your code to run in older browser, you must use `var`. If you want a general rule: **always declare variables with `const`**. If you think the value of the variable can change, use `let`.

In this example, price1, price2, and total, are variables:

```javascript
    const price1 = 5;

    const price2 = 6;

    let total = price1 + price2;
```

The two variables `price1` and `price2` are declared with the `const` keyword. These are constant values and cannot be changed. The variable `total` is declared with the `let` keyword. This is a value that can be changed.

All JavaScript **variables** must be **identified** with **unique names**. These unique names are called **identifiers**.

The general rules for constructing names for variables (unique identifiers) are:

- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter
- Names can also begin with $ and _
- Names are case sensitive (y and Y are different variables)
- Reserved words (like JavaScript keywords) cannot be used as names

`=` is an "assignment" operator and does not mean the same thing as "equal to".

Text (or strings) and numbers are examples of data types.

In computer programs, variables are often declared without a value. The value can be something that has to be calculated, or something that will be provided later, like user input.

A variable declared without a value will have the value `undefined`.

The `$` and `_` symbol is treated as a letters in Javascript.

## What is a computer?

A computer is a machine that can take input from various sources, store that input in memory, process the information from memory and output the information that is processed.

The output can include things such as:

- Text
- Photos
- Videos
- Games
- VR
- Signals to robots

Inside a computer are electric wires and circuits that carry all the information in the computer.

Information in a computer is represented by bits which is an on/off state determined by whether electricity is flowing through a wire, creating a signal. Each wire can either be on or off, represented by a 1 or 0. The more wires, the more bit combinations that are possible and the more complex the information that can be stored.

This combination of 1s and 0s and their decimal system equivalent is called the binary system. Any number can be represented by the binary system as long as their are enough wires available.

Text, images and sounds can also be represented by numbers using the binary system.

Every input or output of a computer is a type of information, which can be represented by on or off electrical signals (1s and 0s).

A CPU is the master chip that controls all the other parts of the computer.

The operating system is the master program that manages how software gets to use the hardware of the computer.

- [Home](README.md)
- [Class 1 Markdown](class1.md)
- [Class 2 The Coder's Computer](class2.md)
- [Class 3 Git & GitHub](class3.md)
- [Class 4 Wireframes and HTML](class4.md)
- [Class 5 CSS](class5.md)
- [Class 6 Javascript Basics](class6.md)
- [Class 7 Programming with Javascript](class7.md)
- [Class 8 Operators and Loops](class8.md)
