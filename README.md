# Live Link:https://mahamudrahat.github.io/Secret-Key-Matcher/


# 1. What is ES6 and what are the new features introduced in ES6?

###### ES6 (ECMAScript 2015) is the sixth edition of the ECMAScript language specification, standardized by ECMA International. It introduced several new features to JavaScript, aiming to make the language more powerful and easier to work with. Some of the key features include:


#####	let and const: Block-scoped variable declarations.
#####	Arrow Functions: A shorter syntax for writing functions and lexically binds the context.
#####	Template Literals: String literals allowing embedded expressions.
#####	Destructuring Assignment: A syntax for extracting values from arrays or objects into distinct variables.
#####	Default Parameters: Function parameters with default values.
#####	Rest and Spread Operators: Allowing functions to accept an indefinite number of arguments (rest) and expanding arrays (spread).


# 2. What is Event Bubble and Event Delegation in JS?

 ##### Event Bubbling: It is a type of event propagation where the event starts from the target element and then bubbles up to the parent elements in the hierarchy. For example, if a user clicks on a button inside a div, the click event will first be captured by the button and then bubble up to the div and other ancestors.
##### Event Delegation: It is a technique to handle events efficiently by attaching a single event listener to a parent element instead of attaching multiple event listeners to individual child elements. The event listener on the parent element can manage events for its child elements, taking advantage of event bubbling. This is particularly useful when dealing with dynamic content.


# 3. What is the difference between localStorage, sessionStorage, and cookies?

##### 	localStorage: Window (accessible within the same origin).Lifetime: Data persists even after the browser is closed and reopened. Larger storage capacity (usually around 5-10MB per domain).Storing long-term data that doesn’t expire.
#####	sessionStorage:Window (accessible within the same origin). Data persists only for the duration of the page session (until the tab or window is closed).imilar capacity to localStorage but less commonly used.Storing temporary data that only needs to be available during the session.
 
#####	Cookies: Sent with every HTTP request to the server, accessible on the server and client side. Can be set to expire after a specific time or when the browser is closed.Smaller storage capacity (about 4KB per cookie). Storing small pieces of data that need to be sent to the server with each request (e.g., user authentication tokens).

# 4. In CSS what is the difference between display inline, display inline-block and display block?

#####	display: inline;
#####	Behavior: Elements do not start on a new line and only take up as much width as necessary.
#####	Box Model: Width and height cannot be set, only horizontal padding and margin are effective.
#####	display: inline-block;
#####	Behavior: Elements do not start on a new line but respect width and height settings.
#####	Box Model: Width, height, padding, and margin can be set and are respected.
#####	display: block;
#####	Behavior: Elements start on a new line and take up the full width available.
#####	Box Model: Width, height, padding, and margin can be set and are respected.


# 5. What are new features in CSS3?

##### CSS3 introduced a wide range of new features and improvements over the previous versions. Some of the notable features include:
#####	Flexbox: A layout mode for arranging elements in a predictable way for different screen sizes and devices.
#####	Grid Layout: A two-dimensional grid-based layout system.
#####	Media Queries: Allowing different styles for different devices and screen sizes.
#####	Animations and Transitions: For animating elements smoothly.
#####	Rounded Corners: Using the border-radius property.
#####	Box Shadows and Text Shadows: For adding shadows to elements and text.
#####	Gradients: Both linear and radial gradients.
#####	Custom Fonts: Using @font-face to include custom fonts.
#####	Multiple Backgrounds: Applying multiple background images to an element.
#####	Opacity: Setting the transparency level of an element.
#####	New Color Models: RGBA and HSLA colors.

