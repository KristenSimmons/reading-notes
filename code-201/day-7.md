# Domain Modeling

## 1. Explain why we need domain modeling.
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem. <br>

### Here are some tips to follow when building your own domain models. <br>

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors. <br>
2. Model its attributes with a constructor function that defines and initializes properties. <br>
3. Model its behaviors with small methods that focus on doing one job well. <br>
4. Create instances using the new keyword followed by a call to a constructor function. <br>
5. Store the newly created object in a variable so you can access its properties and methods from outside. <br>
6. Use the this variable within methods so you can access the object's properties and methods from inside. <br>

# HTML Table Basics

## 1. Why should tables not be used for page layouts?
It used to be common pratice to use HTML tables to lay out web pages, for example: one row to contain the header, one row to contain the content columns, one row to contain the footer, etc. This was commonly used because CSS support across browsers used to be terrible. Now, using tables for layout rather than CSS layout techniques is a bad idea. The main reasons are as follows: <br>
- Layout tables reduce accessibility for visually impaired users <br>
- Tables produce tag soup. <br>
- Tables are not automatically responsive. <br>
## 2. List and describe 3 different semantic HTML elements used in an HTML < table >.
- < td > stands for table data. This will create a cell with the information inside the tags. You need a seperate < td > for each cell. <br>
- < tr > stands for table row. This is how you can create new rows. Your < td > items would go inside of the < tr > elements for each row. <br>
- < th > stands for table header. This will give each row a header. The row and cell elements should go inside the header elements. <br>

# Introducing Constructors

## 1. What is a constructor and what are some advantages to using it?
Using object literals is fine when you only need to create one object, but if you have to create more than one, as in the previous section, they're seriously inadequate. This works fine but is a bit long-winded: we have to create an empty object, initialize it, and return it. A better way is to use a constructor. A constructor is just a function called using the new keyword. When you call a constructor, it will: <br>

- create a new object <br>
- bind this to the new object, so you can refer to this in your constructor code <br>
- run the code in the constructor <br>
- return the new object. <br>

## 2. How does the term this differ when used in an object literal versus when used in a constructor?
The "this" keyword refers to the current object the code is being written inside. This isn't hugely useful when you are writing out object literals by hand, but it will be essential when we start using constructors to create more than one object from a single object definition. Using "this" with constructors will allow for less repeating code. 

# Object Prototypes Using A Constructor

## 1. Explain prototypes and inheritance via an analogy from your previous work experience.
(NOTE: This is a very common front end developer interview question) <br>
Every object in JavaScript has an internal property called a Prototype. To find the Prototype of a newly created object, we will use the getPrototypeOf() method. The output will consist of several built-in properties and methods. <br>
For example, imagine you work at a restaurant where dishes are created based on a set of recipes. Prototypes are like recipe templates that define the basic structure and steps needed to create a dish. Inheritance is akin to creating new dishes by starting with existing recipes and making modifications or additions to them, thereby inheriting some characteristics while introducing new ones.

# Resources 
- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling) <br>
- [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics) <br>
- [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors) <br>
- [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype) <br>
- [HTML Table Advanced Features & Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)