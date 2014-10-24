## Implementing Responsive Web Design

Converting static web site to responsive web sit by using:

* Mixed Fluid and Static layouts.
	** Using display table is semantically incorrect but they are good at mixing both layouts. **
	- Using `display: layout;` will mimic the fluid layout. Since the parent display 
	as table then children should be a cell.
	- Remove any float for children since they are a table cell.