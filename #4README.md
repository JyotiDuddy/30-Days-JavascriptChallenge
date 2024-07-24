// task 1
for (let i = 1; i <= 10; i++) {
console.log(i);
}

// task 2
for (let i = 0; i <= 100; i++) {
if (i % 5 === 0) {
console.log(i);
}
}

// task 3
let i = 1;
while (i <= 10) {
console.log(i);
i++;
}

// task 4
let rep = 10;
while (rep >= 0) {
console.log(rep);
rep--;
}

// task5

let b = 1;
do {
console.log(b);
b++;
} while (b <= 5);

// task6
let number = 5;
let factorial = 1;
let z = number;

do {
factorial \*= z;
z--;
} while (z > 0);

// task 7
for (let row = 0; row <= 5; row++) {
let pattern = "";
for (let col = 0; (col = row + 1); col++) {
pattern += "\*";
}
}

// task 8
for (let i = 0; i <= 10; i++) {
if (i === 5) continue;
console.log(i);
}

// task 9
for (let i = 0; i <= 10; i++) {
if (i === 7) break;
console.log(i);
}
