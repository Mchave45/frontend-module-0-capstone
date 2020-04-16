## Day 4 Questions

1. In your own words, what is the purpose of a function?
A function allows you to temporarily change a variable without having to permanently change it. It also lets you do perform the same tasks again and again without having to write the code over and over again.

1. What is a parameter?
Its the information that lets the function work.

1. What is a return value?
It allows you to use the function again and again.

1. In the space below, create a function named `hello` that will print `"Sam I am"`.
function hello(){
  return "Sam I am.";
};

console.log(hello());

1. Create a function name `hello_someone` that takes an argument of `name` and logs `name + " I am"`.
var name = "Marcos";

function hello_someone(){
  return name + " I am.";
};

console.log(hello_someone());

1. How would you call or execute the function that you created above?
console.log(hello_someone());

1. What questions do you still have about functions in Javascript?
