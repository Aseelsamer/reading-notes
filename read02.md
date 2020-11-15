# JQUERY
-Jquery is a javascript file that you include in your web pages and lets you find elements using CSS-style selectors, it makes code simplr.
You create an object called Jquery() lets you find one or more element in a page and hold refrence to it.

The object and the elements it contains is referred to as a matched set or iQuery selection, you can use the methods of jQuery object to update these elements.

Some jQuery methods both retrieve informatio from and update the content of elements but they do not always apply to all elements.

### Get Infromation: 
if a jQuery holds more than one element and method is used to get info from the selected elements it will retrieve info from **only the first element in the matched set**.

### Set Information:
if a jQuery holds more than one element and method is used to update info on the page it will **update all of the elements in the matched set not just the first one**.

Note:When you create a selection with jQuery it stores a refrence to the corresponding nodes in the DOM tree.(not copies of them)

With jQuery, when a selector returns multiple elements, you can update all of them using the
one method. There is no need to use a loop. 

If you want to use more than one jQuery method on the same selection of elements, you can
list several methods at a time using dot notation to separate each one.

You can use jQuery's.ready() method to check that the page is ready for your code to work with.
.html()
When this method is used to retrieve information
from a jQuery selection, it retrieves only the HTML inside the first element in the matched set, along with any of its descendants. 

.text()
When this method is used to retrieve the text from a jQuery selection, it returns the content from every element in the jQuery selection, along with the text from any descendants. 

.replaceWith()
This method replaces every element in a matched set with new content. It also returns the
replaced elements. 

. remove()
This method removes all of the elements in the matched set. 

-For Adding New Elements:
.before()
This method inserts content before the selected element(s) .
.prepend()
This method inserts content inside the selected element(s),after the opening tag. 
.after()
This method inserts content after the selected element(s).
.append()
This method inserts content inside the selected element(s),before the closing tag.

-You can create attributes, or access and update
their contents, using the following four methods. 
.attr()
This method can get or set a specified attribute and its value. 

.removeAttr()
This method removes a specified attribute (and its value)

.addCl ass()
This method adds a new value to the existing value of the cl ass attribute

.removeClass()
This method removes a value from the cl ass attribute, leaving any other class names within
that attribute intact. 

-How to get CSS property:
The . css () method lets you retrieve and set the values of CSS properties.
Example : var backgroundColor = $( ' li ' ) . css( 'background-color' ); 


The jQuery is included before the body just as the JS.

------------------------------------------------

## Pair Programming :
### How it works?
The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer.

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

Advantages of Pair Programming:
1-Greater efficiency.
2-Engaged collaboration.
3-Learning from others.
4-Social Skills.
5-Job interview readiness.
6-Work enviroment readiness.

------------------------------------------------

