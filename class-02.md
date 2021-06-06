Web browsers create similar models of the web page they are showing 
and of the browser window that the page is being shown in.

PROPERTIES 
Properties describe characteristics of the current 
web page (such as the title of the page).

METHODS 
Methods perform tasks associated with the 
document currently loaded in the browser (such 
as getting information from a specified element or 
adding new content).

These three layers form the basis of a popular 
approach to building web pages called 
progressive enhancement. 

Adding the CSS rules in a 
separate file keeps rules 
regarding how the page looks 
away from the content itself. 

When the browser comes across a <script> element, it stops to 
load the script and then checks to see if it needs to do anything. 

A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.

A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables.

Using the i nnerHTML property, you can access 
and amend the contents of an element, 
including any child elements.

DOM manipulation offers another technique 
to add new content to a page (rather than 
i nnerHTML). 

DOM manipulation can be used to remove 
elements from the DOM tree.

The i nnerHTML property lets you get/update the 
entire content of any element (including markup) as astring.


If you add HTML to a page using i nnerHTML (or several jQuery methods), 
you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, 
an attacker could gain access to your users' accounts. 

All data from untrusted sources should be escaped 
on the server before it is shown on the page. 
Most server-side languages offer helper functions 
that will strip-out or escape malicious code.

The <sup> element is used 
to contain characters that 
should be superscript such 
as the suffixes of dates or 
mathematical concepts like 
raising a number to a power such 
as 22
.

In order to make code easier to 
read, web page authors often 
add extra spaces or start some 
elements on new lines.

As you have already seen, the 
browser will automatically show 
each new paragraph or heading 
on a new line. But if you wanted 
to add a line break inside the 
middle of a paragraph you can 
use the line break tag <br />

Content management systems and HTML editors such as Dreamweaver 
usually have two views of the page you are creating: a visual editor and a 
code view.

Visual editors often resemble 
word processors. Although 
each editor will differ slightly, 
there are some features that 
are common to most editors 
that allow you to control the 
presentation of text.

There are some text elements that are not intended to affect the 
structure of your web pages, but they do add extra information to the 
pages — they are known as semantic markup.


The first time you explain some 
new terminology (perhaps an 
academic concept or some 
jargon) in a document, it is 
known as the defining instance 
of it.
The <dfn> element is used to 
indicate the defining instance of 
a new term.

 Ordered lists are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number.
 Unordered lists are lists that begin with a bullet point 
(rather than characters that indicate order).
 Definition lists are made up of a set of terms along with the 
definitions for each of those terms.


Links are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute.

The border attribute was used 
on both the <table> and <td>
elements to indicate the width of 
the border in pixels.


HTML borrows the concept of a form to refer to different 
elements that allow you to collect information from visitors to 
your site.


A form may have several form controls, each 
gathering different information. The server 
needs to know which piece of inputted data 
corresponds with which form element.


Form controls live inside a 
<form> element. This element 
should always carry the action
attribute and will usually have a 
method and id attribute too.




