# What we will learn

- In Tests We Trust — TDD with Python

- What does the if __name__ =="__main__"

- Recursion

The source of this summary [The first link](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

The source of this summary [The second link](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

The source of this summary [The third link](https://www.geeksforgeeks.org/recursion/)
______________________________________

## In Tests We Trust — TDD with Python


### Unit tests and TDD?

Unit testing: is writing many small tests that each test one very simple function or object behavior.

TDD: is a thinking process that results in unit tests, and “thinking in tests” tends to result in more fine-grained and comprehensive testing, and an easier-to-extend software design.


<img src="https://www.researchgate.net/profile/David-Umphress/publication/254008456/figure/fig1/AS:669952860233745@1536740617691/Fundamental-TDD-Cycle.png" style="height: 300px; width:600px;"/>

Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.

1. Arrange: you need to organize the data needed to execute that piece of code (input)

2. Act: here you will execute the code being tested (exercise the behaviour)

3. Assert: after executing the code, you will check if the result (output) is the same as you were expecting.
______________________________________

## What does the if __name__ =="__main__"do?

**is used to execute some code only if the file was run directly, and not imported.**

**It's boilerplate code that protects users from accidentally invoking the script when they didn't intend to.**


Whenever the Python interpreter reads a source file, it does two things:

it sets a few special variables like __name__, and then

it executes all of the code found in the file.

If your module is the main program, then it will see that __name__ was indeed set to "__main__" and it calls the two functions, printing the strings "Function A" and "Function B 10.0"
______________________________________

## Recursion


### what is Recursion?

**A recursive function is a function defined in terms of itself via self-referential expressions.This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts: base case and recursive case.**


### Recursive Data Structures in Python

**A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure**

<img src="https://cdn.programiz.com/cdn/farfuture/6i17bRQT6hWIqw9JE5rMMyW527g7It_68T7kSzpIplo/mtime:1591262415/sites/tutorial2program/files/python-recursion-function.png" style="height: 300px; width:600px;"/>
