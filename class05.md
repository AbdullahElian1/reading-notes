# image

why we need image ?
Images can be used to set the tone for a site in less time than it takes to read a description.

it is good practice to create a folder for all of the images the site uses.

how to add an image?
\<img src="" alt=" />
src: source for the image
alt:This provides a text description of the image .
title:to provide additional information about the image.

we can specify the size of the image by:

1- width

2- height
example
width="600" height="450".

where to provide the image in the code?
1- before a paragraph.
2-inside start of paragraph.
3-in the middle of paragraph.

alighn the image in the directions:
align:left;...> put the image in the left and the paragraph next to the image.

align:right;...>put the image in the right and the paragraph next to the image.

align:top: the first line of the paragraph in the top of the image.

align:middle: the first line of the paragraph in the middle of the image.

align:bottom:the first line of the paragraph in the bottom of the image.


3 rules to creating an image:

1-Save images in the right format.
like jpeg,gif.

2-Save images at the right size.
the right width and height.

3-Use the correct resolution

tools to edit images:
1-Adobe Photoshop.

2-PaintShop Pro.


in html5 we have two  tags :
1- \<figure> ...>to contain images and their caption.

2-\<figcaption> ...>add a caption to an image.




# color

you can specify the color in css in three way 
1- RGB (255,255,255) 

2- HEX ( #ee3e80) 

3- color names : There are 147 predefined color names such as DarkCyan

CSS3 has also introduced another way  to specify colors called (HSLA)

background-color: to put a color for the background.

It is important to ensure that there is enough contrast 
between any text and the background color.

you can use a color picker To find the color you want.

CSS3: Opacity opacity, rgba CSS3 introduces the opacity property
which allows you to specify the opacity of an element and any of its child elements.


# text

Typeface Terminology
1- serif: made the end of the letters strokes we name them serifs.

2-sans-serif:straight end to letters.

3-Monospace:very letter in a monospace (or fixed-width) font is the same width.


weight:
Light
Medium
Bold
Black

style:
Normal
Italic
Oblique

stretch:
Condensed
Regular
Extended


Specifying Typefaces:

font-family: Georgia, Times, serif;

font-size:12px or 12% or 1.3em;

@font-face {font-family: 'ChunkFiveRegular';
src: url('fonts/chunkfive.eot');}..>to use a font even if you didn't install it in your pc.

font-weight: bold;

font-style: italic;


text-transform: uppercase;...> the text will appear uppercase.

text-transform: lowercase;...> the text will appear lowercase.

text-transform: uppercase;...> the first letter of each word to appear capitalized.


text-decoration: underline;...>adds a line underneath the text.

text-decoration: none;...>removes any decoration

text-decoration:line-through;...>This adds a line through words.

letter-spacing: 1em; space between the letters.

word-spacing :1em; space between the word.

text-align: left; ...> put the text in the left.

text-align: right...> put the text in the right.


text-align: center...> put the text in the middle.


text-align: jusrify...> the line will take the full width except the last line;


text-shadow:: 1px 1px 0px #000000;

a:link {
color: deeppink;
text-decoration: none;}

a:visited {
color: black;}

a:hover {
color: deeppink;
text-decoration: underline;}

a:active {
color: darkcyan;}
