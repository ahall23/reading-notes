How would you describe an object to a non-technical friend you grew up with?
**is an cotainer that holds a group of values like a purse. You can pick out what you want out of your own purse.**

What are some advantages to creating object literals?
**convenience, flexibility in declaration, and less code during declaration. You can drop an object literal anywhere in your program with no previous setup and it'll work, which can be very handy!**

How do objects differ from arrays?
**Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.**

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Evaluate the code below. What does the term this refer to and what is the advantage to using this? youll need. **When you are trying to acces an array**

What is the DOM?  
Briefly describe the relationship between the DOM and JavaScript.

<!-- const is siminlar to "let" but will not change. Person is a vairble and {} 👈🏽 is what objects be in. name: age: bio: are all properities that is naming the array. we also have a console.log which is ouputing the function.-->

const person = {
name: ["Bob", "Smith"],
age: 32,
bio: function () {
console.log(`${this.name[0]} ${this.name[1]} is ${this.age} years old.`);
},
introduceSelf: function () {
console.log(`Hi! I'm ${this.name[0]}.`);
},
};

person.name;
person.name[0];
person.age;
person.bio();
person.introduceSelf();
