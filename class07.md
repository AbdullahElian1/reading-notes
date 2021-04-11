# Tables

What's a Table?

A table represents information in a grid format.
example
sports results.

Structure
\<table> => to creat table
\<tr> =>table row  start row
\<td> => table data cell in the table.
example
\<table>
 \ <tr>
  \   <th></th>
  \</tr>
  \<tr>
   \  <td>
    \ </td>
  \</tr>

\</table>


Spanning ColumnS

The colspan attribute: used on a \<th> or \<td> element and indicates how many columns 
that cell should run across.
example
\<td colspan="2">Geography</td>

Spanning Rows

The rowspan attribute: used on a \<th> or <td> element to indicate how many rows a cell 
should span down the table.
example
 \<td rowspan="2">Movie</td>

we can devide the tables into three elements they are
1-\<thead> =>the head of the table
2-\<tbody> => the body of the table
3-\<tfoot> => the footer of the table




# Constructor

Constructor to create a blank object.
example

var hotel = new Object();

how to add to the object

example

hotel.name ='quay'
hotel.check = function(){
//code
}

to update an object

example

hotel.name='park'


if we want to create many object with similar thing we acn make a template (constructor).

example

function Hotel(name,room,booked)
{
this.name=name;

this.check= function(){
    
//code
}
}

create instances of the object using constructor
example

var quayhotel= new Hotel('quay',40,25)

Array actually special type of object. they hold set of key/value pairs.
example of object

costs ={
room1:100,

room2:200,

room3:300,

room4:400

};

example fo array

costs= [420,460,230,620];


array in object

room1 : items[100,20,10],

object in array

example

[0] {acc: 40, food:20, phone: 10}



BUILT-IN OBJECTS

1-BROWSER OBJECT MODEL.

window.screen.width

2-DOCUMENT OBJECT MODEL.

getElementById()
 
3-GLOBAL JAVASCRIPT OBJECTS.

toUpperCae()