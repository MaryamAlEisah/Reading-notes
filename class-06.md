# JS Object Literals; The DOM & Problem Domain

 

## WHAT IS AN OBJECT? 

An **object** is represented as a collection of key-value pairs in Javascript. In an object, variables are known as **properties** of the
object; functions are known as **methods** of the object. 


### How we can create an *object* In JS ?
There are *5 methods* to create objects in JS:

1. Object Literal.
2. Using a new keyword with Object constructor.
3. Using a new keyword with a constructor function.
4. Object.create() method.
5. Classes.

### What is object literal notation?

The *object literal notation* is basically an array of key:value pairs, with a colon separating the keys and values, and a comma after every key:value pair, except for the last, just like a regular array. Values created with anonymous functions are methods of your *object*.

### How do you make an object literal?

**Object literals** are defined using the following syntax rules:
* A colon `:` separates property name`[1]` from value.
* A comma `,` separates each name-value pair from the next.
* A comma `,` after the last name-value pair is optional`[2]`


 ### Example:

 ![](https://image.slidesharecdn.com/oojs-1229037721986393-1/95/beginning-objectoriented-javascript-15-728.jpg)


## What is the DOM? 

**DOM** is (*Document Object Model* ) is a platform  that allows programs and scripts to dynamically access and update the content, structure, and style of a document." 

### The HTML DOM

With the **HTML DOM**, *JavaScript* can access and change all the elements of an HTML document.

The *HTML DOM model* is constructed as a tree of Objects:

 ![](https://www.w3schools.com/js/pic_htmltree.gif)

With the object model, JavaScript can create dynamic HTML:

* **JS** can change all the HTML elements & change all the HTML attributes.
* **JS** can change all the CSS styles. 
* **JS** can remove existing HTML elements and attributes & add new HTML elements and attributes.
* **JS** can react to all existing HTML events. and can create new HTML events on the page.

*Gonclusion* : The HTML DOM is a standard for how to get, change, add, or delete HTML elements.


### The DOM Tree and Nodes

All items in the *DOM* are defined as *nodes*. There are many types of nodes, but there are three main ones that we work with most often:

* Element nodes
* Text nodes
* Comment nodes

![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Dom-Tree.png)


Any lone text outside of an element is a text node, and an HTML comment is a comment node. In addition to these three node types, the document itself is a document node, which is the root of all other nodes.

### Identifying Node Type

Every **node** in a document has a *node type*, which is accessed through the nodeType *property*.



| Node Type  | Example |
| -----------   | ----------- |
| `ELEMENT_NODE` | The`<body>` element
| `TEXT_NODE` |Text that is not part of an element  |
| `COMMENT_NODE` |	`<!-- an HTML comment -->`|



![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/Attribute-Nodes-in-JavaScript-DOM.jpg)






### DOM interfaces

There are many points where understanding how these work can be confusing. For example, the object representing the HTML form element gets its name property from the HTMLFormElement interface but its className property from the HTMLElement interface. In both cases, the property you want is in that form object.

But the relationship between objects and the interfaces that they implement in the DOM can be confusing, and so this section attempts to say a little something about the actual interfaces in the DOM specification and how they are made available.


### EXAMPLE
DOCUMENT OBJECT MODEL 






![](https://image.slidesharecdn.com/xmldom-120202034528-phpapp02/95/xml-document-object-model-dom-6-728.jpg)


[For more information 🙂](https://info340.github.io/dom.html)


## Problem Domain


### What is the hardest thing about writing code?

There are many common answers as:

* *Learning a new technology*
* *Learning a new Programming language*
* *Fixing the errors*
* *Testing your code*

The list goes on and on.

### Why problem domains are hard ?

Because you need to understand well the problem domains , So Programming is easy if you understand them.

#### What can you do about it?

* Get better at understanding the problem domain.
 * Make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.


 ![](https://miro.medium.com/max/875/1*QMu3QLuDKGyBNI2UJ2bKOA.png)

&copy; 2021