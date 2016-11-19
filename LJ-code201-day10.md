# LJ Code 201 - Day 10

<p>Check out code wars for awesome practice! They show you others' answers after you answer! There is a Code Fellows codewars clan</p>

<p>DOM manipulation review:
<ul>
<li>document.getElementById --->this returns a node</li>
<li>document.createElement --->this returns a node</li>
<li>el.textContent --->this is a method on a node</li>
<li>el.appendChild --->this is a method on a node</li>
</ul>
</p>

<p>Review on Objects
<ul>
<li>We tend to only use bracket notation to access objects on properties when keynames have restricted characters (e.g., start with an integer) OR when we don't know the value of the key -- like we need to evaluate it before we figure out the value of the key.</li><br />
<li>OTHERWISE, we use dot notation to access properties of objects!</li><br />
<li>Object Constructors! Use for multiple similar objects -> those sub-objects become instances of the Object constructor. To create an object from the object instructor is to "instantiate" it. The keyword "new" is important to instantiation. var quay = new Object{value, value, value};</li><br />
<li>**this** is used inside of a method (a function inside of an object) to refer to the object itself inside of object literals. With the constructor, the "this" becomes the new object that is instantiated.</li>
</ul></p>

<p>Review on Events!
<ul>
<li>node.addEventListener('event name', function(){}) is a method of a node that allows us to "listen" for events -- like when the user clicks a button or submits a form.</li>
<li>Examples of events: submit, click, keyup, keydown, and like 50 more.</li>
<li>When the node ('event name') that the eventlistener is connected to is fired off, the event listener triggers the function that was passed into it as a second argument. The function is the event handler.</li>
<li> When the Event happens, often we want to use event.preventDefault(); event.target is critical
</ul>
<p>

<p>Review on Constructors
<ul>**Positioning**
<li>Static is the default positioning: boxes take up space in the dom and they are where they appear to be. Things positioned as "static" do not give access to property setting 'right' or 'left'. "Static" boxes are not actually considered to be "positioned" which affects absolute-positioned elements.
<li> Relative Positioning - its appearance can move, but it still takes up space where it's 'supposed' to be.</li>
<li> Fixed position elements are anchored to one place relative to the viewport - so if you scroll is moves with the scrolling in order to stay in one place.It does not take up any space in the DOM</li>
<li> Absolutely positioned elements are positioned relative to its closest *positioned* parent element.</li>
</ul><p>

<p> **IMPORTANT CSS NOTES** <br />
--->You cannot position inline elements with vertical margins - you can only set them left and right. With inline-block elements you can position them vertically and horizontally!<br />

--->.clearfix:after LEARN THIS to help fix the problems with FLOATS.</p>
