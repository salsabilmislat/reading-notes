# What we will learn

- Reading and Writing Files in Python

- Python Exceptions


The source of this summary [The first link](https://realpython.com/read-write-files-python/)

The source of this summary [The second link](https://realpython.com/python-exceptions/)

______________________________________

## Reading and Writing Files in Python

**The file is a contiguous set of bytes used to store data.**

It has three main parts:

1. Header it is the contents of the file

2. Data the contents written by the creator or editor

3. End of file (EOF) character at the end of the file


File Paths : it is the tree of the files including the File Name and Extension

**To access any file without using the full path we should use the special characters double-dot (..) to move one directory up. and move through them**

**Opening and Closing a File in Python**

There are two types of files that can be handled in Python, normal text files and binary files (written in binary language, 0s, and 1s).

Syntax: File_object = open(“File_Name”, “Access_Mode”)

To explain it more ---> 

Opening a file refers to getting the file ready either for reading or for writing. This can be done using the open() function. This function returns a file object and takes two arguments, one that accepts the file name and another that accepts the mode(Access Mode).

The Access Mode:

1. Read Only	r	Open text file for reading only.

2. Write Only	w	Open the file for writing.

______________________________________

## Python Exceptions

<img src="https://res.cloudinary.com/dyd911kmh/image/upload/v1633675298/python-try-except-else-finally_doblhm.png" style="height: 300px; width:600px;"/>

**Try: It will run the code block in which you expect an error to occur.**

**Except: Here, you will define the type of exception you expect in the try block (built-in or custom).**

**Else: If there isn't any exception, then this block of code will be executed (consider this as a remedy or a fallback option if you expect a part of your script to produce an exception).**

**Finally: Irrespective of whether there is an exception or not, this block of code will always be executed.**


**Exceptions : Python exceptions are errors that are detected during execution and are not unconditionally fatal**


### There is many type of Exceptions:

1. Type Error

This will cause Type Error

a = 2

b = 'DataCamp'

a + b

2. Zero Division Error

This will cause Zero Division Error

100 / 0