# Testing and Modules
---
## In Tests We Trust - TDD with Python:
- Unit tests and TDD :
Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

Unit testing has some details that we should keep an eye on such as the test name , tests can be considered as your alive documentation. We need to be descriptive about it and to say what is expected and what we are testing.

#### Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.

Arrange: you need to organize the data needed to execute that piece of code (input);
Act: here you will execute the code being tested (exercise the behaviour);
Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

## TDD got a cycle that is made by 3 steps 
- Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
- Write the feature and make the test pass! (you can dance after that)
- Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)

#### Things to Remember : 
- The greatest advantage about TDD is to craft the software design first
- Your code will be more reliable: after a change you can run your tests and be in peace
- Beginning may be hard — and that’s fine. You just need to practice!




---
## If name equals main :
#### Pythong files can be excuted in 2 ways : 
- as a Scripts : is a collection of commands in a file designed to be executed like a program.
- as a module : is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended. 

We use the if __name__ == “__main__” to avoid running codes that should not be excuted when we use the same file in different places (module or script)
In the case of having the file as a module the  __name__ will be module name if not , then the __name__  will be __main__ . 

#### This whole process got some advantages : 
- Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
- If you import this script as a module in another script, the __name__ is set to the name of the script/module.
- Python files can act as either reusable modules, or as standalone programs.
- if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.
---

##  Recursion :

What is Recursion? 
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function. Using a recursive algorithm, certain problems can be solved quite easily.

Recursion is made for solving problems that can be broken down into smaller, repetitive problems.

#### Why not to use recursion
- It is usually slower due to the overhead of maintaining the stack.
- It usually uses more memory for the stack.
#### Why to use recursion
- Recursion adds clarity and (sometimes) reduces the time needed to write and debug code (but doesn't necessarily reduce space requirements or speed of execution).
- Reduces time complexity.
- Performs better in solving problems based on tree structures.



---
>### Sources : 

https://stackoverflow.com/questions/5250733/what-are-the-advantages-and-disadvantages-of-recursion#:~:text=Why%20to%20use%20recursion,problems%20based%20on%20tree%20structures.

https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/

https://faculty.washington.edu/rjl/classes/am583s2014/notes/python_scripts_modules.html#:~:text=A%20Python%20script%20is%20a,to%20perform%20a%20specific%20task.

https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/
