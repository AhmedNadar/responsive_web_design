## Responsive Web Design Techniques

Rsponsive Design is an essentional practice for any web developer. It's not that hard to adapt and apply it to any project.

Simply, **It's a redeclaration some styles for specific devices' width** 

**Example:**

  ```@media all and (max-width: 768px) { 
  	h1 {color: red;} 
  }```
  - For all devices no matter what kind, if the width of the screen gets smaller than 768 pixels, make the h2 text color red. Check it out [here](http://jsbin.com/fupigevunu) 
  
  `@media only screen and (min-width: 450px) { ... }`
  - Using only tells IE8, IE7 and IE6 to ignore anything with @mediaquery
