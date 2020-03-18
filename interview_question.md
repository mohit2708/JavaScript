# JavaScript Interview Questions & Answers

### Table of Contents

| No. | Questions |
|---- | ---------|
|  | [What is JavaScript?](#ques-What-is-JavaScript)|
|  | [What is an ECMAScript?](#ques-What-is-an-ECMAScript)|
|  | [Difference between Java and JavaScript?](#ques-Difference-between-Java-and-JavaScript)|
|  | [JavaScript Data Type?](#ques-JavaScript-Data-Type)|
|  |[What is the javaScript Variable?](#ques-What-is-the-javaScript-Variable)|

### Ques. What is JavaScript?
__Ans.__
* JavaScript is a Client-side as well as server side scripting language that can be inserted into HTML pages. JavaScript is also an object based Programming language.
* JavaScript is the programming language of HTML and the Web.
* JavaScript was created by Brendan Eich in September 1995.
* JavaScript is a case sensitive language.
* Netscape is the software company who developed JavaScript.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is an ECMAScript?
__Ans.__ ECMAScript (European Computer Manufacturers Association) Script is a specification for the scripting language standards. It has standardized Javascript which made Javascript the best implementation of ECMAScript.

**[⬆ Back to Top](#table-of-contents)**
### Ques. Difference between Java and JavaScript?
__Ans.__
|Java|JavaScript|
|:---:|:---:|
|Java is an OOP Programming Language.|javaScript is an OOP scripting language.|
|It creates applications that run in a virtual machine or browser.|The code is run on a browser only.|
|Java code needs to be compiled.|JavaScript code are all in the form of text.|

**[⬆ Back to Top](#table-of-contents)**
### Ques. JavaScript Data Type?
__Ans.__ JavaScript variables can hold many data types.

There are 7 primitive types: string, number, bigint, boolean, symbol, null and undefined.

__String:–__ Represents single-character, multi-character, and alphanumeric values
```javascript
let str = "Hello";
var a = 'Hi there!';  // using single quotes
var b = "Hi there!";  // using double quotes
var a = "Let's have a cup of coffee."; //single quote inside double quotes
var b = 'He said "Hello" and left.';  //double quotes inside single quotes
var c = 'We\'ll never give up.';     //escaping single quote with backslash
```

__Number:–__ Represents both integer and floating point values
```javascript
var a = 25;         // integer
var b = 80.5;       // floating-point number
var c = 4.25e+6;    // exponential notation, same as 4.25e6 or 4250000
var d = 4.25e-6;    // exponential notation, same as 0.00000425
```

__Boolean:–__ Represents true and false values
```javascript
var isReading = true;   // yes, I'm reading
var isSleeping = false; // no, I'm not sleeping
var a = 2, b = 5, c = 10; 
alert(b > a) // Output: true
alert(b > c) // Output: false
```

__Null:–__ Represents empty, nothing, and unknown type of values
```javascript
var a = null;
alert(a); // Output: null 
var b = "Hello World!"
alert(b); // Output: Hello World! 
b = null;
alert(b) // Output: null
```
__Object:–__ Used for storing collections of data or more complex entities
```javascript
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```

__Symbol:–__ Used for creating unique identifiers for objects

__Undefined–__ Represents value not assigned. If a variable is only declared and not assigned in JS, then it represents the undefined data type

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the javaScript Variable?
__Ans.__
* A javaScript Variable is simply a name of storage location. There are 2 types of variable in javaScript.
* There are some rules with declaring a javascript varible.
* Name must start with a letter(a to z or A to Z), underscore (_), or dollar ( $ ) sign.
* After the first letter we can use digit (0 to 9), for example value1.
* JavaScript variable are case sensitive, for example x and X are diffrent
* We can declare variables to store data by using the var, let, or const keywords.
* javaScript includes variables which hold the data value and it can be changed anytime.
* To create a variable in JavaScript, use the let keyword.
* Variables named apple and AppLE are two different variables.
