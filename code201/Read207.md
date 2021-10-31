# What we will learn

 - Tables

 - Functions, Methods, and Objects

The source of this summary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

______________________________________

## Tables

  > A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

1. The [table] element is used to create a table. The contents of the table are written out row by row.

2. You indicate the start of each row using the opening [tr] tag. (The tr stands for table row.)

3. Each cell of a table is represented using a [td] element. (The td stands for table data.)

4. The [th] element is used just like the [td] element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

5. The colspan attribute can be used on a [th] or [td] element and indicates how many columns that cell should run across.

6. The rowspan attribute can be used on a [th] or [td] element to indicate how many rows a cell should span down the table.

### For Long Tables

1. The headings of the table should sit inside the [thead] element.

2. The body should sit inside the [tbody] element. 

3. The footer belongs inside the [tfoot] element.


## What we will learn part 2

- ***Functions, Methods, and Objects***

The source of this summary [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F026AD271UG/javascript_and_jquery__interactive_front-end_web_development_.pdf?c=1624715518-be21e32f9bca0681)

______________________________________

**we can create new objects newobject()**

**To delete a property, you use the keyword delete, and then use dot notation to identify the property or method you want to remove from the object.**

- **ARRAYS**
 > Arrays can store multiple pieces of information. Each piece of information is separated by a comma. The order of the values is important because items in an array are assigned a number (called an index). 

  > An object model is a group of objects, each of which represent related things from the real world. Together they form a model of something larger.

 > The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser. 

 > Whenever you have a value that is a string, you can use the properties and methods of the String object on that value. 


>  1. Functions allow you to group a set of related statements together that represent a single task. 
> 2. Functions can take parameters (informatiorJ required to do their job) and may return a value.
> 3. An object is a series of variables and functions that represent something from the world around you.
> 4. In an object, variables are known as properties of the object; functions are known as methods of the object.
>5.  Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
> 6. JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
> 7. Arrays and objects can be used to create complex data sets (and both can contain the other). 