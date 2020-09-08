## Reading Day: 09.07.20

# jQuery
jQuery is a JavaScript file that you include on your web pages. It allows simpler ways to achieve results from JavaScript. jQuery uses CSS selectors that make access to elements easier. jQuery also makes it easier to write event listeners without having to write fallback code for older browsers.

The jQuery function **$()** lets you find one or more elements on a page.
It has similarities to the DOM.
- jQuery selectors offer a simpler syntax and perform a similar task to traditional DOM queries.
- the jQuery object can be stored in a variable just like DOM nodes.
- You can use jQuery methods and properties to manipulate the DOM nodes that you select.  

In order to use jQuery you must include the script in an HTML page. It is inserted inside a script tag before the closing body tag. A JavaScript file is also included that use jQuery selectors and methods to updated the content of the HTML page.

Today I learned about **minification** which applies to jQuery code that has all of the empty spacing taken out. Minification is a commonly used practice used for making jQuery code (libraries) load faster. Why is this important? It ultimately effects how fast the HTML page will load.

# Less is More
My introduction to jQuery has been welcomed. The syntax is easier to understand and I've had more moments of understanding in a shorter period of time that with JavaScript. I say "Bring it on!" And I'm liking the ties to CSS.  

## How jQuery handles Data
Some jQuery methods both retrieve information from and update the contents of elements. These methods can get information from and set information to the HTML page. When creating a selection with jQuery, it stores a reference to the corresponding nodes in the DOM tree.

The most attractive thing about jQuery is the shorthand so to speak. Upon reading about handling methods... **Chaining** is the process of placing several methods in the same selector. This results in a compact line of code.

**$('li{id!="one"] ') .hide().delay(500).fadeIn(1400);** (an example of chaining)

## Getting and Updating Element Content
**.html() and .text()** methods both retrieve and update the content of elements. .html () is used to retrieve information from a jQuery selection. It retrieves only the HTML inside the first elements along with any of its descendants.

**.text()** is a method that is used to retrieve text from a jQuery selection, along with text from any descendants. 

**.replaceWith()** replaces every element in a matched set with new content and returns the replaced elements.

**.remove()**
This method removes all of the elements in the matched set. 

## Inserting Elements
Inserting new elements includes two steps:
1. Create a new element in a jQuery object.
2. Use a method to insert the content into the page.

The following methods can be used to add content to the DOM tree:

- .before() // inserts content before the selected element(s)
- .after () // inserts content after the selected element(s)
- .prepend () // inserts content inside the selected element(s)
- .append () // inserts content inside the selected element(s) before the closing tag.

## Getting and Setting Attribute Values
The following methods create attributes or access and update:
- .attr() // Method can get or set a specified attribute and its value.
- .removeAttr() // Removes a specific attribute.
- .addClass() // Adds a new value to the existing value of class attribute.
- .removeClass() // Removes a value from the class attribute.

## CSS Properties
The **.css()** method lets you retrieve and set the values of CSS properties. What this means is targeting the CSS and changing it! While I've used CSS for at least 6 years, I really became interested in both JavaScript and jQuery and learning how CSS interacts with both of them. I had no idea that CSS was being used this way. 

## Each Method
I'm bringing attention to the .each() method because it allows you to recreate the function of a loop. **.each()** allows you to perform one or more statements on each of the items in the selection of elements  that is returned by a selector - Like a loop in JavaScript.

## Event Object
Every event handling function receives an event object. It has methods and properties related to the event that occurred. It works the same as a JavaScript events object. The **.on() method has two optional properties that let you filter the iQuery selection and pass extra information into the event handler using object literal notation.

## CDN
A CDN stands for 'Content Delivery Network and is a series of servers spread out around the world. Why? They serve HTML, CSS, JavaScript, images, audio and video files quickly to local servers.

## Takeaways
My takeaways from the reading today is the jQuery has some simpler syntax than JavaScript. jQuery and CSS have some ties that I can identify and I look forward to understanding and using the CSS style selectors. This was a complex read for sure and having to make sense of it after such a long day is kind of laughable. Onward!

## Pair Programming
So far I've found Pair Programming a great learning experience. It has been practice for me: Practicing writing code, talking about code, making sense of code and It is so much better than trying to tackle a coding project alone. It is very helpful to have that extra set of eyes to look over code and then to find out the mistake is due to a misspelling.

This article makes some great points:
1. Greater Efficiency
1. Engaged Collaboration
1. Learning from Fellow Students
1. Social Skills
1. Job Interview Readiness
1. Work Environment Readiness

As I look at this list I can definitely say I've benefitted from all six points listed. Personal favorites I would include are engaged collaboration, learning from fellow students, social skills and benefitting with greater efficiency. I'm learning this I'm proud to say.

[<== Back to Table of Contents](index.md)
