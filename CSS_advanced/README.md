<h1 align="center">Advanced CSS</h1>

 ## CSS fundamentals
 ### Overview
CSS (Cascading Style Sheets) are used to style HTML.

CSS works by:
* selecting an HTML element
* choosing a property to alter
* applying a certain value

### Syntax
element-selector {
 one-style-property: value;
 another-style-property: value;
}

A property + value is known as a “declaration”. Like this: text-align: center;

In general, and for readability purposes, we tend to put each declaration on separate lines like the example above. Some people argue that is better to put everything (element, property and value) in one line (when it has a single declaration), but you might need to add more declarations in the future. Also, placing each declaration on dedicated lines makes the code a lot easier to read and follow.