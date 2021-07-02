 

 function object is a construct allowing an object to be invoked or called as if it were an ordinary function

Here's some tips to follow when building your own domain models.
When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.
Tables
What's a Table? A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results

Basic Table Structure
<table>

The <table> element is used to create a table. The contents of the table are written out row by row.

<tr>

You indicate the start of each row using the opening <tr> tag.(The tr stands for table row.)

<td>

Each cell of a table is represented using a <td> element. (The td stands for table data.)

image

Table Headings
<th>

The <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

image

FUNCTIONS, METHODS & OBJECTS
Functions allow you to group a set of related statements together that represent a single task.
Functions can take parameters (informatiorJ required to do their job) and may return a value.
An object is a series of variables and functions that represent something from the world around you.
In an object, variables are known as properties of the object; functions are known as methods of the object.
Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
Arrays and objects can be used to create complex data sets (and both can contain the other).