# Creating Hyperlinks in HTML

## 1. To create a basic link, we wrap text or other content inside what element?
The <a> element; then you would use the href attribute. 

## 2. The href attribute contains what information?
It contains the web address for the hyperlink. 

## 3. What are some ways we can ensure links on our pages are accessible to all readers?
Don't use the word 'link' or 'click here', instead use a description of what you are linking. For example, if a business wants to add a link to their social media account, they wouldn't have a link that says 'Click this link to see our Facebook' they might say 'Check out our Facebook page'. Use precise language in your links. 


# CSS Layout: Flow and Positioning

## 1. What is meant by “normal flow”?
Normal flow refers to the layout or potiioning of elements on a page before any CSS or styling has been applied. 

## 2. What are a few differences between block-level and inline elements?
Block elements consume the entire width available irrespective of their sufficiency. They always start in a new line and have top and bottom margins. It does not contain any other elements next to it. <br>
Inline elements occupy only enough width that is sufficient to it and allows other elements next to it which are inline. Inline elements don’t start from a new line and don’t have top and bottom margins as block elements have. 


## 3. ___ positioning is the default for every html element.
Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."

## 4. Name a few advantages to using absolute positioning on an element.
An absolutely positioned element no longer exists in the normal document flow. Instead, it sits on its own layer separate from everything else. This is very useful: it means that we can create isolated UI features that don't interfere with the layout of other elements on the page. For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.

## 5. What is a key difference between fixed positioning and absolute positioning?
One key difference: where absolute positioning fixes an element in place relative to its nearest positioned ancestor (the initial containing block if there isn't one), fixed positioning usually fixes an element in place relative to the visible portion of the viewport. (An exception to this occurs if one of the element's ancestors is a fixed containing block because its transform property has a value other than none.) This means that you can create useful UI items that are fixed in place, like persistent navigation menus that are always visible no matter how much the page scrolls.

# JS Functions

# 1. Describe the difference between a function declaration and a function invocation.
To declare a fucntion is to give it a name, a value, a lable. To invoke a function is to put it to use within the code. For example: <br>

<p>1. funciton sayGoodbye(name) { <br>
2.    console.log('Goodye, ' + name); <br>
3. } <br>
4. <br>
5. sayGoodbye('neo'); </p>

We are declaring the function in line 1. We dont invoke the function until line 5. 

## 2. What is the difference between a parameter and an argument?
A parameter is the set guidlines for that particular function, set during the declaration of the function. An argument is data you pass into the function after it has been incoked, or while invoking it. 

## Resources

- [Further reading on HTML Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#a_quick_primer_on_urls_and_paths) <br>
- [CSS Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow) <br>
- [CSS Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning) <br>
- [JavaScript Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)