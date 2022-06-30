# Expressions, Operators and Loops

## Assignment operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

Assignment `x = f()` >  `x = f()`
Addition assignment `x += f()` > `x = x + f()`
Subtraction assignment `x -= f()` > `x = x - f()`
Multiplication assignment `x *= f()` > `x = x * f()`
Division assignment `x /= f()` > `x = x / f()`
Remainder assignment `x %= f()` > `x = x % f()`
Exponentiation assignment `x **= f()` > `x = x ** f()`
Left shift assignment `x <<= f()` > `x = x << f()`
Right shift assignment `x >>= f()` > `x = x >> f()`
Unsigned right shift assignment `x >>>= f()` > `x = x >>> f()`
Bitwise AND assignment `x &= f()` > `x = x & f()`
Bitwise XOR assignment `x ^= f()` > `x = x ^ f()`
Bitwise OR assignment `x |= f()` > `x = x | f()`
Logical AND assignment `x &&= f()` > `x && (x = f())`
Logical OR assignment `x ||= f()` > `x || (x = f())`
Logical nullish assignment `x ??= f()` > `x ?? (x = f())`

## Comparison operators

A comparison operator compares two values and returns a logical value (`true` or `false`) based on whether the comparison is true. The values can be numerical, string, logical, or object values.

Equal (`==`) returns `true` if the operands are equal. `3 == var1` or `"3" == var1`
Not equal (`!=`) returns `true` if the operands are not equal. `var1 != 4` or `var2 != "3"`
Strict equal (`===`) returns `true` if the operands are equal and of the same type. See also Object.is and sameness in JS. `3 === var1`
Strict not equal (`!==`) returns `true` if the operands are of the same type but not equal, or are of different type. `var1 !== "3"` or `3 !== '3'`
Greater than (`>`) returns `true` if the left operand is greater than the right operand. `var2 > var1` or `"12" > 2`
Greater than or equal (`>=`) returns `true` if the left operand is greater than or equal to the right operand. `var2 >= var1` or `var1 >= 3`
Less than (`<`) returns `true` if the left operand is less than the right operand. `var1 < var2` or `"2" < 12`
Less than or equal (<=) returns `true` if the left operand is less than or equal to the right operand. `var1 <= var2` or `var2 <= 5`

## Loops and iteration

Loops offer a quick and easy way to do something repeatedly. You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another.

### For statements

A for loop repeats until a specified condition evaluates to false.

```javascript
    for ([initialExpression]; [conditionExpression]; [incrementExpression])
    statement
```

When a for loop executes, the following occurs:

1. The initializing expression `initialExpression`, if any, is executed. This expression can also declare variables.

2. The `conditionExpression` expression is evaluated. If the value of `conditionExpression` is true, the loop statements execute. Otherwise, the `for` loop terminates. (If the `conditionExpression` expression is omitted entirely, the condition is assumed to be true.)

3. The `statement` executes. To execute multiple statements, use a block statement (`{ ... }`) to group those statements.

4. If present, the update expression `incrementExpression` is executed.

5. Control returns to Step 2.

Use the `break` statement to terminate a loop.

The `continue` statement can be used to restart a `while`, `do-while`, `for`, or `label` statement.

### While statements

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

```javascript
    while (condition)
    statement
```

If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop.

The condition test occurs *before* `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and the `condition` is tested again. If the condition returns `false`, execution stops, and control is passed to the statement following `while`.

[Home](README.md)