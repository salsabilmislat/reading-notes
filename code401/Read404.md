# What we will learn

- Classes and Objects

- Thinking Recursively

- Python Testing with pytest: Fixtures and Coverage


The source of this summary [The first link](https://www.learnpython.org/en/Classes_and_Objects)

The source of this summary [The second link](https://realpython.com/python-thinking-recursively/)

The source of this summary [The third link](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)

______________________________________

## Classes and Objects

**Classes are template to create an objects.Objects have member variables and have behaviour associated with them. In python a class is created by the keyword class. An object is created using the constructor of the class. This object will then be called the instance of the class**

### an example 

    class MyClass:
      variable = "blah"

       def function(self):
         print("This is a message inside the class.")

    myobjectx = MyClass()

 ### Accessing Object Variables/Accessing Object Functions

 in order to access the variable inside the object we write 
 
     myobjectx.variable so the output will be (blah)

we can also assign another value to a variable in the same object and the variable of it will have new value add to it 

in order to access a function inside the object we write

        myobjectx.function()

______________________________________

## Thinking Recursively

### Recursive Data Structures in Python

**A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure . In another words Objects can have other objects as attribute values. When an object of some class has an attribute value of that same class, the result is a recursive data structure.**

### Maintaining State

To maintain state during recursion you have two ways 
Keep the state in global scope or thread the state through each recursive call so that the current state is part of the current call’s execution context


### Naive Recursion is Naive

It is the a Fibonacci sequence

 which is the integer sequence of 0, 1, 1, 2, 3, 5, 8....

The first two terms are 0 and 1. All other terms are obtained by adding the preceding two terms. This means to say the nth term is the sum of (n-1)th and (n-2)th term.

______________________________________

## Python Testing with pytest: Fixtures and Coverage


### pytest is a software test framework, which means pytest is a command-line tool that automatically finds tests you've written, runs the tests, and reports the results.


## Fixtures

pytest fixtures are functions attached to the tests which run before the test function is executed. Fixtures are a set of resources that have to be set up before and cleaned up once the Selenium test automation execution is completed

pytest fixture function is automatically called by the pytest framework when the name of the argument and the fixture is the same. 

A function is marked as fixture using the following marker:

    @pytest.fixture



## Coverage

code coverage doesn't mean that my code lacks bugs. But the fact that it has been run at least once. so we should provide an argument to --cov, specifying which program(s) you want to test. And, you should indicate the directory into which the report should be written it will show you where your program still lacks coverage
