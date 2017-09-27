# viewtest

This is a test :-)

To emulate the VIEW/3000 screen,
 with scaling of the Reflection terminal emulator,
 in a web environment.

#Known bugs

The autotab function eats the last character typed.
The error "lightbox" is badly formatted.
The error "lightbox" will not close, instead you must reload the page.
Key Board FKEY's are not yet supported, click on the FKEY buttons works.

Fixing these bugs is outide the scope of this test.

#The goal here

Is to create data fields and function key labels dynamically,
 use the html viewport scaling to scale screen objects like they did at WRQ in the Refelction software.

NOTE: When the page is first displayed it will be blank, with only FKEY's!

F8 will process the form JSON variable and create the screen.
F7 Will clear the screen.

So clicking F8 & F7 consecutively will show how quickly screens can be taken down and re-created.

F6 Display the error "lightbox", not click on it, it is broken.

Other FKEY's probably do nothing.

#Files

index.html		Main Page.
main.css		The main css file.
mcleod-reset.css	My preferred reset css file.
spec3000.js		Form (Formspec) JSON file.
view3000.js		The view logic javascript file.


