# Forms and JS Events

## HTML Forms

### Why are forms so important in web development?
Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

### When designing a form, what are some key things to keep in mind when it comes to user experience?
it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need. Do not nest a form inside another form. 

### List 5 form elements and explain their importance
1) Input: Use this to get user input, exampe: a text box asking for a name <br>
2) Label: Use this to lable the information you are asking for in the input box so you can save and store the user data <br>
3) Text Area: USe this to allow the user to enter longer information that is less specific, example: asking for user comments or feedback <br>
4) li: Lthe list item element is often used in forms that have more than one user input area, use it to list out different questions for user input, example: one list item is an input for name, another list item is an input for their DOB, etc. <br>
5) Button: Use this to create a clickable button for the user, example: a submit button or reset button 

## JS Events

### How would you describe events to a non-technical friend?
Events are things that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs. Examples of this are: the user chooses a key on the keyboard, the user resizes or closes the window, a form is submitted, the page is reloaded, etc. 
To a non-tech friend I would describe it as a reaction on the site based on action from the user, the site reacts in real time in some way. 

### When using the addEventListener() method, what 2 arguments will you need to provide?
The HTML < button > element will fire an event when the user clicks the button. So it defines an addEventListener() function, which we are calling here. We're passing in two parameters: <br>

1. A String: to indicate how the event will happen, such as clicking a button. Buttons can fire lots of other events, such as "mouseover" when the user moves their mouse over the button, or "keydown" when the user presses a key and the button is focused. <br>
2. A Function: to call when the event happens, this will dictate what happens after the event. Example: clicking a submit button on a form should take you to a different page, or give you a "thank you" message of some kind. 

### Describe the event object. Why is the target within the event object useful?
Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information. The target property of the event object is always a reference to the element the event occurred upon.

### What is the difference between event bubbling and event capturing?
Event bubbling describes how the browser handles events targeted at nested elements. Event bubbling can sometimes create problems, but there is a way to prevent it. The Event object has a function available on it called stopPropagation() which, when called inside an event handler, prevents the event from bubbling up to any other elements. An alternative form of event propagation is event capture. This is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached. Event capture is disabled by default. To enable it you have to pass the capture option in addEventListener().

## Resources

- [Intro to HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)<br>
- [Creating Your First Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)<br>
- [How to Structure a Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)<br>
- [JavaScript: Dynamic, Client-side Scripting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)<br>
- [Intro to JS Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)<br>
- [HTML 5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)<br>
