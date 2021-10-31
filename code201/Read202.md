# What we will learn part 1

- HTML Text

- Introducing CSS

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## HTML Text

>When  we creating a web page, we must add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

***Structural markup***

1. heading: represented by  [h1, h2, h3... h6]

2. paragraph: represented by [p]

3. Bold & Italic: represented by [(b) for bold text , (i) for italic text ]

4. Line Breaks & Horizontal Rules: represented by [(br /) break line , (hr /) horizontal rule ]

***Semantic Markup***
*There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.*

1. Strong & Emphasis: represented by [(strong) content has strong importance , (em) indicates emphasis that subtly changes the meaning of a sentence ]

2. Quotations: represented by [(blockquote) used for longer quotes that take up an entire paragraph , (q) shorter quotes that sit within a paragraph ]

3. Changes to Content: represented by [(ins) to show content that has been inserted into a document, (del)  show text that has been deleted from it, (s) something that is no longer accurate or relevant (but that should not be deleted)]

______________________________________

## Introducing CSS

***Cascading Style Sheets allows you to create great-looking web pages ,so CSS allows you to create rules that specify how the content of an element should appear***

***Css syntax:***
 h1 {color: red;}

   ***How to add css in HTML file***

1. *external css*

         [link rel="stylesheet" href="mystyle.css"]

2. *inline css*

         [h1 style="color:blue;text-align:center;" This is a heading][/h1>]
  
3. *internal css*

         [style]
         body {
         background-color: linen;
         }

         h1 {
         color: maroon;
         margin-left: 40px;
         }

         [/style]

***CSS Selectors type***

- Universal Selector [ * {} Targets all elements on the page]

- Class Selector [ .note {} Targets any element whose class attribute has a value of note ]

- ID Selector [ #introduction {} Targets the element whose id attribute has a value of introduction ]

______________________________________

## What we will learn part 2

- Basic JavaScript Instructions

- Decisions and Loops

The source of this summary [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F026AD271UG/javascript_and_jquery__interactive_front-end_web_development_.pdf?c=1624715518-be21e32f9bca0681)

______________________________________

## Basic JavaScript Instructions

    *A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon*

***The Data type for JS***

 1. ***Number***
     *represents numeric values e.g. 100.*

 2. ***String***

     *represents sequence of characters e.g. "hello" ,'1'*

 3. ***Boolean***

     *represents boolean value either false or true*

 4. ***operators***

       1. *arithmetic operators : -*  + / *

       2. *assignment operators : where i can assign variables to their value (=)*

***pop up boxes type***

1. *alert box*

2. *prompt box*

______________________________________

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

***conditional IF... Else statement***

    EXAMPLE

          if ("cat" === "dog") {
         var outcome = "if block";
         } else {
           var outcome = "else block";
         }
         outcome;

    OUTPUT
     "if block"
