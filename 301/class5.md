### What is the single responsibility principle and how does it apply to components?

A component that does a single thing

### What does it mean to build a ‘static’ version of your application?

Creating an application of entirely static files that can be served directly by a web server

### Once you have a static application, what do you need to add?

Build components that reuse other components and pass data using prop.props

### What are the three questions you can ask to determine if something is state?

Can it change over time? Can it be passed between components? Is it needed to determine the output ?

### How can you identify where state needs to live?

 Look at the different components in your application and identify which ones need to store and manage state.

### What is a “higher-order function”?

Higher-order functions allow us to abstract over actions, not just values. They come in several forms. For example, we can have functions that create new functions.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2 defines a arrow function thats takes one parameter and returns a boolean value


### Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

[Home](https://shiloh206.github.io/reading-notes)
