# Objects
### What is an object?
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names

If a variable is part of an object, it is called a property. Properties tell us about the object.

If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object.

Creating objects using literal naotation is the easiest and most popular way to create objects

## The Document Object Model (DOM).
The DOM specifies the way in which the browser should structure this model using a DOM tree. stored in the browsers' memory

The DOM tree is model of a webpage
As a browser loads a web page, it creates a model of that page. The model is called a DOM tree , and it is stored in the browsers’ memory.
It consists of four main types of nodes.
Each node is an object with methods and properties.
Types of Nodes:
* the Document NODE
* ELEMENT NODES
* ATTRIBUTE NODES
* TEXT NODES
### Caching Dom Queries
Methods that find elements in the DOM tree are called DOM queries. When you need to work with an element more than once, you should use a variable to store the result of this query
When people talk about storing elements in variables, they are really storing the location of the element(s) within the DOM tree in a variable. The properties and methods of that element node work on the variable.