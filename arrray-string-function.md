### Table of Contents

| No. | Questions |
|---- | ---------|

### Ques. What is the Array slice() Method?
__Ans.__
* The slice() method returns the selected elements in array, as a new array object.
* The slice() method selects the elements starting at the given start argument, and ends at, but does not include, the given end argument.
```javascript
let arrayIntegers = [1, 2, 3, 4, 5,6];
let arrayIntegers1 = arrayIntegers.slice(0,2); // returns [1,2]
let arrayIntegers2 = arrayIntegers.slice(2,3); // returns [3]
let arrayIntegers3 = arrayIntegers.slice(4); //returns [5,6]
We made 2 objects called target and handler, target is a simple object with a message key and handler is an object that has a get key with a function associated with it.
```

⬆ Back to Top

### Ques. What is the Array splice() Method?
__Ans.__ The splice() method adds/removes items to/from an array, and returns the remove items(s).

__Syntex:-__ array.aplice(index, remove_count, item1,item2, ....., itemX);

Example:- 1st position mtb add karna 2nd position mtb delete ho jana.
```javascript
var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.splice(2, 0, "Lemon", "Kiwi");
document.write(fruits);  // Banana,Orange,Lemon,Kiwi,Apple,Mango

var fruits = ["Banana", "Orange", "Apple", "Mango","mohit"];
fruits.splice(2, 2);		// dusri position sa 2 delete ho jaye. 
document.write(fruits); //	Banana,Orange,mohit

let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
let arrayIntegers1 = arrayIntegersOriginal1.splice(0,2); // returns [1, 2]; original array: [3, 4, 5]

let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]

let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];
let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
```

⬆ Back to Top
### Ques. What is the difference between slice & splice?
__Ans.__

slice()	splice()
Does not modify the original array(immutable)	Modifies the original array(mutable)
Returns the subset of original array	Return the delete element as array
Used to pick the element from array	Used to insert or delete elements to/from array.
⬆ Back to Top

Ques. How do you combine two or more arrays?
__Ans.__ The concat() method is used to join two or more arrays by returning a new array containing all the elements.

Syntex:- array1.concat(array2, array3, ..., arrayX)
```javascript
var veggies = ["Tomato", "Carrot", "Cabbage"];
var fruits = ["Apple", "Orange", "Pears"];
var veggiesAndFruits = veggies.concat(fruits);
console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
```

⬆ Back to Top
### Ques. What is the Array filter() Method?
__Ans.__ The filter() method creates an array filled with all array elements that pass a test (provided as a function).

Note: filter() does not execute the function for array elements without values.

Note: filter() does not change the original array.

Syntex:- array.filter(function(currentValue, index, arr), thisValue)
```javascript
<button onclick="myFunction()">Try it</button>
<p id="demo"></p>
<script>
var ages = [32, 33, 16, 40];
function checkAdult(age) {
  return age >= 18;
}
function myFunction() {
  document.getElementById("demo").innerHTML = ages.filter(checkAdult);
}
</script>
```

⬆ Back to Top
### Ques. What is the Array push() Method?
__Ans.__ The push() method adds new items to the end of an array, and returns the new length.

Syntex:- array.push(item1, item2, ..., itemX)

Example:-
```javascript
var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.push("Kiwi","Mango");
document.write(fruits);
```

⬆ Back to Top
### Ques. What is the Array pop() Method?
__Ans.__ The pop() method removes the last element of an array, and returns that element.

Syntex:- array.pop()
```javascript
var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.pop();
document.write(fruits);
```

⬆ Back to Top
### Ques. What is the Array shift() Method?
__Ans.__ The shift() method removes the first item of an array.
```javascript
var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.shift();
document.write(fruits);	//Orange,Apple, Mango
```

⬆ Back to Top

### Ques. What is the Array unshift() Method?
__Ans.__ The unshift() method adds new items to the beginning of an array, and returns the new length.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.unshift("Lemon", "Pineapple");
document.write(fruits); 	//Lemon,Pineapple,Banana,Orange,Apple,Mango
⬆ Back to Top

