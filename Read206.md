# What we will learn:

- Object Literals

- Document Object Model

The source of this summary [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F026AD271UG/javascript_and_jquery__interactive_front-end_web_development_.pdf?c=1624715518-be21e32f9bca0681)

______________________________________

## Object Literals

> Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.


> ***Like variables and named functions, properties and methods have a name and a value. In an object that name is called a key***

>***The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function.***

**Examble**
    
     var hote l = {
     name: 'Quay',
     rooms: 40,
     booked : 25,
     checkAvailability: function() {
     return this.rooms - this.booked;
     }
     } ;
 
     var el Name = document .getElementByld('hotelName');
     elName.textContent =hotel .name;
     var elRooms = document.getElementByid{'rooms');
     elRooms.textContent = hotel .checkAvailability(); 

     
______________________________________

## Document Object Model

 > specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. You will hear people call the DOM an Application Programming Interface (API).

### WORKING WITH THE DOM TREE

- Accessing and updating the DOM tree involves two steps:

     1. Locate the node that represents the element you want to work with.

     2. Use its text content, child elements, and attributes. 

**METHODS THAT RETURN A SINGLE ELEMENT NODE:**
  1. getElementByld( ' id ') 
  2. querySel ector( 'css selector') 
  3. getEl ementsByClassName( 'class' )
  4. getEl ementsByTagName( 'tagName')
  5. querySelectorAll ( 'css selector')


**summary:**
> 1. The browser represents the page using a DOM tree. 
 > 2. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
  > 3. You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
  > 4. Whenever a DOM query can return more than one node, it will always return a Nade list.
  > 5. From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
  > 6. An element node can contain multiple text nodes and child elements that are siblings of each other.
  > 7. In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
  > 8. Browsers offer tools for viewing the DOM tree . 

***I understand the whole concept of the reading but it's difficult to summary it here***
