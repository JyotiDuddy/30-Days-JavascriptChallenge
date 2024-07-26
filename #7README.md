// task1

let book = {
title: "Do Epic shit",
author: "Ankur Warikoo",
year: 2020,
};
console.log(book);

// task2
console.log(book.title);
console.log(book.author);

// task3
let book2 = {
title: "Do Epic shit",
author: "Ankur Warikoo",
year: 2020,
introduce: function () {
console.log(this);
return `${this.author} first publish is ${this.title}`;
},
};
console.log(book2);
console.log(book2.introduce());

// task4
let book3 = {
title: "Do Epic shit",
author: "Ankur Warikoo",
year: 2020,
updated: function (updatedYear) {
this.year = updatedYear;
},
};
book3.updated(2024);
console.log(book3);

// task5
let book4 = {
title: "Do Epic shit",
author: "Ankur Warikoo",
year: 2020,
library: {
name: "Pathshala",
books: ["Make Epic Shit", "Get Epic Shit Done"],
},
};
console.log(book4.library);

// task6
console.log(book4.library.name);
console.log(book4.library.books);

// task7
let book6 = {
title: "Do Epic shit",
author: "Ankur Warikoo",
year: 2020,
bookthis: function () {
return `${this.author} publish book on ${this.year}`;
},
};
console.log(book6.bookthis());

// task8
for (let item in book6) {
if (item.hasOwnProperty(item)) {
console.log(`${item} : ${item[item]}`);
}
}

// task9
console.log(Object.keys(book6));
console.log(Object.values(book6));
