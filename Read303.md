# What we will learn

 - Lists and Keys

 - The Spread Operator
 
 - How to Pass Functions between Components

The source of this summary [The first link](https://reactjs.org/docs/lists-and-keys.html)

The source of this summary [The second link](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

The source of this summary [The third link](https://www.youtube.com/watch?v=c05OL7XbwXU)
______________________________________

## Lists and Keys

**What does .map() return?**

it will return an array with a new variable of it 

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

using curly braces {} and after that render it in to the DOM using HTML element.

**Each list item needs a unique key.**

**What is the purpose of a key?**

it help  the React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.


______________________________________

## The Spread Operator

**What is the spread operator?**

is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.Also the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

**List 4 things that the spread operator can do**

1. Copying an array

2. Concatenating or combining arrays

3. Using Math functions

4. Adding an item to a list

**Give an example of using the spread operator to combine two arrays.**
***It called array concatennation***
> const myArray = [1,2,3]
const yourArray = [4,5,6]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray)



 **Give an example of using the spread operator to add a new item to an array**

 > const fewNumber = [1,2,3]
const fewMoreNumber = [4, 5, ...fewNumber]

**Give an example of using the spread operator to combine two objects into one**

> const objectOne = {day: 6}
const objectTwo = {month: 12}
const objectThree = {...objectOne, ...objectTwo, year: 2005}

______________________________________

## How to Pass Functions between Components

**In the video, what is the first step that the developer does to pass functions between components?**

creat an object refers to the the function that i want to use 

**In your own words, what does the increment function do?**

it increase the number of how much time we press on the button by check out the name that have been updated .

**How can you pass a method from a parent component into a child component?**
by use it as props object backup to the parent component to a child component

**How does the child component invoke a method that was passed to it from a parent component?**

this.props.parent(this.props.the object)


## Things I want to know more about

to have a real example for how to Pass Functions between Components