Write a blog on the difference between Document and Window objects.*

Document Object:

          The document object represent a web page 
that is loaded in the browser. By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. The document object can be accessed with a window.document or just document.

Syntax: document.property_name;

1.It is loaded inside the window.
2.It is the object of window property.
3.All the tags, elements with attributes in HTML are part of the document.
4.The document is part of BOM and dom.

  example:

    document.title :  will return the title of the document.
    

*Window Object:*

       The window object is the topmost object of the DOM hierarchy.
  It represents a browser window or frame that displays the 
  contents of the webpage. Whenever a window appears on the screen to
  display the contents of the document, the window object is created. 
Syntax: window.property_name;

  1.It is the very first object that is loaded in the browser.
  2.It is the object of the browser.
  3.Global objects, functions, and variables of JavaScript 
    are members of the window object.
  4.The window is part of BOM, not DOM.
  
  example:

    window.innerHeight : will return the height of the 
                         content area of the browser.
