# Error Handling & Debugging


order of execution:

The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run: 

EXECUTION CONTEXTS: The JavaScript interpreter uses the concept of execution contexts. 

three execution context:

1- GLOBAL CONTEXT 

2- FUNCTION CONTEXT 


3- EVAL CONTEXT (NOT SHOWN) 

The Stack: javascript processes one line of code at a time.

when a stetment need call function , it stacks the function on the top of current task.

execution content and hosting.

when th script enter the execution we have two phases :

1-prepare: 

scope created, variables, function created ...

2- execute :

assign value to variables, execute statment.


Understanding Errors: 

If a JavaScript statement generates an error, then it throws an exception. 
so, the interpreter stops and looks for exception-handling code. 

Error object :  help you to fined the mistakes .

built-in error object :

1-RangeError => number outside of range.

2-SyntaxError => syntax is not correct. 

3-TypeError => value is unexpected data type.

4-ReferenceError => variable doesn't exist.


How to deal with errors :

we have two ways :

1-debug the script:

  debug the code , track down the source of the errors and fix it.

2- handle errors gracefully: 
  
using try, catch.


Debugging Workflow:

1- Where is the problem :
look to error message 

check the script is running

use breakpoints


2- what exactly is the problem:
 
set breakpoints to see the variables.

break down/ break out parts of code to test.

check the number of parameters.

Browser Dev Tools and Javascript console.

javaScript consol: will tell you when the problem there a problem with a script.

Error in chrome:

The console will show you when there is an error in your JavaScript. It also displays the line 
where it became a problem for the interpreter. 

you can also try code in the console.


BreakPoints :

you can pause the execution any time then check the value stored in variables.

how to open it in chrome :
1- source

2- breakpoint

3- select the line you want

4- when you run script it will stop in this line.



handiling exception:

we use try and catch if we know the code will fail.

syntax of try and catch:

try { 

//Try to execute this code 

}

catch (exception) { 

//If there is an exception, run this code 

}

finally { // This always gets executed }