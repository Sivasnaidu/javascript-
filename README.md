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


