# LJ Code 201 - Day 11
<p>Floats were initially designed so that text can flow around images, so this is why they have strange properties in modern usage.</p>

<p>Using an outline in your CSS elements will show you the boxes but without adding any space to them like a border does. Look at it mostly as a dev tool: most sites aren't released with outlines. Lets you keep track of what you've got going on with boxes, like collapsing or other problems.</p>

<p>With changing a block element to an inline display you cannot set margins on the top and bottom, or even set height. The content will dictate the height.</p>

<ul> 3 ways to make things line up side by side in CSS
<li>**Display as inline**</li>
<li>**Display as inline-block.** This will usually be used in ul's so the li's can still set vertically - vertical margins had to be set, which cannot be done with inline. This is usually best also for like a nav bar. *There will be a white space that creates a margin if you have a space/ carriage return between your div's or whatever. You have to have no spaces/carriage returns in the CSS or close your tag on the line beneath the opening tag right next to the opening tag of the next element.*</li>
<li>**Float** is usually the best way to handle getting elements to sit side by side without worrying about the white space margins or whatever.We use the "clear: *(left, right, or both)*" property to the element AFTER the floated element If you're trying to clear a UL after floating the li's you can throw in a br and br in CSS go ahead and clear it.</li>
</ul>

<p> **:after** is a pseudo-class. e.g., ul:after in CSS creates a secret HTML element...in CSS, that you can give properties to. You can use it to **apply a clear:both rather than throwing in a br** to clear. It has to be written like ul:after { diplay: table; content: ''; clear: both;}</p>

<p>.clearfix:after { display: table; content: ''; clear: both;} will also let you clear a float.</p>

<p>**DO NOT** use positioning for layout - unless you specifically want something to sit on top of something else.</p>

<p>THe DOM is not the HTML. It is an object model of the HTML in javascript.</p>
