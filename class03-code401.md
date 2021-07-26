# Read & Write Files in Python

What Is a File?

a file is a contiguous set of bytes used to store data. 
This data is organized in a specific format and can be anything as 
simple as a text file or as complicated as a program executable.

three main part of file:
1- Header: metadata about the contents of the file (file name, size, type, and so on)

2- Data: contents of the file as written by the creator or editor

3- End of file (EOF): special character that indicates the end of the file.

File Paths:

The file path is a string that represents the location of a file.

Opening and Closing a File in Python:

to open file :

file = open('dog_breeds.txt')


there are two ways that you can use to ensure that a file is closed properly :

*use the try-finally block:

*use the with statement

There are three different categories of file objects:

*Text files

*Buffered binary files

*Raw binary files


Python Exceptions aand raising

Expections happen when the python code is syntactically correct but u run into an error (the last line of the error tells you what type of exception it is) raise allows you to throw an exception at any time.
The AssertionError Exception

assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
The try and except Block: Handling Exceptions

    In the try clause, all statements are executed until an exception is encountered.

    except is used to catch and handle the exception(s) that are encountered in the try clause.

The else Clause

In Python, using the else statement, you can instruct a program to execute a certain block of code only in the absence of exceptions. else lets you code sections that should run only when no exceptions are encountered in the try clause.
finally

finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions. Everything in the finally clause will be executed it doesn't matter if u run into an exception

