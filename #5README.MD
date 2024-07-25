// #task1
function number(num) {
if (num % 2 === 0) {
console.log(`The num  ${num} is even.`);
} else {
console.log(`The num ${num} is odd.`);
}
}
number(4);

// task 2
function square(num) {
return num \* num;
}
console.log(square(5));

// task3
const max = function (a, b, c) {
return Math.max(a, b, c);
};
console.log(max(3, 4, 10));

// task4
const concate = function (a, b) {
return a + " " + b;
};
console.log(concate("Hello", "world"));

// task5
const sum = (a, b) => a + b;
console.log(sum(6, 7));

// task6

const containChr = (str, chr) => str.includes(chr);

console.log(containChr("Javascript", "s"));
// task7
function product(a, b = 5) {
return a \* b;
}
console.log(product(2));

// task 8
function greeting(name, age = 23) {
return `Hello My name is  ${name} , I am ${age} year old. `;
}
console.log(greeting("jyoti", 24));

// task9

function repeat(fn, times) {
for (let i = 0; i < times; i++) {
fn();
}
}
repeat(() => console.log("hello", 23));

// task10
function applyFunction(f1, f2, value) {
return f2(f1(value));
}
const addFive = (x) => x + 5;
const multiple = (x) => x \* x;

console.log(applyFunction(addFive, multiple, 10));
