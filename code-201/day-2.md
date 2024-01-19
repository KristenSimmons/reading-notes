# HTML Fundamentals
## 1) Why is it important to use semantic elements in our HTML?

HTML is a coding launguage that uses elements to display bits of information. The elements have set stylings that will display automatically. Semantic elements in HTML are elements that have set stylings. It is important to use semantic elements in HTML because it makes the code run smoother, and optimizes the SEO. IT can also make it easier for others to contribute or collaborate on the same projects. 
## 2) How many levels of headings are there in HTML?
There are 6 levels of headings in HTML. Level 1 is the largest, level 6 is the smallest. 

## 3)What are some uses for the < sup > and < sub > elements?

The < sup > element is for adding super script into the text. These look like the little numbers when doing square roots, for example: <br>
<p>The <em>Pythagorean theorem</em> is often expressed as the following equation:</p>

<p>
  <var>a<sup>2</sup></var> + <var>b<sup>2</sup></var> = <var>c<sup>2</sup></var>
</p>

The < sub > element is for adding subscript to the text, like the little numbers used for chemical make up. For example: 
<p>
  Almost every developer's favorite molecule is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>, also known as
  "caffeine."
</p>



##  4)When using the < abbr > element, what attribute must be added to provide the full expansion of the term?

The < abbr > element represents an abbreviation or acronym. When using the < abbr > element, provide the full term in plain text on the first use, along with the <abbr> to mark up the abbreviation. This informs the user what the abbreviation or acronym means. <br>

Accoring to MOzilla, "The optional title attribute can provide an expansion for the abbreviation or acronym when a full expansion is not present. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means. If present, title must contain this full description and nothing else."

# CSS Fundamentals

## 1) What are ways we can apply CSS to our HTML?
There are 3 ways to apply CSS styling to an HTML document: use an external styling sheet, an internal styling sheet, or use in-line styling. 

## 2) Why should we avoid using inline styles?
It is best practice to use either an external or internal styling sheet, avoid in-line styling whenever possible. In-line styling is the least efficient implementation of CSS for maintenance. Also, in-line styling mizes CSS and HTML, making it more difficult for others to read and understand the coding. 

Review the block of code below and answer the following questions:

   h2 { <br>
     color: black;<br>
     padding: 5px;<br>
   }

### 1) What is representing the selector?
The selector refers to the bit of HTML we are styling, in this case the "h2" heading. 
### 2) Which components are the CSS declarations?
The declarations in this example refer to the "black" and "5px" settings. 
### 3) Which components are considered properties?
The properties in this example are "color" and "padding". They refer to a set thing, that we can then style with declarations.
# JavaScript Basics

## 1) What data type is a sequence of text enclosed in single quote marks?
In JavaScript, this is called a string element. 
## 2) List 4 types of JavaScript operators:
An operator is a mathematical symbol that produces a result based on two values (or variables). <br>
Four examples would be: 
<ul>
  <li>Using the + symbol to add 2 values or variables together</li>
  <li>Using the - symbol to subtract</li>
  <li>Using the = symbol to assign a value to a variable</li>
  <li>Using the === symbols to represent strict equality</li>
</ul>
## 3) Describe a real world Problem you could solve with a Function.
A function basically just produces an output based on certain input. A good example of a problem that can be solved with this type of function would be with scheduling telehealth appointments. A patient could potentially log into their doctors website and get help basic help or advice without having to see or speak to a doctor. This would be great when kids are sick and need a doctors note to return to school. It often may not be necesary to see a physician for every little thing. Or it may not be convenient or available to see them same day. Or, depending on the answers given by the patient, it could be determined that they DO need an appointment after all. 

## Conditionals:

### 1) An if statement checks a __ and if it evaluates to ___, then the code block will execute.
The if statement checks a "response" and if it evaluates to "true", the code block will execute. 
### 2) What is the use of an else if?
"Else if" can be used to give other options for a response. For example, if there are various responses that could be considered true, or close to true. 
### 3) List 3 different types of comparison operators.
Comparison operators are used in logical statements to determine equality or difference between variables or values. <br>
For example:
<ul>
  <li>== means two variables have the same value</li>
  <li>=== means two variables have the same type and value, exact equality</li>
  <li>!= means not equal</li>
</ul>

### 4) What is the difference between the logical operator && and ||?
The logical AND ( && ) (logical conjunction) operator for a set of boolean operands will be true if and only if all the operands are true. Otherwise it will be false. The operator returns the value of the first falsy operand encountered when evaluating from left to right, or the value of the last operand if they are all truthy. <br>
The logical OR ( || ) (logical disjunction) operator for a set of operands is true if and only if one or more of its operands is true. It is typically used with boolean (logical) values. When it is, it returns a Boolean value. However, the || operator actually returns the value of one of the specified operands, so if this operator is used with non-Boolean values, it will return a non-Boolean value.



#### Resources and examples borrowed from:
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
[JaveScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
