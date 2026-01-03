# Array Manipulation in JavaScript: From Basics to Advanced

---


## How do you create an empty array in JavaScript?
```js
const arr = [1, 2, 3, 4, "Hello", { name: "Maadevaa" }, [1, 2, 3], 4];
// const arr2 = new Array();
console.log(arr);


## How do you access the first and last elements of an array?
```js 
const firstElement = arr[0]; // O(1)
const arrLength = arr.length;
const lastElement = arr[arrLength - 1];
console.log(firstElement, arrLength, lastElement);  

## How do you remove the last element from an array?
```js
const lastElement1 = arr.pop(); // O(1)
console.log(arr, lastElement1);