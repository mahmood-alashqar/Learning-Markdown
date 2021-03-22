# LayOut

### would you know how to control each element sits on a page and how to create attractive page layouts ?

### when you learning CSS about *Layout* you will :
* Explore different ways to position elements using normal flow, relative positioning, absolute positioning and floats.
* Discover how various devices have different screen sizes and resolution, and how this affects the design process.
* Learn the difference between fixed width and liquid layouts, and how they are created.
* Find out how designers use grids to make their page designs look more professional.

# Key Concepts in Positioning Elements :

* Building Blocks : 
## CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

> Block-level elements 
 start on a new line.
> - Inline elements
 flow in between surrounding text.

* Containing Elements: 
> If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
  **its cool what you can do in CSS**
  ## CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property:
  
  * Normal flow 
  > Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

  * Relative Positioning
  > This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

  * Absolute positioning 
  > This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
  