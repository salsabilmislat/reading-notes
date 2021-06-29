# What we will learn

 - Forms

 - Lists, Tables & Forms

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## Forms

  >HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.

Form controls live inside a [form] element. This element should always carry the action attribute and will usually have a method and id attribute too.

1. Action : Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

2. Method : Forms can be sent using one of two methods: get or post.
      
      - With the get method, the values from the form are added to the end of the URL specified in the action attribute.

      - With the post method the values are sent in what are known as HTTP headers.

3. The [input] element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
        
    1. type="text"
       - name
       - size
       - maxlength
    2. type="password"   
        - name
       - size
       - maxlength
    3. The [textarea] element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag. 
    4. type="radio"
       - name
       - value
       - checked
    5. type="checkbox"
        - name
       - value
       - checked
    6. type="submit"
        - name
       - value

______________________________________

 ## Lists, Tables & Forms



1. list-style-image
    > You can specify an image to act as a bullet point using the list-style-image property.

2. list-style-position
    >Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points.
     - outside The marker sits to the left of the block of text. 
     - inside The marker sits inside the box of text (which is indented).


3. Table Properties
    - width to set the width of the table
    - padding to set the space between the border of each table cell and its content
    - text-transform to convert the content of the table headers to uppercase
    - letter-spacing, font-size to add additional styling to the content of the table headers
    - border-top, border-bottom to set borders above and below the table headers
    - text-align to align the writing to the left of some table cells and to the right of the others
    - background-color to change the background color of the alternating table rows
    - :hover to highlight a table row when a user's mouse goes over it

______________________________________

## What we will learn part 2

- ***Events***

The source of this summary [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F026AD271UG/javascript_and_jquery__interactive_front-end_web_development_.pdf?c=1624715518-be21e32f9bca0681)

______________________________________

## Events

THREE WAYS TO BIND AN EVENT TO AN ELEMENT :
1. HTML EVENT HANDLERS 
    >HTML EVENT HANDLER ATTRIBUTES (DO NOT USE)
2. TRADITIONAL DOM EVENT HANDLERS
    >All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler. 
3. DOM LEVEL 2 EVENT LISTENERS


> Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).

> Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

> When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.

> You can use event delegation to monitor for events that happen on all of the children of an element.

> The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events. 