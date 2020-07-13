# javascript note

.

## script tag

<https://www.w3schools.com/tags/tag_script.asp>
<https://javascript.info/hello-world#summary>

> A single script tag can’t have both the 'src' attribute and code inside.

## `;`

<https://javascript.info/structure#semicolon>

> doesnt matters in javascript. before compiling it will remove all 'newline'

> but error can occure so using ; is good

## comment

<https://javascript.info/structure#code-comments>

> comment in JS is like C/C++

> // This comment occupies a line of its own

> /*An example with two messages.
> This is a multiline comment.
> */  

## use strict

<https://javascript.info/strict-mode>

> use "use strict;" in forst of file to use modern JS

> dont use it

## Variables

<https://javascript.info/variables#a-variable>

> To create a variable in JavaScript, use the 'let' keyword.

.
<https://javascript.info/variables#variable-naming>
> The name must contain only letters, digits, or the symbols '$' and '_'.The first character must not be a digit.

> Variables named 'apple' and 'AppLE' are two different variables.

.
<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Keywords>
> Reserved names cant be used

> you can make varible without 'let' but you should not do it

.

## Constants

<https://javascript.info/variables#constants>

> To declare a constant (unchanging) variable, use 'const' instead of 'let'

<https://javascript.info/variables#uppercase-constants>

> There is a widespread practice to use constants as aliases for difficult-to-remember values that are known prior to execution.

## Data types

<https://javascript.info/types>

[There are 8 basic data types in JavaScript.](https://javascript.info/types#summary)

* **number** for numbers of any kind: integer or floating-point, integers are limited by ±253.
* **bigint** is for integer numbers of arbitrary length.
* **string** for strings. A string may have zero or more characters, there’s no separate single-character type.
* **boolean** for true/false.
* **null** for unknown values – a standalone type that has a single value null.
* **undefined** for unassigned values – a standalone type that has a single value undefined.
* **object** for more complex data structures.
* **symbol** for unique identifiers.

> JS is dynamically typed. so, you can store *string* in var then store a *int*

> there are so-called “special numeric values” which also belong to this data type: Infinity, -Infinity and NaN.

>In JavaScript, the “number” type cannot represent integer values larger than (253-1) (that’s 9007199254740991), or less than -(-253-1) for negatives.

### bigint

>A BigInt value is created by appending n to the end of an integer

### strings

>In JavaScript, there are 3 types of quotes.

    1. Double quotes: "Hello".
    2. Single quotes: 'Hello'.
    3. Backticks: `Hello`.

>Double and single quotes are “simple” quotes. There’s practically no difference between them in JavaScript.

>Backticks are “extended functionality” quotes. They allow us to embed variables and expressions into a string by wrapping them in ${…}

```javascript
let name = "John";

// embed a variable
alert( `Hello, ${name}!` );
```

> useing backtic is much better idea

.

> **typeof var** will give info about var

## Interaction

<https://javascript.info/alert-prompt-confirm>

>The mini-window with the message is called a modal window. The word “modal” means that the visitor can’t interact with the rest of the page, press other buttons, etc, until they have dealt with the window.

### alert

> This one we’ve seen already. It shows a message and waits for the user to presses *OK*.

### prompt

<https://javascript.info/alert-prompt-confirm#prompt>

>The function prompt accepts two arguments
>
> * **title** : The text to show the visitor
> * **default** : An optional second parameter, the initial value for the input field

### confirm

>The function confirm shows a modal window with a question and two buttons: *OK* and *Cancel*.

>The result is *true* if OK is pressed and *false* otherwise

## Type Conversions

<https://javascript.info/type-conversions>

### String Conversion

>call the **String(value)** function to convert a value to a string

>String conversion is mostly obvious. A false becomes "false", null becomes "null", etc.

### Numeric Conversion

>use the **Number(value)** function to explicitly convert a value to a number

>If the string is not a valid number, the result of such a conversion is NaN. For instance

### Boolean Conversion

>call to **Boolean(value)**

>Values that are intuitively “empty”, like 0, an empty string, null, undefined, and NaN, become **false**. 
>Other values become **true**

## Basic operators, maths

<https://javascript.info/operators>

### math operation

* Addition `+`
* Subtraction `-`
* Multiplication `*`
* Division `/`
* Remainder `%`
* Exponentiation `**`

### String operataion

<https://javascript.info/operators#string-concatenation-with-binary>

### Assignment

<https://javascript.info/operators#assignment>

### Bitwise operators

<https://javascript.info/operators#bitwise-operators>

* AND ( & )
* OR ( | )
* XOR ( ^ )
* NOT ( ~ )
* LEFT SHIFT ( << )
* RIGHT SHIFT ( >> )
* ZERO-FILL RIGHT SHIFT ( >>> )

### Comma

<https://javascript.info/operators#comma>

> The comma operator allows us to evaluate several expressions, dividing them with a comma `,`. Each of them is evaluated but only the result of the last one is returned.

## Comparisons

<https://javascript.info/comparison>

[String comparison](https://javascript.info/comparison#string-comparison)

[Comparison of different types](https://javascript.info/comparison#comparison-of-different-types)

> When comparing values of different types, JavaScript converts the values to numbers.

### if-else

<https://javascript.info/ifelse>

### Logical operators

<https://javascript.info/logical-operators>

### Nullish coalescing operator '??'

<https://javascript.info/nullish-coalescing-operator>

> The nullish coalescing operator ?? provides a short syntax for selecting a first “defined” variable from the list.

> The result of a ?? b is:
>
> * a if it’s not null or undefined,
> * b, otherwise.
>.

### switch

<https://javascript.info/switch>

## loops

<https://javascript.info/while-for>

## Functions

<https://javascript.info/function-basics>

> use `function` keyword before defining function

> A function can access an outer variable.
> ( like global var in c/cpp )

> The function has full access to the outer variable. It can modify it as well.

> If a parameter is not provided, then its value becomes    `undefined`

> if we pass a variable to the function and if the function changes value then the change is not seen outside, because a function always gets a copy of the value

> no one give **fuck** about arg var or return var type

> Never add a newline between `return` and the value

> A function with an empty `return` or without it returns `undefined`

### Function expressions

<https://javascript.info/function-expressions>

```javascript
let sayHi = function() {
  alert( "Hello" );
};
```

> Here, the function is created and assigned to the variable explicitly, like any other value. No matter how the function is defined, it’s just a value stored in the variable `sayHi`

> **semicolon** at the end

> function as a argument

>

## Arrow functions

<https://javascript.info/arrow-functions-basics>






.
.

.
.
.
.
.


.

..
.
.
.
.
.
.

.
.
.
.
.
.

..
.

.

.