### Ques. What is the Array sort() Method?
__Ans.__ The sort() method sorts the items of an array.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.sort();
document.write(fruits);
⬆ Back to Top

Ques. What is the Array reverse() Method?
__Ans.__ The reverse() method reverses the order of the elements in an array.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.reverse();
document.write(fruits);
⬆ Back to Top

### Ques. What is the Array concat() Method?
__Ans.__ The concat() method is used to join two or more arrays.

Example:-

var hege = ["Cecilie", "Lone"];
var stale = ["Emil", "Tobias", "Linus"];
var kai = ["Robin"];
var children = hege.concat(stale,kai); 
document.write(children);
⬆ Back to Top

### Ques. What is the Array join() Method?
__Ans.__ The join() method returns the array as a string.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.write(fruits.join(" and "));
⬆ Back to Top

### Ques. What is the Array isArray() Method?
__Ans.__

⬆ Back to Top

### Ques. What is the Array indexOf() Method?
__Ans.__ The indexOf() method searches the array for the specified item, and returns its position.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.write(fruits.indexOf("Orange"));  	//1
⬆ Back to Top

### Ques. What is the Array lastIndexOf() Method?
__Ans.__ ⬆ Back to Top

### Ques. What is the Array entries() Method ?
__Ans.__ The entries() method returns an Array Iterator object with key/value pairs.

⬆ Back to Top

### Ques. What is the Array every() Method?
__Ans.__ The every() method checks if all elements in an array pass a test (provided as a function).[every() function check karta hai ki sari valu 18 sa badi hai to hi true aayega otherwise fale.]

var ages = [32, 33, 58, 40];
var b = ages.every(checkAdult);
document.write(b);

function checkAdult(age) {
  return age >= 18;
}
const isBelowThreshold = (currentValue) => currentValue < 40;
const array1 = [1, 30, 39, 29, 10, 13];
console.log(array1.every(isBelowThreshold));
// expected output: true
⬆ Back to Top

### Ques. What is the Array filter() Method?
__Ans.__

⬆ Back to Top

### Ques. What is the Array find() Method?
__Ans.__ ⬆ Back to Top

### Ques. What is the Array findindex() Method?
__Ans.__

⬆ Back to Top

### Ques. What is the Array includes() Method?
__Ans.__ includes() method check the value in the array.

The includes() method is case sensitive.

var fruits = ["Banana", "Orange", "Apple", "Mango"];
var n = fruits.includes("Mango");
document.write(n); //True
⬆ Back to Top

### Ques. What is the Array some() Method?
__Ans.__

⬆ Back to Top

Ques. What is the Array forEach() Method?
__Ans.__ ⬆ Back to Top

### Ques. What is the Array toString() Method?
__Ans.__ The toString() method returns a string with all the array values, separated by commas.

var arr = new Array("orange", "mango", "banana", "sugar");        
var str = arr.toString();
document.write("Returned string is : " + str );
⬆ Back to Top

### Ques. What is the Array valueOf() Method?
__Ans.__

⬆ Back to Top

### Ques. What is the Array fill() Method?
__Ans.__

⬆ Back to Top

### Ques. Find the length of the array?
__Ans.__

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.length;   // the length of fruits is 4
⬆ Back to Top

### Ques. Accessing the first Element of the Array?
__Ans.__

var fruits = ["Banana", "Orange", "Apple", "Mango"];
var first = fruits[0];
document.getElementById("demo").innerHTML = first;
⬆ Back to Top

### Ques. Accessing the last Element of the Array?
__Ans.__

fruits = ["Banana", "Orange", "Apple", "Mango"];
var last = fruits[fruits.length - 1]; //Mango
⬆ Back to Top

### Ques. Changing an Array Element?
__Ans.__

var cars = ["Saab", "Volvo", "BMW"];
cars[0] = "Opel";
document.getElementById("demo").innerHTML = cars[0]; //Opel,Volvo,BMW
⬆ Back to Top

### Ques. JavaScript String Length function?
__Ans.__ The length property returns the length of a string.

var txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
len = txt.length;
document.write(len);	//26
⬆ Back to Top
**[⬆ Back to Top](#table-of-contents)**
