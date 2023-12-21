# Operations & Loops in JavaScript

## 1. What is an expression in JavaScript?

At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate. <br>

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7. <br>

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded.

## 2. Why would we use a loop in our code?

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!) <br>

Various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

## 3. When does a for loop stop executing?

A for loop repeats until a specified condition evaluates to false. <br>
Example of a 'for' statement: <br>

for (initialization; condition; afterthought) <br>
    (indent) statement

## 4. How many times will a while loop execute?

The do...while statement repeats until a specified condition evaluates to false. <br>

A do...while statement looks as follows: <br>

do <br>
  (indent) statement <br>
(indent) while (condition);

## References

[Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#do...while_statement)

[Expressions & Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

