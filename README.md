# Callbacks

## Exercise 1 

- complete the function below by adding a parameter called `callback`
- create 3 functions that return 3 different messages, 1 each. Write your own messages or use those: 
  - "done!" 
  - "finished counting for today"
  - "can take a nap now"
- pass those functions to `basicLoop` as callbacks
- the function `basicLoop` should execute the `callback` at the end of the loop

BONUS: do the same thing, using anonymous functions or arrow functions

```
function basicLoop() {
  for (let i = 0; i < 10; i++) {
    console.log(i);
  }
}
```

## Exercise 2

Write a function called `map` that accepts an array of numbers and a callback. It returns a new array after applying the callback to every number in the array.

Write 3 other functions and pass them as callbacks, to:

1. create an array with all the numbers doubled
2. create an array with the square of each number
3. create an array where all even numbers remain untouched, and odd numbers are replaced by 0


## Exercise 3

Write a function called `filter` that accepts an array of numbers and callback.

Write 3 other functions and pass them as callbacks to:

1. return a new array containing only even numbers
2. return a new array containing only numbers bigger than 10
3. return a new array containing only numbers multiples of 5

## Exercise 4

Write a function called `filterProducts` that takes an array of objects and a callback as parameters.

Write 3 functions to be used as callback to:

1. get a new array containing only products of type t-shirt
2. get a new array of only products of color yellow
3. get a new array of products that cost more than 10


```
let products = [
  {
    type: "t-shirt",
    price: 9.99,
    color: "red",
  },
  {
    type: "socks",
    price: 4.99,
    color: "blue",
  },
  {
    type: "jeans",
    price: 44.99,
    color: "black",
  },
  {
    type: "t-shirt",
    price: 14.99,
    color: "green",
  },
  {
    type: "t-shirt",
    price: 22.99,
    color: "blue",
  },
  {
    type: "jeans",
    price: 59.99,
    color: "blue",
  },
  {
    type: "skirt",
    price: 24.99,
    color: "yellow",
  },
  {
    type: "socks",
    price: 14.99,
    color: "yellow",
  },
];
```
