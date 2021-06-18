#  What we will learn part 1: 

- HTML structure
- Extra markup
- HTML5 layout
- Process & design

The source of this sammary [the Duckett HTML book](https://wtf.tw/ref/duckett.pdf)
__________

## HTML structure
**as duckett said:**
>Many web pages act like electronic versions of Newspapers,
insurance forms, shop catalogues... 


   **As he said when we are going to build a web pages it want be different of Newspapers all we need is to separate out the text to give it structure. Each topic might have a new paragraph, and each section can have a heading to describe what it covers**


 #### ***HTML Uses Elements to Describe the Structure of Pages***
+ ***Element of HTML***
   ![element](https://www.codeinbook.com/images/element-and-tag-graphics.png )

***Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.***

 ***For the Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.***


______________________

## Extra markup
***Duckett said:***
>You may know that HTML stands for HyperText Markup Language. The HyperText part refers to the fact that HTML allows you to create links that allow visitors to move from one page to another quickly and easily. A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of a document. If you think of a web page, we add code around the original text we want to display and the browser then uses the code to display the page correctly. So the tags we add are the markup.

______
 ***DOCTYPEs :***

  + **In mention of that about HTML versions, Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included)**


 ***Comments in HTML:***
 + **your code that will not be visible in the user's browser**
 
 ***E.P: <!-- comment goes here -->***

***ID Attribute:***
  + **the id attribute. It is used to uniquely identify that element from other elements on the page** 

  ***E.P: <p id="pullquote">text </p>***
  
***Class attribute:***
  + **Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page.**

  ***E.P: <p class="important">text </p>***

***Block Elements:***
  
  + **Examples of block elements are <h1>, <p>, <ul>, and <li>.**

***inline elements***
  
  + **Examples of inline elements are <a>, <b>, <em>, and <img>**

***The <div> element:*** 
  + **allows you to group a set of elements together in one block-level box.**

***The <span> element:***
  + **acts like an inline equivalent of the <div> element**

***IFrames:***
  + **An iframe is like a little window that has been cut into your page is to embed a Google Map into a page**

_______________
## HTML5 layout

***HTML5 introduces a new set of elements that allow you to divide up the parts of a page.***


***New Html5 Layout Elements:***
 + **Headers & Footers**

 *<header> <footer>*

 + **Navigation**

 *<nav>*

 + **The <article> element**

  *acts as a container for any section of a page that could stand alone and potentially be syndicated*

 + **The <section> element groups**

  *related content together, and typically each section would have its own heading*

______________________
## Process & design

***Duckett give us small summary of this topic:***

>It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return. Also design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them. For sure wireframes allow you to organize the information that will need to go on each page.

___________________________________

#  What we will learn part 2:
 - The ABC of Programming

The source of this sammary [the Duckett JS book](https://slack-files.com/files-pri-safe/TNGRRLUMA-F0263V3S9J4/javascript_and_jquery__interactive_front-end_web_development_.pdf?c=1624027087-dd32dd0afa631c65)
__________
 ***What is a script?***

 **A script is a series of instructions that a computer can follow to achieve a goal,To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.**

**Things to know Computers solve problems programmatically; they follow series of instructions, one after another. The type of instructions they need are often different to the type of instructions you might give to another human.**

  ***How the computer fit in with the world around them?***
 
 **First: Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an object's properties.** 

 **Second: to make web page interactive, you write code that uses the browser's model of the web page**

***How to write script for a web page?***

 **you can link it in When you want to use JavaScript with a web page you use the HTML <script> element to tell the browser it is coming across a script. Its src attribute tells people where the JavaScript file is stored**

