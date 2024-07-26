// task1
let arr = [1, 2, 3, 4, 5];
console.log(arr);

// task2
console.log(arr[0]);
console.log(arr[4]);

// task3
arr.push(6);
console.log(arr);

// task4
arr.pop();
console.log(arr);

// task5
arr.shift();
console.log(arr);

// task6
arr.unshift(1);
console.log(arr);

// task7
const arr2 = arr.map((num) => num \* 2);
// console.log(arr2);

// task8
const arr3 = arr.filter((ar) => ar % 2 === 0);
console.log(arr3);

// task9
const arr4 = arr.reduce((num, acc) => {
return acc + num;
}, 0);
console.log(arr4);

// task10

// for loop
for (let i = 0; i <= arr.length - 1; i++) {
console.log(arr[i]);
}

// for of loop
for (const item of arr.entries()) {
console.log(item);
}

// task 11
arr.forEach((num) => {
console.log(num);
});

// task12
let matrix = [
[1, 2, 3],
[4, 5, 6],
[7, 8, 9],
];
console.log(matrix);

// task 13
let matrix2 = [
[1, 2, 3],
[4, 5, 6],
[7, 8, 9],
];
console.log(matrix2[1][1]);
