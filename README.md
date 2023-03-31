# DOM-Array-Methods
DOM Array Methods
Welcome to the DOM Array Methods project, a powerful and easy-to-use library for working with HTML DOM elements in a more array-like fashion. This library provides a set of methods that simplify the process of selecting, manipulating, and traversing DOM elements while making your code more readable and maintainable.

Visit the live demo and documentation here: https://sonnymay.github.io/DOM-Array-Methods/

Features
Lightweight and easy to integrate
Chainable methods for seamless DOM manipulation
Compatible with modern browsers
Intuitive and familiar syntax for JavaScript developers
Installation
To install the DOM Array Methods library, include the following script tag in your HTML file:

html
Copy code
<script src="https://sonnymay.github.io/DOM-Array-Methods/dist/dom-array-methods.min.js"></script>
Usage
Using the DOM Array Methods library is as simple as selecting an element or a group of elements and applying the desired method.

Basic example
javascript
Copy code
// Select all paragraphs and hide them
dom(".paragraph").hide();

// Select a single element by ID and change its text content
dom("#myElement").text("Hello, world!");
Chaining methods
javascript
Copy code
// Select all list items, add a class, and change the text color
dom("li")
  .addClass("myClass")
  .css("color", "red");
Available Methods
Here is a list of the most common methods provided by the DOM Array Methods library. Please visit the documentation for a complete list and detailed explanations.

dom(selector): Select elements
each(callback): Iterate through elements
addClass(className): Add a class to elements
removeClass(className): Remove a class from elements
toggleClass(className): Toggle a class on elements
hasClass(className): Check if an element has a class
attr(attribute, value): Get or set attributes
removeAttr(attribute): Remove attributes
css(property, value): Get or set CSS properties
text(content): Get or set text content
html(content): Get or set HTML content
val(value): Get or set the value of form elements
append(content): Append content to elements
prepend(content): Prepend content to elements
before(content): Insert content before elements
after(content): Insert content after elements
remove(): Remove elements from the DOM
empty(): Remove all child nodes from elements
parent(): Get the parent element
children(): Get the child elements
siblings(): Get the sibling elements
show(): Show elements
hide(): Hide elements
toggle(): Toggle the visibility of elements
on(event, callback): Add an event listener
off(event): Remove an event listener
Contributing
Contributions are welcome! Please read our contributing guidelines before submitting a pull request or opening an issue.

License
This project is licensed under the MIT License.
