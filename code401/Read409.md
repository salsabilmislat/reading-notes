# What we will learn

- Dunder Methods 

- probability


The source of this summary [The first link](https://dbader.org/blog/python-dunder-methods)

The source of this summary [The second link](https://www.dataquest.io/blog/basic-statistics-in-python-probability/)

______________________________________

## Dunder Methods 

**Dunder methods having two prefix and suffix underscores in the method name. Dunder here means “Double Under (Underscores)”. These are commonly used for operator overloading.**


### Object Initialization: __init__:

Constructors are used to initialize the object's state. The task of constructors is to initialize(assign values) to the data members of the class when an object of class is created.

### Object Representation: 
    __str__, __repr__


**__repr__ is a special method used to represent a class's objects as a string**


**The repr() built-in function. You can define your own string representation of your class objects using the __repr__ method. Special methods are a set of predefined methods used to enrich your classes.**


**The __str__ method in Python represents the class objects as a string – it can be used for classes. The __str__ method should be defined in a way that is easy to read and outputs all the members of the class. This method is also used as a debugging tool when the members of a class need to be checked.**

______________________________________

## probability

### what is probability

**The probability of an event A is the number of ways event A can occur divided by the total number of possible outcomes. To calculate the chance of an event happening, we also need to consider all the other events that can occur.**


### From statistics to probability

**Probability is the measure of the likelihood that an event will occur in a Random Experiment. Probability is quantified as a number between 0 and 1, where, loosely speaking, 0 indicates impossibility and 1 indicates certainty. The higher the probability of an event, the more likely it is that the event will occur.**

<img src="https://i.imgur.com/GtbawRt.jpg" style="height: 300px; width:600px;"/>

### Revisiting the normal

**It could contain two factors:**

1. the Central Limit Theorem 

     the Central Limit Theorem suggests that we can hone in on the theoretical ideal given by probability, even when we don’t know the true probability. Central Limit Theorem lets us know that the average of many trials means will approach the true mean

2. the Three Sigma Rule.

    the Three Sigma Rule will tell us how much the data will be spread out around this mean.Although the Three Sigma rule is a statement of how much of your data falls within known values

