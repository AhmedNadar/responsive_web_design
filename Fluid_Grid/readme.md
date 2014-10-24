## Implementing Responsive Web Design

#### Creating Fluid Web sit by using:

**Fluid layouts**

	- Creating 12 columns grid layout based on 960 Grid System
	- Fix display the whole element with its margin using `box-sizing` property. 
		A good hack form our old firend IE6 (RIP) http://caniuse.com/#search=box-sizing
	- Add a clear fix solution for parents element to clear all children by adding 
	a block after the parent element.

** Flexible Images**

	- The property `max-width: 100%;` for images, forces any image to not exceed it's parent width. This is not enough solution.
	- Specifying a width and height for each image. Doing so will show the wrong hieght for that image.
	- To fix that, we override the inline image height by setting its value to auto.