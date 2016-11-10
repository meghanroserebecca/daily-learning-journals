# LJ Code 201 - Day 3

<p>Learned that \n is inserted into a string to break up the line!</p>

<p>Javascript will treat all words outside of strings as variables. It will spit out a reference error if you have forgotten to enclose your string in '' because it will treat them as UNDEFINED variables!</p.
<p>Do not put semi-colons after a block(of code)!</p>

<p>If when you open code on a browser you get an issue with loading, always check the console first! The console will tell you the file the error is n (app.js? style.css? index.html?) and what *line* it's on.</p>

<p>If you declare a variable at the top of the scope (beginning of your JS code) to be, for example, var seeMyArt; you have declared a variable and left it UNDEFINED. Which means it can be overwritten with a definition later in the script. It's best practice to declare variables, even if you leave them undefined, at the TOP of your SCOPE. EXCEPT for those variables inside of for loops.</p>

 <p>NULL & UNDEFINED are both a **"falsey"** value - both will evaluate to false. Null is an object for stupid javascript reasons, and undefined is undefined. Undefined is a *default value* - it's something that exists but is not yet defined. Null is null on purpose: it is not null by default, something (someone) has set something to null on purpose. They both mean, though, that "nothing is here" or "empty." Hitting cancel on a prompt is usually something that brings up null...although I'm still not very clear on this.</p>

<p>ctrl + shift + j = open console on browser</p>

<p>Types: Functions, Strings, Booleans, Numbers, Objects (an array is an object), and Undefined. You can find the type of something by using the keyworkd *typeof* --keywords, unlike functions, are not called, they are just printed in front of something. For example if you type:     typeof 4     your console will return "number".</p>

<p>Other keywords: var, if, null, while, break, do, debugger, throw, switch, instanceof, open, return, void... etc. http://stackoverflow.com/questions/26255/reserved-keywords-in-javascript</p>

<p>Falsey values in javascript: 0, false, undefined, null, NaN, empty string -- '' </p>

<p>TYPE COERCION. If we concatenate two strings, e.g., ('two' + 'strings') javcascript will spit out 'twostrings'. If you add 5 + 5, javascript will spit out 10. If you type 5 + '5', javascript will assume you meant TWO strings, concatenate them, and return '55'. <br />
.....this is where == and === come in. Don't fuckin use double equals! No ==  !</p>

<p>**ARRAYS** - we use them when we want to store a series of things and access those things. They also help when ORDERING is important (everything in the array takes on an numerical value, the first instance taking 0 and each following 1 + the previous)</p>

<p>While loops:<br />
      **while (*...condition...*) {  <br />
        *..block of code...* <br />
      } <br />**
  while the conditions in the parentheses are true, the loop runs. It keeps running until it is false. If it never evaluates to false, your browser crashes.</p>

<p>For loops (has to always have two semi-colons! even if the second one isn't filled in!): <br />
**for (var i = 0; *condition* i < myArrayOfAnimals.length; i += 1** *or i++ --they are the same in a for loop, but try only using += outside of for loops to achieve these ends* **)** <br />


do while loop is good for this assignment.
