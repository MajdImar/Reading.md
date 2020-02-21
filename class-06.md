
# Article : Understanding The Problem Domain Is The Hardest Part Of Programming:
-Programming is easy if you understand the problem domain.
- by taking away the problem domain, or making it so trivial that it is easily understood, I am able to make both teaching and learning easier.
1. Make the problem domain easier.
2. Get better at understanding the problem domain.
* **You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem**.
# Chapter 3: “Object Literals” :
- Objects group together : a set of variables and functions to create a model of a something you would recognize from the real world.
-  VARIABLES become PROPERTIES.
- FUNCTIONS BECOME  METHODS.
• HTML uses attribute names and values. 
• CSS uses property names and values. 
• In JavaScript Variables have a name and you can assign them a value of a string, number, or Boolean.
# Chapter 5: “Document Object Model” :
- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window
- Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes
- NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT .


- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 
- Whenever a DOM query can return more than one node, it will always return a Nade list .
* From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 
- An element node can contain multiple text nodes and child elements that are siblings of each other. 
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 
-Browsers offer tools for viewing the DOM tree . 
