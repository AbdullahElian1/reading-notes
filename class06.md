# Object

Objects group together a set of variables and functions to create a model 
of a something.

in the object the variables and the function become known as 

variables = property.
function = method.

the name of property called a key.
example

name :'Quay',
how to create an object

example
var hotel{

name:'amman',
room :20,

check : function(){

return ...;
}
}

access the object

example

var hotelNmae= hotel.name;
var room = hotel.check();


# Document Object Model

The Document Object Model (DOM): specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents


DOM TREE 
example
![dom](https://content.codecademy.com/practice/art-for-practice/dom-nodes.png)


Accessing and updating the DOM tree involves two steps: 
1: Locate the node that represents the element you want to work with. 
2: Use its text content, child elements, and attributes. 

we have 3 way to access the elements:
1-select individual element
example 
getElementByld () 

2-welect multiple element
example
getElementByClassName()

3-TRAVERSING BETWEEN ELEMENT NODES 
example
parentNode 



to find element in dom tree we use dom queries 
example 
getElementById()

if you want to dealing with this element more than once then store it in variable.
example
var itemOne= getElementById('one');


access element
dom queries can return one element or nodelist.

getElementByld( 'id')
return one element

querySel ector('css selector') 
return one element

getEl ementsByClassName('class')
return a Nodelist. 


getEl ementsByTagName('tagName')
return a Nodelist. 

There are two ways to select an element from a Nodelist:
1- item() method
example
var elements = document.getElementsByClassName('hot') 
if (elements.length>= 1) { 
var firstltem = elements.item(O); 
}

2- array syntax
var elements = document.getElementsByClassName('hot') 
if (elements.length>= 1) { 
var firstltem = elements.item[0]; 

if you need the same action for all nodelist use loop
example
var hotitems= document.querySelectorAll(li.hot)
\for(var i =0; i<hotitem.length;i++)
hotitem[i].className='cool'
}


TRAVERSING THE DOM 
1-parentNode
2-previousSibling 
3-nextSibling 
4-firstChild
5-lastChild


change the content
1- nodeValue
example
document.getElementByid( 1 one 1 ).firstChild.nextSibling. nodeValue;
2- replace ...> replace word with word
example
elText = elText.replace( ' pine nuts', ' kale '); ...>I Change pine nuts to kale.

3-textContent: allows you to 
collect or update just the text that is in the containing element (and its children). 
example
document .getElementByid('one') .textContent; 

4-innerText: you should generally avoid it for three key reasons: 

1-SUPPORT: Firefox does not because i nnerText is not part of any standard.

2-OBEYS CSS : It will not show any content that has been hidden by CSS.

3-PERFORMANCE: PERFORMANCE Because the i nnerText property 
takes into account layout rules that specify whether the element is visible or not.



Add or Remove html
1-innerHtml
example
var iten;
item='\<em>fresh</em> figs';

2-DOM Manipulation
steps
1-createElement () 
2-createTextNode()
3-appendChild() 
example
var newEl document .createEl ement( ' li '); 
var newText document.createTextNode( 'quinoa ' );
newEl .appendChild(newText); 
var position = document.getElementsByTagName('ul ')[O]; 
position.appendChild(newEl); 




Attribute nodes
example
document.getElementById('one').getAttribute('class');

CHECK FOR AN ATTRIBUTE
example
var firstitem = document.getElementByid( 'one'); 
if (firstitem.hasAttribute('class')) { 
var attr = firstltem.getAttribute(' class');
var el = document .getElementByid( 'scriptResults'); 
el.innerHTML = /'<p>The first i tem has a class name : ' + attr + '<Ip>'; 





 






 







 







 