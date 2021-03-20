# Problem Domain, Objects, and the DOM


Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,
variables and functions take on new names.

As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.

- THE DOCUMENT NODE
- ELEMENT NODES
- ATTRIBUTE NODES
- TEXT NODES

Accessing and updating the DOM tree involves two steps:

1: Locate the node that represents the element you want to work with.

2: Use its text content, child elements, and attributes.

The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element,
it is actually working with a node that represents that element.

When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.
