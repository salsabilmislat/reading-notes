# What we will learn

- Layout

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## HTML Layout

>control where each element sits on a page and how to create attractive page layouts

***Block-level elements start on a new line Examples include: [h1] [p] [ul] [li]***

***Inline elements flow in between surrounding text Examples include: [img] [b] [i]***

>If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

1. *Normal Flow (position:static)*

     > each block-level element sits on top of the next one
     I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.

2. *Fixed positioning*

     > It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place

3. *Floating Elements (float)*

     > The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

4. *Relative Positioning*

    >This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

5. *Absolute positioning*

    > This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

***You can include multiple CSS files in one page.***
