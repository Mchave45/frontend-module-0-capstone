## Day 5 Questions

1. What is an Object, and how is it different from an Array in Javascript?

An *Object* is like an *Array* in that it stores lists of things, but *Objects* are not ordered, and can contain methods and strings and numbers.

1. In the space below, create an Object stored to a variable named `petStore`.  This object should hold an inventory of items and the number of that item that you might find at a pet store.

`var petStore = {
  puppies = 37,
  kittens = 25,
  parakeet = 15,
  hamsters = 120,
  };`

1. Given the following `states = {"CO": "Colorado", "IA": "Iowa", "OK": "Oklahoma"}`, how would you access the value `"Iowa"`?

`Object.values(states)[1];`

1. How would you add a new property to that object with a key of `"MN"` and a value of `"Minnesota"`?

`states.MN = "Minnesota";`

1. What is another example of when we might use a object?  In this case, why is a object better than an array?

You would use an *Object* when you want to store different types of data types, you can also store an *Array* inside of an *Object*. When you don't need to depend on the order you can use an *Object*

1. What questions do you still have about objects?

Why use a array at all?
