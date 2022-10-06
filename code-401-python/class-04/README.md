# FileIO & Exceptions
---
## Read & Write Files in Python 

### First of all lets discuss what files are : 
-  a file is a contiguous set of bytes used to store data. This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable. In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.

modern file systems are composed of three main parts:

- Header: metadata about the contents of the file (file name, size, type, and so on)
- Data: contents of the file as written by the creator or editor
- End of file (EOF): special character that indicates the end of the file

Each file has its own unique path which has 3 parts  :
- Folder Path 
- File Name (Name in the picture below)
- Extension (The last part of the file name after the separator)

![image](https://user-images.githubusercontent.com/84404158/194339365-423655f3-a821-4b29-a24b-e072bbc1011b.png)

Openning files in Python has many 3 main types which are :
- 'r'	Open for reading (default)
- 'w'	Open for writing, truncating (overwriting) the file first
- 'rb' or 'wb'	Open in binary mode (read/write using byte data)

- You can open files using the open :
The open() function opens a file, and returns it as a file object. Read more about file handling in our chapters about File Handling.

After opening the files you have many operations that you can apply on the file which are : 
- Read()
- readline()
- readlines()
- write()
- writelines()

#### Other advanced and normal level Python operation that are done with files : 
![image](https://user-images.githubusercontent.com/84404158/194343781-25831898-754f-445c-92d5-d00f83024704.png)






---
## Exceptions in Python

- An exception is an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions.

[Click here to have a look on python exceptions](https://www.tutorialspoint.com/python/python_exceptions.htm#:~:text=An%20exception%20is%20an%20event,object%20that%20represents%20an%20error.)

####  2 ways to apply and exception in python :-
- Default exception that can be Raised automatically
- Cutomized exceptions that the developer can set when a specific senario happened

It is important to distinguish between two types of errors, syntax error result when the interpreter faces a Python code that is written in a wrong way, while, on the other hand, exception errors get raised when a correct python code causes an error, a typical example on that is when you try to open a file by specifying the file path wrongly.

To raise an exception, use the keyword raise followed by the function Exception(<error-message>).

#### Try and Except
- Try and Except are used to handle errors manually (Exception errors) , We can use them to run a specific code in the try and handle any error with the excpet 
For Example : 

```
try:
  file = open(<file-path>)
  ...
except FileNotFoundError:
  # do something
```



---
>### Sources : 
  
  
[python-exceptions - realpython.com](https://realpython.com/python-exceptions/#exceptions-versus-syntax-errors)

[read-write-files-python](https://realpython.com/read-write-files-python/)

[python_exceptions - tutorialspoint.com ](https://www.tutorialspoint.com/python/python_exceptions.htm#:~:text=An%20exception%20is%20an%20event,object%20that%20represents%20an%20error.)

[python - open files](https://www.w3schools.com/python/ref_func_open.asp#:~:text=The%20open()%20function%20opens,our%20chapters%20about%20File%20Handling.)

[list-of-computer-file-extensions-and-their-meaning](http://www.vidyagyaan.com/computer-knowledge/list-of-computer-file-extensions-and-their-meaning/)




