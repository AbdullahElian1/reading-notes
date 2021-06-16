
    What is a ‘call’?

The call stack is primarily used for function invocation (call) and this funcyion execute the functions from top to down


    How many ‘calls’ can happen at once?

one at a time

    What does LIFO mean?

last in first out that mean the last function pushed to the stack will pop out first.

    Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
    
function firstFunction(){

  console.log("Hello from firstFunction");

}

function secondFunction(){

  firstFunction();

  console.log("The end from secondFunction");

}

secondFunction();

    What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 


    What is a ‘refrence error’?

when you try to use a variable that is not yet declared 


    What is a ‘syntax error’?

this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.


    What is a ‘range error’?

when you try  manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.


    What is a ‘tyep error’?

like accessing a property in an undefined type of variable.


    What is a breakpoint?

 breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.


    What does the word ‘debugger’ do in your code?

debugger statement and when running the code above you can see the “history” before reaching that breakpoint.

