# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

### 1. How would you describe an object to a non-technical friend you grew up with?
An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). Basically, an object is kind of like a box that can hold many items. We can access those items later individually, or move/manipulate the entire box if we need to. 

### 2. What are some advantages to creating object literals?
An object like this is referred to as an object literal — we've literally written out the object contents as we've come to create it. This is different compared to objects instantiated from classes. It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.

### 3. How do objects differ from arrays?
Objects hold properties that have different values and functions. The properties in the object can be easier to work with individually, compared to working with individual components of an array. 

### 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use square brackets. For example, if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

### 5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
The "this" keyword refers to the current object the code is being written inside — so in this case this is equivalent to dog. The advantage to using "this.name" instead of "dog.name". If you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create. For example, if you had many objects (dog1, dog2, dog3, etc.) You could simply use "this.name" in each object, instead of "dog1.name", "dog2.name", and so on. This isn't hugely useful when you are writing out object literals by hand, but it will be essential when we start using constructors to create more than one object from a single object definition. <br>
<p>
"const dog = { <br>
  name: 'Spot', <br>
  age: 2, <br>
  color: 'white with black spots', <br>
  humanAge: function (){ <br>
    console.log(`${this.name} is ${this.age*7} in human years`); <br>
  } <br>
}" <br>
</p>

## Introduction To The DOM

### 1. What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

A web page is a document that can be either displayed in the browser window or as the HTML source. In both cases, it is the same document but the Document Object Model (DOM) representation allows it to be manipulated. As an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.

### 2. Briefly describe the relationship between the DOM and JavaScript.
The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript. The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.

## Resources
- [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics) <br>
- [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) <br>
- [Solving Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/) <br>
- [What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

