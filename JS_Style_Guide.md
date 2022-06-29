# Javascript Style Guide

Nothing is set in stone here. These are style preferences, not religious dogmas.

## Consistency
A style guide is a set of rules that developers follow when writing their code to ensure consistency between developers.

## Readability
There’s may not be a problem in either of their approaches, but if you’ve got different developers writing code differently, your codebase will start to look a little bit unreadable. Also, new developers coming into the team won’t necessarily know which best approach to use.

## Predictability

## Efficiency

## Major Javascript Style Guides

[Airbnb JavaScript Style Guide](https://airbnb.io/javascript/)

[JavaScript Standard Style](https://standardjs.com/index.html)

[Idiomatic JavaScript](https://github.com/rwaldron/idiomatic.js/)

[Google Style Guide](https://google.github.io/styleguide/jsguide.html)

[jQuery JavaScript Style Guide](https://contribute.jquery.org/style-guide/js/)

[Dojo Style Guide](https://dojotoolkit.org/reference-guide/1.9/developer/styleguide.html)

[Node.js Style Guide](https://github.com/felixge/node-style-guide)

[Crockfords’s Coding Standards for JavaScript](http://javascript.crockford.com/code.html)

[NPM Style Guide](https://doc.codingdict.com/npm-ref/misc/coding-style.html)

[WordPress JavaScript Coding Standards](https://make.wordpress.org/core/handbook/coding-standards/javascript/)


In performance-critical code, performance considerations take precedance over these guidelines.

curly braces are written in “Egyptian” style with the opening brace on the same line as the corresponding keyword – not on a new line. There should also be a space before the opening bracket.
Use const for all of your references; avoid using var.
If you must reassign references, use let instead of var.
Use the literal syntax for object creation.

# Promises

Promises are used when the runtime of the function is unknown.

# Function Arguments

All function that take any arguments must accept an arguments object.  If the meaning of a single parameter is obvious, this can be accepted as well.
Functions with two parameters are to be used only in the rare circumstances where the meaning of the parameters is obvious.
Functions with three or more parameters are never to be used.
