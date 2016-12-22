# LJ Code 201 - Day 15

<p>In the bus mall project we were using the click event to randomize display of images shown on the screen, limit number of clicks a user could make to 25, track clicks on specific images, and track specific images shown.
<ul>To track clicks we needed to know:
<li>Which image we clicked on;<br />
---->we need to "listen" for a clicked;<br />
---->event.target for information;<br />
---->match paths  ( we used the split method on the strong for this<br /> --------to match event.target.src to our 'paths' array);<br />
---->find object that corresponds to the path;
</li>
<li>Count number of times an image was clicked<br />
----->we know we need to track as property of an object. We know since<br /> ------the objects will have similar properties with different values we <br />------know a constructor object is useful!</li>
</ul>
<ul>The problem domain for randomize images:
<li>pick three random images;<br />
---->abstract this problem out to finding 3 random numbers that can<br /> ------be used as index numbers of the items array containing the images
</li>
<li>compare each image within the set to other images in the set to ensure no duplicates;<br />
---->For this we need randomly generated indexes;<br />
---->And we need to be able to access the previous set of indexes;<br />
---->And across these two things we need to ensure no duplications of<br /> ------indexes.
</li>
<li>compare the current set to the previous set to ensure no duplications;</li>
</ul>

<p>*The event object* provides information on the event. THe event object gets passed into every function in the click handling function.</p>
<p>event.target fetches a DOM node. Nodes have all sorts of properties, like innerHTML, textContent, etc.<p>
<p>We work with DOM nodes in particular ways. event.target fetches the node where the event was registered. In bus_mall, the event should register on an image that gets clicked.</p>
<p>the source (i.e, event.target.**src**), is what we used to match the source path to our local path.</p>

<ul>Local storage has two methods:
<li>.getItem('key')</li>
<li>.setItem('key','value')</li>
</ul>

<p>ChartJS is a javascript library, meaning it contains tons of functions that have already been written.</p>

<ul>To get chartJS running we needed:
<li>To insert a <canvas> element into the html skeleton;</li>
<li>we used the chart object which is a kind of configuration object. if you want to pass into a function a bunch of optional arguments (ddata, colors, multiple arrays, multiple datasets, etc.) - it is crazy unwieldy to try to pass a million arguments into a function! We might want to pass an object in instead!</li>
</ul>
