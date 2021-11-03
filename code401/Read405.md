# What we will learn

- Big O

- Linked Lists



The source of this summary [The first link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)

The source of this summary [The second link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

______________________________________

## Linked Lists

**A linked list is a sequence of data elements, which are connected together via links. Each data element contains a connection to another data element in form of a pointer**

### characteristic of linked lists

1. linear data structures:

which means that there is a sequence and an order to how they are constructed and traversed.

2. non-linear data structures:

items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially


### Memory management

**Python don’t have to think about how much memory an array uses when we write our code on a day to day basis because there are several layers of abstraction that end up with us not having to worry about memory allocation at all.**

in other word python do not care about memory allocation for the array.

Array need a contiguous  block of memory

Linked list don not need to be contiguous in memory. it can grow dynamically 



### Lists for all shapes and sizes

**type of linked lists**

1. Singly linked lists

2. doubly linked list

3. circular linked list

______________________________________

## Big O

**Big O notation is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity.... In computer science, big O notation is used to classify algorithms according to how their run time or space requirements grow as the input size grows.**

<img src="https://cdn-media-1.freecodecamp.org/images/1*KfZYFUT2OKfjekJlCeYvuQ.jpeg" style="height: 300px; width:600px;"/>

### Some Of Orders of Growth


Logarithmic Complexity represents a function that sees a decrease in the rate of complexity growth, the greater our value of n.

Linearithmic functions grow faster than input size n, but not by much



1. O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

2. O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.

3. O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set.

4. O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set.