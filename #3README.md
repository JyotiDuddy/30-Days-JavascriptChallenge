// task 1

let num = 0;
if (num > 0) {
  console.log(`The num ${num} is positive.`);
} else {
  console.log(`The num ${num} is zero or negative.`);
}

// task 2
let age = 24;
if (age < 18) {
  console.log(`The person is eligible to vote.`);
} else {
  console.log(`The person is eligible to vote.`);
}

// task 3
let num1 = 7;
let num2 = 10;
let num3 = 17;

if (num1 > num2 && num3) {
  console.log(`The greatest is num1 ${num1}`);
} else if (num2 > num3 && num1) {
  console.log(`The greatest is num2 ${num2}`);
} else {
  console.log(`The greatest is num3 ${num3}`);
}

// task4
let day = "sunday";

switch (day) {
  case "Monday":
    console.log(`Monday`);
    break;
  case "Tuesday":
    console.log(`Tuesday`);
    break;
  case "Wednesday":
    console.log(`Wednesday`);
    break;
  case "Thursday":
    console.log(`Thursday`);
    break;
  case "Friday":
    console.log(`Friday`);
    break;
  case "Saturday":
    console.log(`Saturday`);
    break;
  default:
    console.log(`Sunday`);
}

// task5
let score = 89;
let grade;
switch (score) {
  case "score > 90":
    console.log(`The grade is A`);
    break;
  case "score > 80":
    console.log(`The grade is B`);
    break;
  case "score > 70":
    console.log(`The grade is C`);
    break;
  case "score > 60":
    console.log(`The grade is D`);
    break;
  default:
    console.log(`The grade is F`);
}

// task 6
const num5 = 12;
const numF = num5 % 2 === 0 ? "even" : "odd";
console.log(numF);

// task 7
let days = 364;
if ((days % 4 === 0 && days % 100 !== 0) || days % 400 === 0) {
  console.log(`The year is leap year`);
} else {
  console.log(`The year is non-leap year`);
}
