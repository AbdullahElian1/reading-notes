# links

defintion list

links : allow you to move from one web page to another.
type of links

1-link website to another
2-link two page in the sam website.
3- part in the page to another part.

Directory Structure... organize your code by put the pages in new folder.
example 
pages that related to the css put it inside new folder.

Relative URLs: used to link pages within the website.
example:\<a href="music/listings.html">Listings</a>





cheat list:
\<a href="the link"> Name</a>....> link tag.

href"www.google.com"...> link to another website.
href"index.html"....link to page in the same website.

\<a href="mailto:jon@example.org">Email Jon</a>...> email link.
\<a href="http://www.imdb.com" target="_blank">....> we use target _blank to open the page in new tab.
\<a> href="#top">Top</a> link in the same page.


# layout

defintion list
block-element: start a new line
such as (h1,p,ul).
inline element: on the same line
such as(img b).

position:allow you to control the layout of a page.
type of the position
1-Normal
2-Relative
3-Absolute

z-index:  control which 
element sits on top.

float: take the element and place it to the righ or left of the containing.



cheat list:

p{
position: relative;
top: 10px;
left: 100px;}

h1 {
position: absolute;
top: 0px;
left: 500px;
width: 250px;}

h1 {
position: fixed;
top: 0px;
left: 50px;
}

z-index
h1 {
position: fixed;
top: 0px;
left: 50px;
z-index=10;
}

float:

blockquote {
 float: right;
 width: 275px;
 font-size: 130%;
 font-style: italic;

}

place elements side by side.
p {
width: 230px;
float: left;
margin: 5px;
padding: 5px;
background-color: #efefef;}



screen size: that show different amounts of information.


screen Resolution: refers to the number of dots a screen shows per inch.

page sizes: web designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

fixed width : don't change the size when increas or decrease the window.

Liquid layout designs : stretch and contract as the user increases or decreases the size of their browser window. 

CSS Frameworks: aim to make your life easier by providing the code for common tasks.





# javascript 

function: Functions let you group a series of statements together to perform a specific task.
how to declare a function ?

fuction sayhello(){
//code
} 

how to call the function?
we just call the name like this sayhello();


how declare a function with information?

function getArea(width,height){

return width*height;
}


how to call a function with information?

getArea(3,5);


get single value from the function?


function getArea(width,height){

return width*height;
this function will return one value.
}

get multiple values from the function?
function getSize (width, height, depth) { 
var area = width * height; 
} 
var volume = width * height * depth; 
var sizes= [area , volume]; 
return sizes

this function will return more than on value in array
}


local variables :When a variable is created inside a function using the 
var keyword, it can only be used in that function. 

global variables:If you create a variable outside of a function, then it 
can be used anywhere within the script.