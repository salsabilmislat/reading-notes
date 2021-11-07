# What we will learn

- Python Scope 

- Big O Notation


The source of this summary [The first link](https://realpython.com/python-scope-legb-rule/)

The source of this summary [The second link](https://www.youtube.com/watch?v=5Uqawfl0VHQ)

______________________________________

## Python Scope 

### The LEGB rule

**The Python scope concept is generally presented using a rule which is The LEGB rule** 

### The global scope

**Variables defined in global scope are available everywhere in the application. In a module, a variable declared outside any function is hidden and not available to other modules unless it is explicitly exported.**

### The Nonlocal scope

**Nonlocal variables are used in nested functions whose local scope is not defined. This means that the variable can be neither in the local nor the global scope. Let's see an example of how a nonlocal variable is used in Python. We use nonlocal keywords to create nonlocal variables.**


### Built-in scopes

**When the variable or object is not found in local, global, or enclosing scope, then Python starts looking for it in the built-in scope. Built-in scopes are one of the widest scopes that cover all the reserved keywords. These are easy to call anywhere in the program prior to using them, without the need to define them.**


## Names and Scopes in Python

1. Assignments --->	x = value

2. Import operations ---->	import module or from module import name

3. Function definitions --->	def my_func(): ...

4. Argument definitions in the context of functions	------->   def my_func(arg1, arg2,... argN): ...

5. Class definitions -----> 	class MyClass: ...

**functions and classes are available after you define them using def or class**

### The global Statement

      counter = 0  # A global name
        def update_counter():

          counter = counter + 1

### The nonlocal Statement

        def func():
         var = 100  # A nonlocal variable
           def nested():
             nonlocal var  # Declare var as nonlocal
             var += 100

          nested()
         print(var)

     func()


______________________________________

## Big O Notation

### What Is Big O Notation

**Big O is a formal notation that describes the behaviour of a function when the argument tends towards the maximum input.Big O takes the upper bound. The worst-case results in the worst execution of the algorithm. For our shopping list example, the worst-case is an infinite list.**

### Big O level

**The most basic level for the Big O that's the time complexity component and the space complexity component of it**


### A simple Example to understand it 

**You know you tend to find out that you've reached your space complex in your space limit when the computer runs out of memory but obviously managing that memory can be very important too so Big O notation allows you to do that 
it's a way of quantifying and comparing two different algorithms or seeing how a particular algorithm will respond once you start throwing more data at it**

### Simplifying Big O notation 

1. Different step added

2. Drop constants

3. Different inputs --> shows different variables

4. Drop non-dominate terms