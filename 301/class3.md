### What does .map() return?

The .map() function in JavaScript returns a new array with the same number of elements as the original array, but with each element transformed based on the return value of the callback function passed to the .map() method.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

Use the map function to loop through the numbers array, create a new array of JSX elements with the value of the current item in the array.

We then return a div with the new array of JSX elements. When the component is rendered, React will iterate over the new array and display each element.

### Each list item needs a unique ____.

Key

### What is the purpose of a key?

To identify which items were added or removed. Key give elements in array an identity 

### What is the spread operator?

It is the use of an ellipsi of three dots to expand an iterable object into the list of arguments

### List 4 things that the spread operator can do.

Copying an array, Using math functions, Adding an item to a list, Combining objects, Converting NodeList to an array 

### Give an example of using the spread operator to combine two arrays.

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩


### Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

### Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂


### In the video, what is the first step that the developer does to pass functions between components?



### In your own words, what does the increment function do?

Take a value as an input and return a value that is one more then the input value

### How can you pass a method from a parent component into a child component?

Through props

### How does the child component invoke a method that was passed to it from a parent component?

It can invoke a method that was passed to it from a parent component by calling the method using the props object that was used to pass the method down.


[Home](https://shiloh206.github.io/reading-notes)