# LJ Code 201 - Day 12

<p>'use strict' throws us some errors that javascript should but doesn't. if we assign to a variable without delcaring it strict mode will throw an error. in non-strict mode javascript will just give that variable global scope. in strict mode 'this' does not have a default mode - in normal mode it does and it defaults to setting something to the window object.</p>

<p>event.target.src  ... we are accessing a property from the event object (we know from the dot). target is also an object, which we know from the dot. the target object of the event object is asking for the src node that fires off the event.
