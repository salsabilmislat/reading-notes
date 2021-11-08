# What we will learn

- List Comprehensions 

- Primer on Python Decorators


The source of this summary [The first link](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

The source of this summary [The second link](https://realpython.com/primer-on-python-decorators/)

______________________________________

## List Comprehensions

**List comprehension is an elegant way to define and create lists based on existing lists.**

**List comprehension is generally more compact and faster than normal functions and loops for creating list. However, we should avoid writing very long list comprehensions in one line to ensure that code is user-friendly.**

### Syntax

    my_new_list = [ expression for item in list ]

### Create a List with range()

        digits = [x for x in range(10)]

        print(digits)

        [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

### Multiplying Parts of a List

        multiples_of_three = [ x*3 for x in range(10) ]

        print(multiples_of_three)

        [0, 3, 6, 9, 12, 15, 18, 21, 24, 27]

______________________________________

## Primer on Python Decorators

**Allows a user to add new functionality to an existing object without modifying its structure. Decorators are usually called before the definition of a function you want to decorate.**


### Assigning Functions to Variables

        def plus_one(number):
            return number + 1

    add_one = plus_one
    add_one(5)

### Defining Functions Inside other Functions

    def plus_one(number):
        def add_one(number):
            return number + 1


        result = add_one(number)
        return result
    plus_one(4)
