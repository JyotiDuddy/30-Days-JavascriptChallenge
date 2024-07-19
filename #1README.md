Day 1 VARIABLE AND DATA TYPES

1.What is Variable?

In javascript it is a way of declaring variable.variable mans holding some data value,
const b =5;
Its means b is a variable whch holds a value of 5.

2.What are the rules for declaring variables?
a. use Camelcase .
b.variable name cannot start with number.
c.variable number must start with number, underscore(\_), or doolar sign($).

3.Waht are Data types?
Data types specify the kind of data that can be stored and manipulated within the program.
Mainly ,we can differentiated data types in 2 types:-
1.Primitive data Types.
2.Reference Data Types.

Primitive data Types :- Number, Booleans,String,Symbol,BigInt, Null,Undefined.

Reference Data Types:- Function,Array, Object, etc.

<-- Practice -->

// task1
var a = 5;
console.log(a);

// task 2

let b = "Hello";
console.log(b);

// task3
const isStudent = true;
console.log(isStudent);

// task4
// 1. Primitive Data Types
const quantity = 5;
console.log(quantity, typeof quantity);

const subject = " Science";
console.log(subject, typeof subject);

const passed = true;
console.log(true, typeof passed);

const num = BigInt(999999999999999);
console.log(num, typeof num);

const y = Symbol("x");
console.log(y, typeof y);

let z;
console.log(z, typeof z);

const val = null;
console.log(b, typeof val);

// 2.Reference Data Types
function x() {
return "Hello";
}
console.log(x(), typeof x);

const arr = ["Vishal", "Rohit", "Somu"];
console.log(arr, typeof arr);

const obj = {
name: "Jyoti",
age: 24,
};
console.log(obj, typeof obj);

// task 5
let initalValue = 5;
console.log(initalValue);

initalValue = 7;
console.log(initalValue);

// task 6

// const value = 6;
// console.log(value);

// value = 7;
// console.log(value);
// Cause error bcz const value cannot be reassigned

// 1.Feature Request
const name = "Jyoti";
const age = 24;
const isStrudent = true;
const hobby = ["Reading", "Dancing"];
console.log(
`My name is ${name} age is ${age} and Its ${isStrudent} that I am a student and my hobby is ${hobby}`
);
// 2.Feature Request
let initalvalue = 5;
console.log(
`I DECLARE VARIABLE USING LET AND ITS INITAL VALUE IS ${initalValue}`
);
initalvalue = 6;
console.log(
`I DECLARE VARIABLE USING LET AND ITS MUTATED  VALUE IS ${initalValue}`
);

const actualvalue = 5;
console.log(
`I DECLARE VARIABLE USING CONST AND ITS INITAL VALUE IS ${actualvalue}`
);
// actualvalue = 9;
// console.log(
// `I DECLARE VARIABLE USING CONST AND ITS MUTATED VALUE IS ${actualvalue}`
// );
// But its create error bcz const value cannot cannot be assigned
