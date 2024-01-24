# Learn HTML

## 1) When should you use an unordered list in your HTML document?
An unordered list works for bullet points, or any lists that don't necesarily need to be numbered or go in a specific order. 
## 2) How do you change the bullet style of unordered list items?
The bullet style can be changed by specifying which attribute you would like to use. Bullet points can come in a blacked out circle, an empty circle, a dash, or a triangle

## 3) When should you use an ordered list vs an unorder list in your HTML document?
An ordered list should be used when listing things that need to be numbered or in a specific order. 
## 4)Describe two ways you can change the numbers on list items provided by an ordered list?
You can use numbers like 1, 2, 3, 4, ..etc. or you can number items using Roman Numerals

# Learn CSS

## 1) Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Think of the Box Model like a house. The Margin box is the house itself - holding eveeything in. Within the house is are rooms, think of one room as the Border box. Inside the Border box is a closet, that is the Padding. Within the padding is your clothing, that would be the content box. 

## 2) List and describe the four parts of an HTML elements box as referred to by the box model.

1. Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height. <br>
2. Padding box: The padding sits around the content as white space; size it using padding and related properties. <br>
3. Border box: The border box wraps the content and any padding; size it using border and related properties. <br>
4. Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.<br>

# Learn JavaScript

## 1) What data types can you store inside of an Array?
Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. You can access each value inside the list individually, and do super useful and efficient things with the list. Arrays consist of square brackets and items that are separated by commas. 
## 2) Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

### "const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];"
This is a valid array, with several multidimensional arrays within. To access the value stores, you would use the index number for the item. With multidimensional arrays, you will use the index of the group and an index of the item within the group. For example, the index for the item "accountant" would be "(people[2][3])"
## 3) List five shorthand operators for assignment in javascript and describe what they do.
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x. <br>
<ol>
    <li>Assignment: "x = f( )" Means "x = f( )" So x and f( ) now have the same value</li>
    <li>Addition Assignment: "x += f( )" Means "x = x + f( )" So x now stores the vsalue of x plus f( ). </li>
    <li>Subtraction Assignment: "x -= f( )" Means "	x = x - f( )" So x now holds the value of x minus f( ).</li>
    <li>Multiplication Assignment: "x *= f( )" Means "	x = x * f( )" So x now holds the value of x multiplied by f( ).
    <li>Logical Operator: "x && f( )" This Boolean logical operator means that if both x and f( ) are equal, the funciton will be true. Otherwise, it will come back false. </li>
</ol>
 
## 4) Read the code below and evaluate the last expression and explain what the result would be and why.
 let a = 10; <br>
 let b = 'dog'; <br>
 let c = false; <br>

 // evaluate this <br>
 (a + c) + b;

 The final expression will be "false". It essentially is saying (10 + false) + 'dog'. This is not a valid expression, so the result would come back "false"

 ## 5) Describe a real world example of when a conditional statement should be used in a JavaScript program.
 Developers use conditional statements often when sites or software interact with users. For example, I have an app that allows me to track my calories and macros for eating. To find my calorie goal for the day, the app asks a series of questions, including my age and activity level. Depending on the answers provided by myself, or other users, the app will recommend a number that works best under those set of answers. Someonme with different answers than mine should get back a different result. 
## 6) Give an example of when a Loop is useful in JavaScript.
Loops are all about doing the same thing over and over again. Often, the code will be slightly different each time round the loop, or the same code will run but with different variables. A loop coud be useful for wanting to find a specific item within an array that holds 100 values. For example, you could use a loop function to search for a specific name within a phone book. 
