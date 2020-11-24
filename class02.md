# JQUERY

**ATTRIBUTION**
- JavaScript and jQuery book by Jon Duckett

jQuery offers a simple way to achieve a variety of common
JavaScript tasks quickly and consistently, across all major
browsers and without any fallback code needed. 

jQuery doesn't do anything you cannot achieve with pure JavaScript.
It is just a JavaScript file but estimates show it has been used on over a
quarter of the sites on the web, because it makes coding simpler. 

jQuery's motto is "Write less, do more," because it allows you to achieve
the same goals but in fewer lines of code than you would need to write
with plain JavaScript. 

**LOOPING**

In plain JavaScript, if you wanted to do the same thing to several
elements, you would need to write code to loop through all of
the elements you selected.

With jQuery, when a selector returns multiple elements, you
can update all of them using the one method. There is no need to
use a loop. 

**CHAINING**

If you want to use more than one jQuery method on the same
selection of elements, you can list several methods at a time
using dot notation to separate each one.

The process of placing several methods in the same selector is
referred to as chaining. As you can see, it results in code that is
far more compact.

**GETTING ELEMENT CONTENT**

. html()
When this method is used to retrieve information
from a jQuery selection, it retrieves only the HTML
inside the first element in the matched set, along
with any of its descendants. 

. text()
When this method is used to retrieve the text from
a jQuery selection, it returns the content from every
element in the jQuery selection, along with the text
from any descendants. 

.replaceWith()
This method replaces every element in a matched 
set with new content. It also returns the
replaced elements.

. remove()
This method removes all of the elements in the matched set. 

.before()
This method inserts content before the selected element(s).

.after()
This method inserts content after the selected element(s).

.prepend()
This method inserts content inside the selected element(s),
after the opening tag.

.append()
This method inserts content inside the selected element(s),
before the closing tag.

.attr()
This method can get or set a specified attribute and its value.
To get the value of an attribute, you specify the name of the
attribute in the parentheses.

. removeAttr()
This method removes a specified attribute (and its value). You just
specify the name of the attribute that you want to remove from the
element in the parentheses. 

. addCl ass()
This method adds a new value to the existing value of the cl ass
attribute. It does not overwrite existing values. 

.removeClass()
This method removes a value from the cl ass attribute, leaving
any other class names within that attribute intact. 


