# LJ Code 201 - Day 5
<p>Pro Note: **atom shortcut**! type html [tab] in atom will fill in the <!DOCTYPE html> for you!</p>

<p>**Return stops a function** and kicks you out of it.</p>
<p>**Debugging**
Check input and output of functions first! </br>
**Check input**: console.log the input of the function. Ex: function myFunction(firstName, lastName) {<br />
  console.log('user entered ' +firstName + ' ' + lastName')<br />
  *actual code block of function*<br />
}   The console.log shows us the input.<br />
**Check Output** return lets us see what a function evaluates to. Ex: <br />
function loudLastName(firstName, lastName){<br />
  lastName = lastName.toUppercase();<br />
  return [firstName, lastName];<br />
}   The console.log shows us the output -> the return.
**------------->If you want to get multiple outputs out of a function, you have to return an array!**</p>

<p>When we're talking about **HTML**, fundamentally we are talking about **simply structure.** <h1> h1 isn't how the text is bigger
when we're strictly talking HTML.</h1> We're talking about its structural relationship to other elements on the page - it's more *important* than other headings on the page!</p>

<p>**CSS** is where we talk about how things look.<br />
**Main Display Properties**: *block* (own line, expands to width of its parent container unless width value is set by you) & *inline* (does not sit on its own line; width by default wraps to the content) & *inline-block* (it's kind of like inline but allows you to futz with positioning properties) & *none*<br />
**block elements**: div, p, li, ul, ol, h1...h6<br />
**inline elements**: anchors (used for links), span</br>
**CSS Positioning Properties**: static (default), absolute, fixed -- most of what positioning does it gives us access to moving things in CSS using top, bottom, left, right properties. ** *Relative* ** relates the movement properties to its static (default) values - i.e., it moves the box relative to its static position. It does not take it out of the flow of the page. ** *Absolute* ** is moved relative to its closest positioned ancestor (relative, absolute, and fixed are all positioned! **static** is **not**). It takes it out of the flow of the page. ** *Fixed* ** is positioned relative to the window. It takes it out of the flow of the page. **Out of flow of page** means whether or not the rest of the page thinks of the element as being there or not. Once you position something as absolute or fixed, the rest of the element do not treat the positioned element as if it's there.
</p>

<br />

<p>**Git** ---> *add, commit, push* **add, commit, push.** add, commit, push.  These are a few of my favorite things!</p>

<p>Git checkout -b *branch name* - creates & switches you to a new branch.</p>

<p>Git pull origin master let's you bring the updated master from github back to update your local master (this is the end of the branch, add, commit, push, merge cycle - happens after you have "pulled" (merged) the new branch and master branch in github)</p>

<br />

<p>**Terminal** --> navigation: cd, ls, pwd<br />
            create/edit: mkdir, touch, cp<br />
            delete: rm </p>
<br />

**Project Structure**: <br />
HTML File --- index.html<br />
Javascript File --- app.js<br />
CSS File --- style.css<br />

<p>In the HTML file, the app.js is linked with script tags at the bottom of the page before the closing body tag. CSS is linked in the head section.</p>

<br />

Fancy note: "modals" are the pop-up windows that grey out the rest of the screen - it is accomplished through CSS by popping a div box up with absolute positioning and other values.

<p>**Falsey values**: <ul><li>null,</li> <li>false,</li> <li>0,</li> <li>undefined,</li> <li>'' *(empty string)*,</li> <li>NaN</li></ul></p>
<p>**Truthy values**: Everything that is not a falsey value.</p>

**Null** versus **Undefined** : everything is undefined by default, whereas if something is null it is null by design. For reasons.

<p>**Arrays** : if you are not either *accessing* or *creating* an array, don't use [] brackets!<br />
var arr = ['stuff', 'thing']<br />
We use for loops to iterate over arrays: <br />
for (var i=0; i < arr.length; i++) { var[i] }<br />
Then you type var[i] to access the contents of the array.</p>
<br />
