# LJ Code 201 - Day 13

<p>End goal of final projects: 3 pages, 2 that takes user input, and something that stays in local storage (pseudo-persistence). Demonstrate some core competencies, including research (e.g., reading docs and figuring stuff out from there).</p>

<p>Side note: RegEx is basically another language inside of javascript with its own rules that helps with pattern matching in strings. regexr is a good site to learn about regex.</p>

<p>If you want to find something in an array, you have to go through an entire array. (for loops)</p>

<p>When you need to keep track of state (of application) you normally use global variables -- like counters.</p>

<p>REMINDER: if stuff stops working, open the browser console!!! The console tells you specific lines where your app is fucked up. Except with unexpected tokens -- sometimes they are before the line the console tells you.</p>

<p>Debugging is its own skillset, and a very important one. Before you start debugging, know what you *expect* your program to be doing (and what it *should* be doing) *before* you try to debug problems.</p>

<ul>**Common errors**
<li>Error of an undefined variable or property</li>
<li>Syntax and unexpected token errors</li>
<li>Calling a function that requires 1+ paramaters without passing in those arguments gives an error of undefined</li>
</ul>

<p>check application part of console to look in on local storage <br />
localStorage.setItem <br />
localStorage.getItem <br />
JSON (javascript object notatation) is a built in object that lets us turn objects/arrays into strings and strings back into objects/arrays. It has two methods - JSON.parse and JSON.stringify. stringify turns an array into a string. It wraps the keys and values in the array in double quotes. You can then localStorage.setItem a stringified object (u may want to set up a variable that contains the stringified object/array) on local storage. You get that string back when you localStorage.getItem(variable). We can JSON.parse it back into an object. <br />
</p>

->You start with your items... var items = [{..},{..}]<br />
->then var itemsJSON = JSON.stringify(items)<br />
->Then localStorage.setItem('items',itemsJSON)<br />
->Then var storedItemsString = localStorage.getItem('items')<br />
->Then var tems = JSON.parse(storedItemsString) which gives you your original items back.
