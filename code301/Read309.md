# What we will learn

- FUNCTIONAL PROGRAMMING

- Node JS

The source of this summary [The first link](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

The source of this summary [The second link](https://www.youtube.com/watch?v=xHLd36QoS4k)

______________________________________

## FUNCTIONAL PROGRAMMING

**What is functional programming?**

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

**What is a pure function and how do we know if something is a pure function?**

The first fundamental concept we learn when we want to understand functional programming , It returns the same result if given the same arguments and It does not cause any observable side effects.

**What are the benefits of a pure function?**

The code’s definitely easier to test. We don’t need to mock anything, also Pure functions are stable, consistent, and predictable

**What is immutability?**

Unchanging over time or unable to be changed.
its state cannot change after it’s created

**What is Referential transparency?**

if a function consistently yields the same result for the same input.

pure functions + immutable data = referential transparency
______________________________________

## Node JS

**What is a module?**

Modules are the blocks of encapsulated code that communicates with an external application on the basis of their related functionality. Modules can be a single file or a collection of multiples files/folders

**What does the word ‘require’ do?**

It allows you to include modules in your app. You can add built-in core Node.js modules, community-based modules (node_modules), and local modules too.it reads a JavaScript file, executes the file, and then proceeds to return the exports object.

**How do we bring another module into the file the we are working in?**

we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation

**What do we have to do to make a module available?**

Export the module.
