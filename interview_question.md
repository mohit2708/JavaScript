# JavaScript Interview Questions & Answers

### Table of Contents

| No. | Questions |
|---- | ---------|
|  | [What is JavaScript?](#ques-What-is-JavaScript)|
|  | [What is an ECMAScript?](#ques-What-is-an-ECMAScript)|
|  | [Difference between Java and JavaScript?](#ques-Difference-between-Java-and-JavaScript)|
|  | [JavaScript Data Type?](#ques-JavaScript-Data-Type)|
|  |[What is the javaScript Variable?](#ques-What-is-the-javaScript-Variable)|
|  |[What is Operate in javascript?](#ques-What-is-Operate-in-javascript)|
|  |[What is the javaScript Comment?](#ques-What-is-the-javaScript-Comment)|
|  |[What is the difference between the operators '==' and '==='?](#ques-What-is-the-difference-between-the-operators-'=='-and-'===')|
|  |[What is cookies?](#ques-What-is-cookies)|
|  |[What is Local Storage in JavaScript?](#ques-What-is-Local-Storage-in-JavaScript)|
|  |[What is Session Storage in JavaScript?](#ques-What-is-Session-Storage-in-JavaScript)|
|  |[What is the difference between Local storage & Session storage](#ques-What-is-the-difference-between-Local-storage-&-Session-storage)|
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
__Syntex:-__
```javascript
let proxy = new Proxy(target, handler)
```
#### What is a proxy object?
The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc. The syntax would be as follows,
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
