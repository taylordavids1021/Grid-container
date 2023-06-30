# Grid-container
Practise grid css

An element that implements CSS Grid has two main parts:

The first is the grid container, which can be any block level, like a div, which serves as a wrapper for all the cells or elements inside the grid. The grid container has its display property set equal to 'grid' (For example, display: grid;) and has a list of properties that allow you to manipulate how elements inside it are displayed and sorted, how many columns are in the grid, etc.
The second is the grid item. Grid items are all child elements inside a grid container. They can be any type of element (inline or block-level element). Grid items also have their own unique properties, mostly dealing with the sizes or dimensions of an item.

An alternative you have to the ‘display: grid’ value is the display: ‘inline-grid’ property, which changes the grid container from a block-level element to an inline element, allowing you to place other inline elements next to the grid.

 

In the code above, we briefly cover one of the most fundamental properties of CSS Grid, the grid-template-columns property, which allows us to specify the default width of all columns in the grid and how many columns the grid will have. This code will create three columns so only three elements will be allowed in a single row by default, leaving the rest of the elements to overflow onto the next row.