# html

There are three types of HTML lists: ordered, 
unordered, and definition. 

\<ol></ol> ...>ordered list

\<li></li>...> list item in the list

\<ul></ul>...> unordered list

\<dl></dl>....> definition list usually consists of a series of terms.
\<dt></dt>....> contain the term being defined

nested list
we can add another list inside <li> element.
example of a list
\<ul>
 \<li>2 A</li>
 \<li>B</li>
 \<li>B</li>
 \</ul>

# Boxes

Box Dimensions ...> width, height
we use these to set your own dimensions for a 
box 

example
div{
width: 300px;
height:300px;
}

min-width, max-width max-height, min-height.
to specifies the smallest and maximum width and height can be display on the window.
example

div{
min-width : 450px;
max-width : 650px;
max-height: 400px;
min-height: 500px;
}

overflow : tell the browser what to do if the content larger than the box it has two value.
1-hidden...> hides any extra content.
2-scroll...> add scrollbar to the box.
example
p{
overflow:hidden;
}
p{
overflow:scroll;
}

border: separates the box from another.

margin: to create a gap between the borders of two adjacent boxes.

padding: space between the border and the content contained within it.

border-width...> d to control the width of a border.
example
p{
border-width: 2px;}

boorder-style...> solid,dotted,double.....

corder-color..> to give color for it.

margin: 10px auto 10px auto; ...>we use auto from the right and left to center the content.

display : to turn an inline element into a block-level element or vice versa.

1-inline: block-level to inline element.

2-block: inline element to block level.

3-inline-block: This causes a block-level  element to flow like an inline  element, while retaining other 
features of a block-level element.

4-none: This hides an element from the page.

visibilty: hide the box but it leaves a space where the element should be.
1-hidden: hide the element.

2- show the element.

box shadows: The box-shadow property  allows you to add a drop shadow around a box.

border-redius: to rounded corners .

# Javascript

array: to stores a list of values.
create an array:
example
var colors; 
colors ['white', 'black', ' custom']; 

Values in an array are accessed as if they are in a numbered list
the array start from index zero.
example

INDEX VALUE 
o    'white ' 
1    'bl ack' 
2    ' custom' 
var itemThree; 
itemThree = colors [2] ; ...> to access the third item.

Update the third item in the array 
colors[2] = 'beige ' ; 


the if statement and we use it to consider
 a condition and based on the out result if 
the result was true we will do action and if false we will do another action.

syntax

if(expression){

if this true do //code

if not go to the next else if to check

else if {

code//

}

else {

do this default //code 

}

}

 

also we have a switch statement it's like if statement
 but here we took a value then consider some cases based on this value 

syntax

switch(value){

case :

//code;

break;

....

default:

//code 

 

}  

type coercion: JavaScript can convert
 data types behind the scenes to complete an operation.

# Loops

*for loop*
for loop will check the condition if true will run a block of code then the condition will be checked again until come false usually, we use it when we know how many times we want to run the code.

*while loop*
like the for loop but usually, we use it if we don't know how many times the code will run.

*do while*
like the wihle but here the condition will run at least one.


declaration:
for(var i=0;i<=10; i++){
//code
}

while (i < 10) { 
//code
i++; 

}


do { 
//code
i++; 
} wh il e ( i < 1) ; 
