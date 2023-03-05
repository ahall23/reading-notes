# class 02

## HTML Text Fundamentals. HTML Advanced Text Formatting

1. Why is it important to use semantic elements in our HTML?
   > It makes your code easier to understand and it makes the source code eaiser for developers to read.
2. How many levels of headings are there in HTML?
   > There are 6 Headings in total. You cannot go over 6 headings
3. What are some uses for the < sup > and < sub > elements?
   > Dates, chemical formulae, and mathematical equations so they have the correct meaning.
4. When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
   > A title attribute

### **How CSS Is Structured.**

1.What are ways we can apply CSS to our HTML?

> You can apply them with an external stylesheet, with an internal stylesheet, and with inline styles.

2. Why should we avoid using inline styles?

   > it is the least efficient implementation of CSS for maintenance and one styling change may requore multiple edits within a single web page also it can make the code with HTML content harder to read.. we dont have time for that.

3. What is representing the selector?

> h2

4. Which components are the CSS declarations?

> brackets

5. Which components are considered properties?

> Setting CSS properties to specific values is the primary way of defining layout and styling for a document. (:)

**JavaScript Basics.**

What data type is a sequence of text enclosed in single quote marks?

> Its a string.

List 4 types of JavaScript operators.
Describe a real world Problem you could solve with a Function.

> You can solve the distance to travel to the nearest grocery shop.

**Making Decisions In Your Code – Conditionals.**

1. An if statement checks a **condition** and if it evaluates to **false**, then the code block will execute.
2. What is the use of an else if?
   > to check for true or false statements
3. List 3 different types of comparison operators.
   > === and !==
   > < and >  
   > <= and >=
4. What is the difference between the logical operator && and ||?
   > && puts together two or more expressions so that all of them can individually evaluate to true. || puts together two or more expressions but only one or more can individually be true.

[CSS width Gurll👀](https://developer.mozilla.org/en-US/docs/Web/CSS/width)

[JS Conditions- if else- else if](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

<!-- . switch statements
.if else
.else if
. operator-->

function testNum(a) {
let result;
if (a > 0) {
result = 'positive';
} else {
result = 'NOT positive';
}
return result;
}

<!-- console.log(testNum(9));
// So you have the function name "testNum" and the test is (a) if a is greater than 0
//answer 'positive' else result or answer 'NOT positive' the console.log is adressing
//the varible and what it will do and the outcome.  -->

<!-- To understand this syntax better, let's consider a real example. Imagine a child being asked for help with a chore by their mother or father. The parent might say "Hey sweetheart! If you help me by going and doing the shopping, I'll give you some extra allowance so you can afford that toy you wanted." In JavaScript, we could represent this like so:

let shoppingDone = false;
let childsAllowance;

if (shoppingDone === true) {
  childsAllowance = 10;
} else {
  childsAllowance = 5;
}
so basically you are declaring a varible which is childsAllowance; with that varible you are applying it to the condition. you letting the varible equal to something tho -->
<!-- Nesting if...else
It is perfectly OK to put one if...else statement inside another one — to nest them. For example, we could update our weather forecast application to show a further set of choices depending on what the temperature is:

if (choice === 'sunny') {
  if (temperature < 86) {
    para.textContent = `It is ${temperature} degrees outside — nice and sunny. Let's go out to the beach, or the park, and get an ice cream.`;
  } else if (temperature >= 86) {
    para.textContent = `It is ${temperature} degrees outside — REALLY HOT! If you want to go outside, make sure to put some sunscreen on.`;
  }
} -->
