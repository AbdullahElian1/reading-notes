# Local Storage 

Historically, Cookies were invented early in the web’s 
history and we use it to store small amounts of data.

three downsides for cookies:

1-Cookies are included with every HTTP request , that will slowing your web.

2- the data wii send without encrypted.

3-cookies limit 4 KB.


# HTML5 Storage 

HTML5 Storage :it’s a way for web pages to store 
named key/value pairs locally, within the client web browser.

to check html Storage :


if (Modernizr.localstorage) {

  // window.localStorage is available!

} else {

  // no native support for HTML5 storage :(

  // maybe try dojox.storage or a third-party solution

}


HTML5 Storge based on named key/value and its store anything as 
a string and you can usr parseInt to retrieve the data as number.


example

var foo = localStorage.getItem("bar");

// ...

localStorage.setItem("bar", foo);


method to remove value to given key


interface Storage {

  deleter void removeItem(in DOMString key);

  void clear();

};


get the total number of values.


interface Storage {

  readonly attribute unsigned long length;

  getter DOMString key(in unsigned long index);

};


StorageEvent object, which has the following properties:

key: string the named key that was added, removed, or modified.

oldValue: any the previous value (now overwritten), or 
null if a new item was added.

newValue: any	the new value, or null if an item was removed.

url*: string the page which called a method that triggered this change.










