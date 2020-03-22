# JavaScript Interview Questions & Answers

### Table of Contents

| No. | Questions |
|---- | ---------|
|  | [What is JavaScript?](#ques-What-is-JavaScript)|
|  | [What is an ECMAScript?](#ques-What-is-an-ECMAScript)|
|  |[Name some of the Javascript frameworks?](#Name-some-of-the-Javascript-frameworks)
|  | [Difference between Java and JavaScript?](#ques-Difference-between-Java-and-JavaScript)|
|  | [JavaScript Data Type?](#ques-JavaScript-Data-Type)|
|  |[What is the javaScript Variable?](#ques-What-is-the-javaScript-Variable)|
|  |[Dfference between var and Let?](#ques-difference-between-var-and-let)
|  |[What is Operate in javascript?](#ques-What-is-Operate-in-javascript)|
|  |[What is the javaScript Comment?](#ques-What-is-the-javaScript-Comment)|
|  |[What is the difference between the operators '==' and '==='?](#ques-What-is-the-difference-between-the-operators-'=='-and-'===')|
|  |[What is cookies?](#ques-What-is-cookies)|
|  |[What is Local Storage in JavaScript?](#ques-What-is-Local-Storage-in-JavaScript)|
|  |[What is Session Storage in JavaScript?](#ques-What-is-Session-Storage-in-JavaScript)|
|  |[What is the difference between Local storage & Session storage](#ques-What-is-the-difference-between-Local-storage-&-Session-storage)|
|  |[What is Proxy object?](#ques-What-is-Proxy-object)|
|  |[What is JavaScript Object?](#ques-What-is-JavaScript-Object)|
|  |[What are the possible ways to create objects in javascript?](#ques-What-are-the-possible-ways-to-create-objects-in-javascript)|
|  |[What are the different error names from error object?](#ques-What-are-the-different-error-names-from-error-object)|
|  |[What is JavaScript Function](#ques-What-is-JavaScript-Function)|
|  |[What are lambda or arrow functions?](#ques-What-are-lambda-or-arrow-functions)|
|  |[What is currying function?](#ques-What-is-currying-function)|
|  |[What is Generator function?](#ques-What-is-Generator-function)|
|  |[What is a callback function?](#ques-What-is-a-callback-function)|
|  |[What is callback in callback?](#ques-What-is-callback-in-callback)|
|  |[What is the difference between write and writeln?](#ques-What-is-the-difference-between-write-and-writeln)|
|  |[Name the different types of pop up boxes in Javascript?](#Ques-Name-the-different-types-of-pop-up-boxes-in-Javascript)|
|  |[]()|
|  |[]()|
|  |[]()|



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
### Name some of the Javascript frameworks?
(i) Angular (ii) React (iii) Vue

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

**[⬆ Back to Top](#table-of-contents)**
### Ques. Dfference between var and Let?
|Var|let|
|:---:|:---:|
|It has a global/function scope.|It is limited to block scope.|
|It can be declared globally and can be accessed globally.|It can be declared globally but cannot be accessed globally.|
|It is hoisted.|It is not hoisted.|
|Variable declared with var keyword can be re-declared and updated in the same scope.|Variable declared with let keyword can be updated but not re-declared.|
Example:	
function varGreeter(){ 
var a = 10;
 var a = 20; //a is replaced
 console.log(a);
 } 
varGreeter();
Example: 
function varGreeter(){ 
let a = 10; 
let a = 20; //SyntaxError: 
//Identifier 'a' has already been declared console.log(a);
 } 
varGreeter();
Variables will be hoisted
Hoisted but not initialized

let message;
message = 'Hello!';
alert(message); // shows the variable content

let user = 'John', age = 25, message = 'Hello';   //We can also declare multiple variables in one line:

A real-life analogy:-

let message;
message = 'Hello!';
message = 'World!'; // value changed
alert(message);  //World

let hello = 'Hello world!';
let message;  // copy 'Hello world' from hello into message
message = hello;// now two variables hold the same data
alert(hello); // Hello world!
alert(message); // Hello world!

Variable naming:-
There are two limitations on variable names in JavaScript:
The name must contain only letters, digits, or the symbols $ and _.
The first character must not be a digit.



**[⬆ Back to Top](#table-of-contents)**
### Ques. What is Operate in javascript?<br>
__Arithmetic Operators:-__ Addition(+), Subtraction(-), Multiplication(*), Exponentiation (ES2016)(**), Division(/), Modulus(Division Remainder)(%), Increment(++), Decrement(--).

__Assignment Operators:-__

__Comparison Operators:-__

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the javaScript Comment?<br>
__Single Line Comment:-__ Single line comment start with //<br>
__Multi-Line Comments:-__ Multi-Line comment start with /* and end with */

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the difference between the operators '==' and '==='?
__Ans.__ The operator '==' compares the value; whereas, the operator '===' compares both value and type.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is cookies?
__Ans.__ Php cookie is a small piece of information, which is stored on the client browser. Cookies are saved as key/value pairs.<br>
__Syntex:-__ document.cookie = "key1 = value1; key2 = value2; expires = date";
```javascript
document.cookie = "username=John Doe; expires=Thu, 18 Dec 2013 12:00:00 UTC; path=/";
```
__Delete Cookie:-__ To delete a cookie, you just need to set the value of the cookie to empty and set the value of expires to a passed date.

#### Two Types Of Cookie:-

__1. Persistent Cookie:-__ A persistent cookie is a cookie which is store information for certain time in a browser. By default cookie are temporary and are erased if we close the browser.<br>
__2. Non Persistent Cookie:-__ Non persistent cookies are stored in ram on the server. Ex:- login

#### Why do you need a Cookie?
* Cookies are used to remember information about the user profile(such as username). It basically involves two steps,
* When a user visits a web page, user profile can be stored in a cookie.
* Next time the user visits the page, the cookie remembers user profile.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is Local Storage in JavaScript?
* The local storage is a read only Property of window object.
* It stores the data in a web browser specifically to the domain and protocol.
* It does not get sent to the server as it is stored locally in the web browser with no expiration date.
* The data will not be deleted when the browser is closed and reopened and will be available the next day, week or year.
Methods

__1. setItem(key, value):-__ It allows to add a key/value pair to the storage obj. if the key already exists, the name value will overwrite the old value.<br>
__2. getItem(Key):-__ It returns the value of the item that is set with the given key.<br>
__3. key(n):-__ It returns the key of the item in the storage obj at the nth index which can be useful for looping.<br>
__4. removeItem(key):-__ It removes the item in the storage object with the given key.
__5. sessionStorage.clear(); :-__ Remove all saved data from sessionStorage
```javascript
window.localStorage.setItem("user","mohit");
window.localStorage.setItem("email","mksaxena27@gmail.com");
console.log(localStorage);
console.log(localStorage.length)		//2
console.log(localStorage.getItem('email'))	//mksaxena27@gmail.com
console.log(localStorage.key(0))		//email
localStorage.removeItem('email')		//email delete ho gaya
localStorage.clear()				// all localstorage clear
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is Session Storage in JavaScript?
* The session storage read only property of window object.
* It store data in web browser specifically to the domain and protocol for a particular session.
* It does not get sent to the server.
* Data stored in session storage gets cleared when the page session ends.
* A page session lasts for as long as the browser is open and survives over page reload and restore.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the difference between Local storage & Session storage?
__Local Storage:–__ The data is not sent back to the server for every HTTP request (HTML, images, JavaScript, CSS, etc) – reducing the amount of traffic between client and server. It will stay until it is manually cleared through settings or program.<br>
__Session Storage:–__ It is similar to local storage; the only difference is while data stored in local storage has no expiration time, data stored in session storage gets cleared when the page session ends. Session Storage will leave when the browser is closed.<br>

LocalStorage is same as SessionStorage but it persists the data even when the browser is closed and reopened(i.e it has no expiration time) whereas in sessionStorage data gets cleared when the page session ends.<br>

Ans. Local Storage will stay until it is manually cleared through settings or program.
Session Storage will leave when the browser is closed.

### Ques. What is Proxy object?
* A Proxy object wraps another object and intercepts operations.
* Proxy is an object in javascript which wraps an object or a function and monitors it via something called target.
* Proxy is a wrapper around an object, that forwards operations on it to the object, optionally trapping some of them.
* It can wrap any kind of object, including classes and functions.<br>
* The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc. The syntax would be as follows.
__Syntex:-__
```javascript
let proxy = new Proxy(target, handler)
```
```javascript
var p = new Proxy(target, handler);
Let's take an example of proxy object,
var handler = {
    get: function(obj, prop) {
        return prop in obj ?
            obj[prop] :
            100;
    }
};

var p = new Proxy({}, handler);
p.a = 10;
p.b = null;

console.log(p.a, p.b); // 1, null
console.log('c' in p, p.c); // false, 100
In the above code, it uses get handler which define the behavior of the proxy when an operation is performed on it
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is JavaScript Object?
* An object can be created with curly brackets { } with an optional list of properties.
* A property is a “Key:value” pair, where the key (or property name) is always a string, and value (or property value) can be any data type, like string, number, boolean or complex data type like array, function, and other objects.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What are the possible ways to create objects in javascript?
There are many ways to create objects in javascript as below,<br>
1. **Object constructor:**<br>
 The simplest way to create an empty object is using Object constructor. Currently this approach is not recommended.
 ```javascript
 var object = new Object();
 ```
 2. **Object's create method:**
 The create method of Object creates a new object by passing the prototype object as a parameter
 ```javascript
 var object = Object.create(null);
 ```
 3. **Object literal syntax:**
 The object literal syntax is equivalent to create method when it passes null as parameter
 ```javascript
 var object = {};
 ```
 4. **Function constructor:**
 Create any function and apply the new operator to create object instances,
 ```javascript
 function Person(name){
  var object = {};
  object.name=name;
  object.age=21;
  return object;
 }
 var object = new Person("Sudheer");
 ```
 5. **Function constructor with prototype:**
 This is similar to function constructor but it uses prototype for their properties and methods,
```javascript
function Person(){}
Person.prototype.name = "Sudheer";
var object = new Person();
```
This is equivalent to an instance created with an object create method with a function prototype and then call that function with an instance and parameters as arguments.
```javascript
function func {};

new func(x, y, z);

**(OR)**

// Create a new instance using function prototype.
var newInstance = Object.create(func.prototype)

// Call the function
var result = func.call(newInstance, x, y, z),

// If the result is a non-null object then use it otherwise just use the new instance.
console.log(result && typeof result === 'object' ? result : newInstance);
```

6. **ES6 Class syntax:**
ES6 introduces class feature to create the objects
```javascript
class Person {
 constructor(name) {
    this.name = name;
 }
}

var object = new Person("Sudheer");
```

7. **Singleton pattern:**
A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and this way one can ensure that they don't accidentally create multiple instances.
```javascript
var object = new function(){
  this.name = "Sudheer";
}
```
Accessing object:- var book = { "name": "Harry Potter and the Goblet of Fire", "author": "J. K. Rowling", "year": 2000 }; document.write(book.author); // Prints: J. K. Rowling document.write(book["year"]); // Prints: 2000

Setting object:- var person = { name: "Peter", age: 28, gender: "Male" }; // Setting a new property person.country = "United States"; document.write(person.country); // Prints: United States

Deleting object:- var person = { name: "Peter", age: 28, gender: "Male", displayName: function() { alert(this.name); } }; // Deleting property delete person.age; alert(person.age); // Outputs: undefined

**[⬆ Back to Top](#table-of-contents)**
### Ques. What are the different error names from error object?
There are 6 different types of error names returned from error object,
| Error Name | Description |
|---- | ---------
| EvalError  | An error has occurred in the eval() function |
| RangeError | An error has occurred with a number "out of range"  |
| ReferenceError | An error due to an illegal reference|
| SyntaxError | An error due to a syntax error|
| TypeError | An error due to a type error |
| URIError | An error due to encodeURI() |


**[⬆ Back to Top](#table-of-contents)**
### Ques. What is JavaScript Function?
* A JavaScript function is a block of code designed to perform a particular task.
* You can reuse code: Define the code once, and use it many times.
* You can use the same code many times with different arguments, to produce different results.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What are lambda or arrow functions?
* An arrow function is a shorter syntex for a function.
```javasacript
hello = () => {
  return "Hello World!";
}

let sum = (a, b) => a + b;
alert( sum(1, 2) ); // 3
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is currying function?
* Currying is a technique of evaluating function with multiple arguments, into sequence of function with single argument.
* Currying is a transformation of functions that translates a function from callable as f(a, b, c) into callable as f(a)(b)(c).
* Currying is an advanced technique of working with functions. It’s used not only in JavaScript, but in other languages as well.
* Currying helps you to avoid passing the same variable again and again.
* Currying is the process of taking a function with multiple arguments and turning it into a sequence of functions each with only a single argument. Currying is named after a mathematician Haskell Curry. By applying currying, a n-ary function turns it into a unary function. 
Syntex:-
```javascript
function* name([param[, param[, ... param]]]) {
   statements
}
```
Example:-
```javascript
function curry(f) { // curry(f) does the currying transform
  return function(a) {
    return function(b) {
      return f(a, b);
    };
  };
}

// usage
function sum(a, b) {
  return a + b;
}

let curriedSum = curry(sum);

alert( curriedSum(1)(2) ); // 3


A partial invocation of a Javascript function is called Currying. Few arguments of a function are processed and a function is returned. Few more arguments are added by the returning function.


What is currying function?
Let's take an example of n-ary function and how it turns into a currying function
const multiArgFunction = (a, b, c) => a + b + c;
const curryUnaryFunction = a => b => c => a + b + c;
curryUnaryFunction (1); // returns a function: b => c =>  1 + b + c
curryUnaryFunction (1) (2); // returns a function: c => 3 + c
curryUnaryFunction (1) (2) (3); // returns the number 6
Curried functions are great to improve code re-usability and functional composition.
```

 **[⬆ Back to Top](#table-of-contents)**
### Ques. What is Generator function?
* Generators are a special class of functions that simplify the task of writing iterators.
* A generator is a function that produces a sequence of results instead of a single value, i.e you generate ​a series of values.
* Regular functions return only one, single value (or nothing).
* Generators can return (“yield”) multiple values, one after another, on-demand.
* Generators are created by generator functions function* f(…) {…}.
```javascript
function* idMaker() {
    var index = 0;
    while(true)
        yield index++;
}
var gen = idMaker(); // "Generator { }"
console.log(gen.next().value); // 0
console.log(gen.next().value); // 1
console.log(gen.next().value); // 2
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is a callback function?
* callback function is a function passed into another function as an argument.
* This function is invoked inside the outer function to complete an action.
```javascript
function callbackFunction(name) {
  console.log('Hello ' + name);
}

function outerFunction(callback) {
  let name = prompt('Please enter your name.');
  callback(name);
}

outerFunction(callbackFunction);
```

**[⬆ Back to Top](#table-of-contents)**
### What is callback in callback?
You can nest one callback inside in another callback to execute the actions sequentially one by one. This is known as callbacks in callbacks.
```javascript
loadScript('/script1.js', function(script) {
   console.log('first script is loaded');

  loadScript('/script2.js', function(script) {

    console.log('second script is loaded');

    loadScript('/script3.js', function(script) {

        console.log('third script is loaded');
      // after all scripts are loaded
    });

  })

});
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is a promise?
A promise is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.
    The syntax of promise would be as below
```javascript
const promise = new Promise(function(resolve, reject) {
   // promise description
})
```

**[⬆ Back to Top](#table-of-contents)**
### Ques. Why do you need a promise?
Promises are used to handle asynchronous operations. They provide an alternative approach for callbacks by reducing the callback hell and writing the cleaner code.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What are the three states of promise?
Promises have three states:
1. **Pending:** This is an initial state of the Promise before an operation begins
2. **Fulfilled:** This state indicates that specified operation was completed.
3. **Rejected:** This state indicates that the operation did not complete. In this case an error value will be thrown.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the difference between write and writeln?
write and writeln are the same function. The only difference is that writeln adds a new line at the end of the text. writeln adds a \n character to the end of the string
```javascript
document.write("Hello World!");
document.write("Have a nice day!"); 
output:- //Hello World!Have a nice day!

document.writeln("Hello World!");
document.writeln("Have a nice day!"); 
Output:- //Hello World!
	//Have a nice day!
 ```
 
 **[⬆ Back to Top](#table-of-contents)**
### Ques. What is the use of isNaN Function?
* isNan function returns true if the argument is not a number otherwise it is false.
* NaN is a short form of Not a Number.

 **[⬆ Back to Top](#table-of-contents)**
### Ques. Name the different types of pop up boxes in Javascript?
There are three types of pop up boxes in Javascript<br>
(i) alert() provides some information to the user with just an OK button<br>
(ii) confirm() asks a question to the user with two options Ok and cancel, and<br>
(iii) prompt() takes an input from the user.


**[⬆ Back to Top](#table-of-contents)**
### Ques. What is the setInterval?
* The setInterval() method calls a function or evaluates an expression at specified intervals (in milliseconds).
* The setInterval() method will continue calling the function until clearInterval() is called, or the window is closed.
* The ID value returned by setInterval() is used as the parameter for the clearInterval() method.<br>
__syntex:-__ setInterval(function, milliseconds, param1, param2, ...)
```javascript
function myFunction() {
  setInterval(function(){ alert("Hello"); }, 3000);
}
```
```javascript
<button onclick="myStopFunction()">Stop time</button>
<script>
var myVar = setInterval(myTimer, 1000);
function myTimer() {
  var d = new Date();
  var t = d.toLocaleTimeString();
  document.getElementById("demo").innerHTML = t;
}
function myStopFunction() {
  clearInterval(myVar);
}
</script>
```

