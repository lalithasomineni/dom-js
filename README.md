- .innerHtml() //changes the inner html content of the selected id element.

- document.getElementById(id)	Find an element by element id
- document.getElementsByTagName(name)	Find elements by tag name
- document.getElementsByClassName(name)	Find elements by class name
- element.innerHTML =  new html content	Change the inner HTML of an element
- element.attribute = new value	Change the attribute value of an HTML element
- element.style.property = new style	Change the style of an HTML element
- element.setAttribute(attribute, value)	Change the attribute value of an HTML element
- document.createElement(element)	Create an HTML element
- document.removeChild(element)	Remove an HTML element
- document.appendChild(element)	Add an HTML element
- document.replaceChild(new, old)	Replace an HTML element
- document.write(text)	Write into the HTML output stream
##### example event:
- <button onclick="displayDate()">Try it</button>
##### event listenerss
- document.getElementById("myBtn").addEventListener("click", displayDate);
 on click start executing displaydatefunction.
 parameters are evnet(click,mouseover etc)and function to be executed .
