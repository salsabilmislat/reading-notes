# What we will learn

- Pain vs. Suffering

- A beginner's guide to Big O Notation

- Names and Values in Python

The source of this summary [The first link](https://codefellows.github.io/code-401-python-guide/curriculum/class-01/notes/pain_suffering)

The source of this summary [The second link](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation)
______________________________________

## Pain vs. Suffering

**so in general Pain is the feeling of unpleasant physical sensations or emotions. Suffering is the struggle, denial, worry, regret, indignation, complaining, and self-pity wrapped around pain. To let go of suffering, you must first allow and accept the pain**

**The pain of growth by doing something new** 

1. You’ll lose sleep, you’ll forget to work out, and you’ll feel exhausted all while being filled with information day after day. 

2. You’ll be pushed physically, and while sitting in a chair and staring at your screen isn’t the most strenuous exercise in the world, the consecutive hours of it will take its toll.

3. You’ll have to research for hours on end, fleshing out the skeleton that we discuss in class, piling information on top of application so that you can reach your goals.


> All growth comes with some degree of pain, as it pulls you out of your comfort zone. The greater the growth, the greater the pain. But pain in the service of growth is a good thing, as long as that pain is what’s necessary to achieve the growth that you’re aiming for. And even better than that, this pain is only temporary. It’s what will launch you forward into the next phase of your life.

______________________________________

## A beginner's guide to Big O Notation

**Big O notation is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity. ... In computer science, big O notation is used to classify algorithms according to how their run time or space requirements grow as the input size grows. It is a nice welcome for 401**

<img src="https://cdn-media-1.freecodecamp.org/images/1*KfZYFUT2OKfjekJlCeYvuQ.jpeg" style="height: 300px; width:600px;"/>


1. O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

2. O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.

3. O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set.

4. O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set.

______________________________________

## Names and Values in Python

**Think of a variable as a name attached to a particular object. In Python, variables need not be declared or defined in advance, as is the case in many other programming languages. To create a variable, you just assign it a value and then start using it. Assignment is done with a single equals sign (=)**

1. *First thing to know is Names refer to values.*

If we says name=salsabil  print(name)  we’ll get the value salsabil

2. *Many names can refer to one value*

x=100

y=x

3. *Names are reassigned independently*

x=100

y=x

x=50

4. *Values live until no references*
Python keeps track of how many references each value has

5. Variables in Python are not subject to this restriction. In Python, a variable may be assigned a value of one type and then later re-assigned a value of a different type 

m=25.5

m="Now it is a string"

print(m) -----> Now it is a string (output)
