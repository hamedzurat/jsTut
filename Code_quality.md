# Code quality

.

## debugger

<https://javascript.info/debugging-chrome>

> use **debugger;** for triggering bowser debugger.


## Coding Style

<https://javascript.info/coding-style>


### syntax 

<https://javascript.info/coding-style#syntax>

#### curly braces

<https://javascript.info/coding-style#curly-braces>

#### line length

<https://javascript.info/coding-style#line-length>

#### nesting levels

<https://javascript.info/coding-style#nesting-levels>

### function placement

> there is no rules for this shit

### Style Guides

* <https://google.github.io/styleguide/jsguide.html>
* <https://github.com/rwaldron/idiomatic.js>
* <https://standardjs.com/>

### Automated Linters

<https://javascript.info/coding-style#automated-linters>

> inters are tools that can automatically check the style of your code and make improving suggestions.

* <https://eslint.org/>


## Comments

<https://javascript.info/comments>

> use jsDoc
>
> * <https://en.wikipedia.org/wiki/JSDoc>
> * <https://jsdoc.app/>

> replace a code piece with a *function*,

> camelcased *function* and *varible*

> comment on top of function about *usage*, *parameters*, *returned value*.

## Ninja code

<https://javascript.info/ninja-code>

> Many try to follow ninja paths. Few succeed. so..

> **dont use it**

## testing code with Mocha

<https://javascript.info/testing-mocha>

[*mocha*](https://mochajs.org)

> **its very important**

### The development flow

> * An initial spec is written, with tests for the most basic functionality.
> * An initial implementation is created.
> To check whether it works, we run the testing framework Mocha (more details soon) that runs the spec. While the functionality is not complete, errors are displayed. We make corrections until everything works.
> * Now we have a working initial implementation with tests.
> * We add more use cases to the spec, probably not yet supported by the implementations. Tests start to fail.
> * Go to 3, update the implementation till tests give no errors.
> * Repeat steps 3-6 till the functionality is ready.

> testing function 
>
> * <https://www.chaijs.com/api/assert/>

## Polyfills

<https://javascript.info/polyfills>

### Babel

> Babel is a transpiler.
> It rewrites modern JavaScript code into the previous standard.

> use bable because some browser might broke if we use modern fetures

EOF.
