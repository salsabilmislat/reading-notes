# What we will learn part 1

- Links

- Layout

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## HTML Lists

  >they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

***Writing Links***

    [a] element Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.

1. Linking to Other Sites

       [a href="http://www.empireonline.com ]Empire[/a]

2. Linking to Other Pages on the Same Site

       [a href="about-us.html"]About[/a]

3. Opening Links in a New Window

       [a href="http://www.imdb.com" target="_blank"]

4. Linking to a Specific Part of the Same Page

        by the # symbol after declare an id for the part
        [a href="#arc_shot"]the part[/a]

## Layout

   >control where each element sits on a page and how to create attractive page layouts

1. *Normal Flow (position:static)*

     > each block-level element sits on top of the next one
     I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.

2. *Fixed positioning*

     > It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place

3. *Floating Elements (float)*

     > The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

## What we will learn part 2

- ***Functions, Methods, and Objects***

The source of this summary [the Duckett JS book](file:///C:/Users/STUDENT/Downloads/JavaScript%20and%20JQuery_%20Interactive%20Front-End%20Web%20Development_.pdf)

______________________________________

## Functions, Methods, and Objects

> Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

***how to write a function***

      function name(parameter1, parameter2, parameter3) {
     // code to be executed
     }

## pair programming

The source of this summary [pair programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

______________________________________

> While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard.The Navigator uses their words to guide the Driver but does not provide any direct input to the computer.

***Things make you use pair programming***

1. Greater efficiency

    > when two people focus on the same code base, it is easier to catch mistakes in the making.

2. Engaged collaboration

    > two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.

3. Learning from fellow students

    > working with a teammate can expose developers to techniques they otherwise would not have thought of.

4. Social skills

   > can also help programmers develop their interpersonal skills.

5. Job interview readiness

    > companies can get a better feel for how an applicant will fit into the team and their collaboration style.

6. Work environment readiness

    > Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.
