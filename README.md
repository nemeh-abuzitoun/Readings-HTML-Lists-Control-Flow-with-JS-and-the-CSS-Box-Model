# Readings-HTML-Lists-Control-Flow-with-JS-and-the-CSS-Box-Model
CSS Box Model


HTML-Lists

HTML lists allow web developers to group a set of related items in lists.

Example
An unordered HTML list:

Item
Item
Item
Item
An ordered HTML list:

First item
Second item
Third item
Fourth item
Unordered HTML List
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

The list items will be marked with bullets (small black circles) by default:

Example
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

Ordered HTML List
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.

The list items will be marked with numbers by default:

Example
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
HTML Description Lists
HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:

Example
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
HTML List Tags
Tag	Description
<ul>	Defines an unordered list
<ol>	Defines an ordered list
<li>	Defines a list item
<dl>	Defines a description list
<dt>	Defines a term in a description list
<dd>	Describes the term in a description list
For a complete list of all available HTML tags, visit our HTML Tag Reference.
All HTML elements can be considered as boxes.
https://www.w3schools.com/html/html_lists.asp
  
  
  
  
  
  
The CSS Box Model
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent
The box model allows us to add a border around elements, and to define space between elements. 

Example
Demonstration of the box model:

div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
Width and Height of an Element
In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

Important: When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

Example
This <div> element will have a total width of 350px: 

div {
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
Here is the calculation:
320px (width)
+ 20px (left + right padding)
+ 10px (left + right border)
+ 0px (left + right margin)
= 350px
The total width of an element should be calculated like this:

Total element width = width + left padding + right padding + left border + right border + left margin + right margin

The total height of an element should be calculated like this:

Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin

https://www.w3schools.com/css/css_boxmodel.asp
  
  control flow
  Control flow on Javascript
One of the most famous poets from Portugal has a sentence that is: “Primeiro estranha-se,depois entranha-se”, that in English is something like first it feels weird but then you feel it in you. That has been my experience with Javascript since the beginning. It started something that just felt weird but with time, it got on me and now I just want to know more and more and practice more and more.
That being said I decided to write posts about Javascript topics. By writing it here I learn it better and you will also find something useful out of it. Because I am a code newbie and mostly I write these posts for other code newbies it might be that some things seem easy, even for me and you, but it just to get a ground start and to not jump over bit subjects in a topic.
The first one of this long series is going to be about Control flow in Javascript.
Control flow is in computer science the order that the instructions or statements or functions are executed. In javascript, we read the code starting from the first line till the last line unless of course in the code there is some instructions or statements that changes that control flow.
The most known control flow used I would think is the if statement that we used many of our code. For example, you want a website to show some page if you are older than 18, if not, the website would render a different page is a traditional example of a control flow/ conditional example
NOTE: Loops are a big part of control flow statement but because I want to write a post only about loops, even that I am going to mention and use them on the examples it will not be my main focus.
  https://dev.to/mugas/control-flow-in-javascript-246l
  
