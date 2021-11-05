# What we will learn

- Random Module in Python

- Risk Analysis

- Test Coverage

- Big O Notation


The source of this summary [The first link](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)

The source of this summary [The second link](https://www.edureka.co/blog/risk-analysis-in-software-testing/)

The source of this summary [The third link](https://martinfowler.com/bliki/TestCoverage.html)

The source of this summary [The fourth link](https://www.youtube.com/watch?v=v4cd1O4zkGw)
______________________________________

## Random Module in Python

**The random module provides access to functions that support many operations. Also allows you to generate random numbers. It can be used when making your password database more secure or powering a random page feature of your website ...**

### Random functions

1. Randint 

       we can use the randint function if we wanted a random integer

2. Random

       If we want a larger number, we can multiply it.

3. Choice

       The choice function can be used for choosing a random element from a list.

4. Shuffle
   
        It will place values in random order

5. Randrange

        It will selected element from range(start, stop, step)

______________________________________

## Risk Analysis

*Definition:*

**Risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.**


*Why we use Risk Analysis:*

**It helps the developers and managers to mitigate the risks.**

*Some of the encounter risks:*

- Use of new hardware

- Use of new technology

- Use of new automation tool

- The sequence of code

- Availability of test resources for the application

*These are risks levels:*

- High : The company might face loss.

- Medium : The company may suffer financially but there is a limited risk.

- Low : The company will not face any financial loss.

*Risk Assessment*

**perspectives on risk assessment**


<img src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/08/Picture1-768x422.png" style="height: 300px; width:300px;"/>


*How to perform Risk Analysis*

- Searching the risk

- Analyzing the impact of each individual risk

- Measures for the risk identified

______________________________________

## Test Coverage

**Test coverage is a useful tool for finding untested parts of a codebase. Certainly low coverage numbers, say below half, are a sign of trouble. But high numbers don't necessarily mean much, and lead to ignorance-promoting dashboards.**

______________________________________

## Big O Notation

is an essentially an equation that describes how to run scales with respect to some input variables.

1. O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

2. O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.

3. O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set.


**There is four rules to explain the Big O**

1. Different step added

2. Drop constants

3. Different inputs --> shows different variables

4. Drop non-dominate terms
