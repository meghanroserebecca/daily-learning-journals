# LJ Code 201 - Day 9

<p>Synchronous code is code that reads and runs from beginning to end. Asynchronous code is something that occurs when there is code that will not run until the user interacts with it. EventListeners is our first step into Asynchronous code.</p>

<p>Good rule of thumb is to declare your variables at the top of their scope (except like i and j). Remember that you can declare a variable without assigning it a value! Example: var ExampleVar; (leave out the = assigner and just close after the variable name with a semi-colon)</p>

<p>'use strict'; at the top of a JS file will throw an error at you if you try assigning a variable before declaring it with "var". If you weren't using 'use strict'; and you didn't declare a variable inside of a function but just assign it, then javascript will go ahead and declare that variable for you on the GLOBAL scope.In strict mode if you try to do this you will be thrown an error and your code won't run. It also prevents stupid things from happening to ***this*** in your code.</p>

<p> If you have a variable value set to a string that runs more than one line in Javascript, javascript will not treat the lines after the first as a string. You have to concatenate the lines with the + operator and multiple '' tags, or you can escape \ at the end of each line to let JS know the next line is also a string.<p>

<p>If you try to get something from html with javascript with a getElementById('..') and that element isn't there, the javascript will assign Null to that variable. Otherwise, the variable will become a DOM node! Nodes are good :) </p>

<p>Not **all** programming languages let you set a function as an argument in another function. Javascript does. These functions are known as higher order functions.</p>

<p>event.target gets the DOM node that fired off an event (it's usually whatever element/variable linked to an element you added the .addEventListener to). event.target.store_name grabs the input specifically from the store_name. event.target.store_name.value gives us the value from store_name.
