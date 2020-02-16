
# Summary Html :
 # **Introduction** :
1. The book has three parts:
-  HtML :is used to create web pages.
- css : enable you to control the styling and layout of web pages.
2.Different ways in which people access the web and clarify some terminology:
- Browsers :People access websites using software called a web browser. Popular examples include Firefox, Internet Explorer, Safari, Chrome, and Opera.
- weB servers : Web servers are special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them.
- DevIces: including desktop computers, laptops, tablets, and mobile phones.
- Screen readers : are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.
3. How weBsItes are created :
- All websites use HTML and CSS, but content management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.
-  more complex sites  may use a database to store data, and programming languages such as PHP, ASP.Net, Java, or Ruby on the web server.
4. How the web works:
- The web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.
- steps:
1.When you connect to the web, you do so via an Internet Service Provider (ISP).
2.Your computer contacts a network of servers called Domain Name System (DNS) server.
3.The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested.
4.The web server then sends the page you requested back to your web browser.
- **web server** : is a computer that is constantly connected to the web, and is set up especially to send web pages to users.
# **chapter1 Structure** :
* HtmL deScribeS tHe Structure of PageS :HTML element tells the browser something about the information that sits between its opening and closing tags.
* Tags act like containers. They tell you something about the information that lies between their opening and closing tags.
* attributeS teLL uS more about eLementS :name and a value, separated by an equals sign.
* Anything written between the <title> tags will appear in the title bar (or tabs) at the top of the browser window.
 # **chapter8 Extra Markup** :
  - thE Evolution of htMl :
  (htMl 4 rElEasEd 1997, xhtMl 1.0 rElEasEd 2000,htMl5 rElEasEd 2000)
  - DOCTYPES tell browsers which version of HTML you are using .
- You can add comments to your code between <!-- and -->  markers  .
  - The  id and class attributes allow you to identify the particular elements,s known as a **global attribute** because it can be used on any element . 
  - Some elements will always appear to start on a new line in the browser window. These are known as block level elements.
  
  - Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.

- span :
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
2. Contain a number of inline elements

- The  div and span elements allow you to group blocklevel and inline elements together.
- iframes : cut windows into your web pages through which other pages can be displayed.
- There are a few attributes that you will need to know to use it:
(src,height,width)
- scrolling ,frameborder :attributes will not be supported in HTML5.
- seamless :in HTML5, a new attribute called seamless can be applied to an iframe where scrollbars are not desired. 
The meta element is an empty element so it does not have a closing tag. It uses attributes to carry the information.
- The   meta tag allows you to supply all kinds of information about your web page.
- Escape characters are used to include special  characters in your pages .
- #**chapter17 HTML5 Layout** :
- The new HTML5 elements indicate the purpose of different parts of a web page and help to describeits structure.
- The new elements provide clearer code (compared with using multiple div elements).
- Older browsers that do not understand HTML5  elements need to be told which elements areblock-level elements.
- hgroup:The purpose of the hgroup element is to group together a set of one or more h1 through h6 elements so that they are treated as one single heading.
  - Figures : It can be used to contain any content that is referenced from the main flow of an article (not just images). 
  - The figure element should also contain a <figcaption> element which provides a text decription for the content of the figure element. 
  - The aside element has two purposes, depending on whether it is inside an article element or not.
1. When the aside element is used inside an article element, it should contain information that is related to the article but not essential to its overall meaning. 
  2. When the <aside> element is used outside of an article element, it acts as a container for content that is related to the entire page
- To make HTML5 elements work in Internet Explorer 8(and older versions of IE), extra JavaScript is needed, which is available free from Google.
- **chapter18 Process & Design** :
  - It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
  - Site maps allow you to plan the structure of a site.
  - To help you decide what information should go on each page, you can use a technique called card sorting.
  - Wireframes allow you to organize the information that   will need to go on each page,It shows the hierarchy of the information and how much space it might require.

  - Design is about communication. Visual hierarchy helps   visitors understand what you are trying to tell them.
  - designer needs to organize and prioritize the information to communicate their message and help users find what they're looking for.
- Grouping together related content into blocks or chunks makes the page look simpler (and easier to understand). 
  - You can differentiate between pieces of information   using size, color, and style.
  - You can use grouping and similarity to help simplify  the information you present.
  - Grouping related pieces of information together can make a design easier to comprehend
 - visual hierarchy refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.
 - Designing navigation :helps people find where they want to go and also helps them understand what your site is about and how it is organized.


   # **JS Chapter 1: “The ABC of Programming** :
  - JavaScript can be used in browsers to make websites more interactive, interesting, and user-friendly.
  - A script : is a series of instructions that the computer can follow,in order to achieve a goal. 
  - To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. 
   Follow these steps :
   1: DEFINE THE GOAL  2.2: DESIGN THE SCRIPT 3.3: CODE EACH STEP 
 - Each time the script runs, it might only use a subset of all the instructions. 
  - Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
  - Computers solve problems programmatically; they follow series of instructions, one after another
  - To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
  - The flowcharts show the paths between each step.
  - An event is the computer's way of sticking up its hand to say, "Hey, this just happened!" .
  - The code for a method can contain lots of instructions that together represent one task. 
  - Programmers choose which events they respond to. When a specific event happens, that event can be used to trigger a specific section of the code. 
  - WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS .
  - Using the document object, you can access and change what content users see on the page and respond to how they interact with it.
  - All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow. 
  - It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.
  - The HTML script element is used in HTML pages to tell the browser to load the JavaScript file (rather like the link element can be used to load a CSS file). 
 - LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE(ou use the HTML script element to tell the browser it is coming across a script) 
  - If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 
  


  
  

 







