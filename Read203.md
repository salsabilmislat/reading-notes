# What we will learn part 1

- Lists

- Boxes

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## HTML Lists

Three different types of list:

1. Ordered listsare: lists where each item in the list is numbered.
    represented by [ol] Each item in the list is placed between an opening [li] tag and a closing [/li] tag

2. Unordered Lists: lists that begin with a bullet point (rather than characters that indicate order).
   represented by [ul] Each item in the list is placed between an opening [li] tag and a closing [/li] tag

3. Definition lists: made up of a set of terms along with thedefinitions for each of those terms.
   represented by [dl] you will usually see pairs of [dt] the definition term and [dd]  This is used to contain the definition.

4. Nested lists: You can put a second list inside an [li] element to create a sublist or nested list.

## CSS Boxes

1. we can Control the dimensions of boxes such as : width, height by  pixels

2. Limiting Width: min-width, max-width

     >Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

3. Limiting Height: min-height, max-height you also can controling the height as the width.

4. overflow:

     > The overflow property tells the browser what to do if the content contained within a box is larger than the box itself.It can have one of two values: hidden, scroll.

5. >You can also control the borders, margin and padding for each box with CSS.

6. Change Inline/Block

    - inline This causes a block-level element to act like an inline element.

    - block This causes an inline element to act like a block-level element.

    - inline-block This causes a block-level element to flow like an inline element, while retaining other features of a block-level element.

    - none This hides an element from the page.

___________________________;

## What we will learn part 2

- Basic JavaScript Instructions

- Decisions and Loops

The source of this summary [the Duckett JS book](file:///C:/Users/STUDENT/Downloads/JavaScript%20and%20JQuery_%20Interactive%20Front-End%20Web%20Development_.pdf)

___________________;

## Basic JavaScript Instructions

- >An array is a special type of variable. It doesn't just store one value; it stores a list of values you can store a string, a number and a Boolean all in the same array.
colors= ['white','black','custom'];

___________________;

## Decisions and Loops

### we can use comparison operators

1. == is Equal to

2. != is not Equal to

3. (>) is greater than

4. (<) is less than

5. 11 <= less than or equal to

6. 10 >= greater than or equal to

### we can use logical operators

1. && logical and

2. || logical or

3. ! logical not

***conditional IF... Else statment***

    EXAMPLE

if ("cat" === "dog") {
      var outcome = "if block";
} else {
      var outcome = "else block";
}
outcome;

    OUTPUT
"if block"

***SWITCH STATEMENTS***
   >starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

     EXAMPLE

    switch (key) {
    case value:
        
        break;

    default:
        break;}

***for loop***

    countering as a condition for a specific number of times loop repeats until a specified condition evaluates to false.
  
 How a for statement looks

     for ([initialExpression]; [conditionExpression]; [incrementExpression])
     {
         statement;
     }

***while loop***

      statement executes its statements as long as a specified condition evaluates to true

     How a while statement looks

     while (condition)

     {
      statement;
     }
  
***break statement***

     statement to terminate a loop

         How a while statement looks

              break;

***DO WHILE LOOPS***

- > The key difference betweena while loop and a do while loop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condition is met.

      How a while statement looks
         do {
              statement;
           } while (condition);
