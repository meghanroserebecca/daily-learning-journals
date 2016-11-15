# LJ Code 201 - Day 6

<p>**Variables are a place to store things AND also give semantic meaning to your code!** Refer to the function assignment - I declared variables, but I could have skipped variables and just done the return part as return [a + b, 'the sum of ' + a + (etc.)'] and that would have saved a couple lines of code and been totally fine, but it wouldn't have been as clear.</p>

<p>**logging out** (console.log()) every step of code can help us to understand better what is going on and what is going wrong!</p>

<p>If you're not sure exactly how to get where you're going in a function,  break down each expression in the function to its own variable.</p>

<p>**Objects** are what we use to model constructions we come up with ourselves. We get to give something a shape and behaviors.<br />
-->*Initialize* objects with curly braces!<br />
-->Normally we want to use dot notation when creating objects! Not brackets!<br />
-->At its core, an object is just a series of name/value pairs. **keys** are ***strings*** and **properties/values** are anything you want them to be.<br /></p>

<p>**Functions** that are part of **Objects** are called **methods**</p>

<p>We have a specialized keyword called **"this"** that goes in functions that are in objects..it refers to the object itself! so "this" inside an object called cookieStore is itself referring to cookieStore object.</p>

<p>**DOM manipulation** <br />
DOM = document object model <br />
obviously a javascript object called cookieStore is not a literal physical cookie store. It is a javascript object. So the "document" is an html document that we are modeling or representing in javascript. The main ways to interact with the DOM are: <ul> <li> the method document.getElementById - this gets us the object we want from the html so we can manipulate it.</li> <li>In our javascript we then create a new html node that we can work with. We do this with document.createElement('...'). We modify the element or add new elements to it in javascript and then reattach it to the html document.</li><li>Text content (e.g., topBar.textContent('...'') lets us make text modifications to a node.</li><li>Append Child is how we make an element a child of another node. We call it as a method of the element we are adding another element to (e.g., topBar.appendChild(newHeading))</li></ul>

Difference between IDs and classes: (1)We can have multiple of the same class, but only one of a particular ID. (2) Usually we insert IDs into html documents in order to get them into the script. Classes we use primarily for styling.
