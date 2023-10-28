Javascript 
* Data structures in js are arrays, sets and maps.
* Variables are containers to store data for var, let and const.
Es6 let and const are introduced.
Var variables can use value and number (value1) but not (1value)
No space (var first name), camelCase can be used.
Var and let variable can be changed 
! Var name = “hari”;
name = “giri”;
console.log(name); !
Const variable cant be changed.

String methods;
toLowerCase()
toUpperCase()
trim()
slice()
const  firstName = 'harikrishna';
let name = firstName.slice(2,4)
console.log(name)

Data types primitive:
String
Number
Boolean
Null
Undefined
Symbol
BigInt

“console.log(typeof firstName)”

Convert num to string;
Age  = age + “”;

Covert string to number
Let myStr = +”32”;

String concaenation 
const  firstName = 'harikrishna';
let name = "deva";
let fullName = firstName + name;
console.log(fullName)

Template litrals /strings
const  firstName = 'harikrishna';
let name = "deva";
let fullName = ` my name is ${name}  ${firstName}`

console.log(fullName)

Teranary operator
 let age = 18;
 let drink = age <= 10 ? "cofee" : "milk";
 console.log(drink)

And operator only of both conditions are true &&
let name = 'wizi';
let age = 22;

if (name[0] === "w" && age < 18){
  console.log("Hero")
}
else {
  console.log("Villan")
}

|| or operator if onr of the condition is true;
 let name = 'wizi';
let age = 22;

if (name[0] === "s" || age < 18){
  console.log("Hero")
}
else {
  console.log("Villan")
}

//Array Methods ::

push();
Adds one or more elements to the end of an array and returns the new length of the array.
const fruits = ['apple', 'mango', 'grapes','orange'];
let fruit1 = fruits.push('banana');
console.log(fruits);

pop() - Removes the last element from an array and returns that element.
const fruits = ['apple', 'mango', 'grapes','orange'];
let fruit1 = fruits.pop();
console.log(fruits);

unshift() - Adds one or more elements to the beginning of an array and returns the new length of the array.
const fruits = ['apple', 'mango', 'grapes','orange'];
let fruit1 = fruits.unshift('banana');
console.log(fruits);

shift() - Removes the first element from an array and returns that element.
const fruits = ['apple', 'mango', 'grapes','orange'];
let fruit1 = fruits.shift();
console.log(fruits);

concat() - Combines two or more arrays and returns a new array.
const fruits = ['apple', 'mango', 'grapes','orange'];
const fruit = ['banana','kiwi']
let fruit1 = fruits.concat(fruit);
console.log(fruit1);

join() - Joins all elements of an array into a string with a specified separator.
const fruits = ['apple', 'mango', 'grapes','orange'];
const fruit = fruits.join(',')
console.log(fruit);

slice() - Returns a shallow copy of a portion of an array into a new array.
const fruits = ['apple', 'banana', 'orange', 'strawberry'];
const selectedFruits = fruits.slice(1, 3);
// selectedFruits is ['banana', 'orange']

splice() - Changes the contents of an array by removing, replacing, or adding elements.
const fruits = ['apple', 'banana', 'orange'];
fruits.splice(1, 1, 'strawberry');
// fruits is now ['apple', 'strawberry', 'orange']

forEach()
const numbers = [1, 2, 3];
numbers.forEach((number) => {
    console.log(number * 2);
});
// Output: 2, 4, 6




