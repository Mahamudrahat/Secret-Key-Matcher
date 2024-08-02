#Question and Answer:
##1.What is ES6 and what are the new features introduced in ES6?
#Answer:ES6 (ECMAScript 2015) is the sixth edition of the ECMAScript language specification, standardized by ECMA International. It introduced several new features to JavaScript, aiming to make the language more powerful and easier to work with. Some of the key features include:

#let and const: Block-scoped variable declarations.
#Arrow Functions: A shorter syntax for writing functions and lexically binds the context.
#Template Literals: String literals allowing embedded expressions.
#Destructuring Assignment: A syntax for extracting values from arrays or objects into distinct variables.
#Default Parameters: Function parameters with default values.
#Rest and Spread Operators: Allowing functions to accept an indefinite number of arguments (rest) and expanding arrays (spread).
#Classes: A syntactical sugar over JavaScript’s existing prototype-based inheritance.
#Modules: Native support for modules to organize code into separate files.
#Promises: A way to handle asynchronous operations.
#Iterators and Generators: For creating iterable objects and controlling the iterator's execution.
#Map and Set: New collection types.
##2. What is Event Bubble and Event Delegation in JS?
#Answer: Event Bubbling: It is a type of event propagation where the event starts from the target element and then bubbles up to the parent elements in the hierarchy. For example, if a user clicks on a button inside a div, the click event will first be captured by the button and then bubble up to the div and other ancestors.
#Event Delegation: It is a technique to handle events efficiently by attaching a single event listener to a parent element instead of attaching multiple event listeners to individual child elements. The event listener on the parent element can manage events for its child elements, taking advantage of event bubbling. This is particularly useful when dealing with dynamic content.