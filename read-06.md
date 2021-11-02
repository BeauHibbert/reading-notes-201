# Problem Domain, Objects, and the DOM
## Problem Domain
Notes from John Sonmez, “Understanding the problem domain is the hardest part of programming
John noticed through his teachings that by “Simply that by taking away the problem domain, or making it so trivial that it is easily understood, I am able to make both teaching and learning easier.” Or in other words, making parts of a problem easy in order to focus on other parts.
Understanding the problem is the most important piece to the equation
Two ways to understand the problem domain better
* Make the problem domain easier
* Get better at understanding the problem domain

# Primitive Values and Object References
Notes from Chris Geelhoed, “What’s the difference between primitive values and object differences in Javascript”

Javascript supports 8 different data types. 7 primitive and objects
* Boolean
* Null
* Undefined
* Number
* BigInt
* String
* Symbol
* Objects

 Primitive values are immutable — they cannot be changed after being created. Object references, however, are mutable and can be changed.
Loose equality is checked using the == operator and strict equality is checked using the === equality

# Chapter 3: Object literals
Notes from Jon Duckett’s JS book
Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on new names.
If a variable is part of an object, it is called a property.
If a function is part of an object, it is called a method.
Properties and functions have a name and a value. In an object, that name is called a key.

# CHAPTER 5: Document object model
Notes from Jon Duckett’s JS book
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how javascript can access and update the contents of a web page while it is in the browser window.
Dom trees have four types of nodes:
* Document nodes
* Element nodes
* Attribute nodes
* Text nodes
Element nodes can be selected by their id or class attributes, by name, or by using CSS selector syntax
Whenever a DOM query can return more than one node, it will always return a NodeList
Browsers offer tools for viewing the DOM tree
