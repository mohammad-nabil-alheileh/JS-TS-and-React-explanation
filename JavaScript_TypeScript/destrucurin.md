Destructuring it unpacks values out of an array or object and puts them straight into variables, it prevent repeating the code

we can destrucuuring by

- position : const [first, second] = colors;
const [, , third] = colors;

- name : const user = { name: "Ali", age: 20, city: "Amman" };

const { name, age } = user;

we can use it in function parameters 