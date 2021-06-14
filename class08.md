#css layout
CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.

Block-level elements
start on a new line
Examples include:
<h1> <p> <ul> <li>

Inline elements
flow in between 
surrounding text
Examples include:
<img> <b> <i>

If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.


A box may be nested inside 
several other block-level 
elements. The containing 
element is always the direct 
parent of that element.


Every block-level element 
appears on a new line, causing 
each item to appear lower down 
the page than the previous one. 
Even if you specify the width 
of the boxes and there is space 
for two elements to sit side-byside, they will not appear next 
to each other. This is the default 
behavior (unless you tell the 
browser to do something else).

width
This sets the width of the 
columns.
float
This positions the columns next 
to each other.
margin
This creates a gap between the 
columns.

The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
X Pages can be fixed width or liquid (stretchy) layouts.
X Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
X Grids help create professional and flexible designs.
X CSS Frameworks provide rules for common tasks.
X You can include multiple CSS files in one page


