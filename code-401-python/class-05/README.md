# Intro to OOP
---
## Classes and Objects
Class : a blueprint for objects. A class is a user-defined type that describes what a certain type of object will look like. A class description consists of a declaration and a definition. Usually these pieces are split into separate files.

An object is a single instance of a class. You can create many objects from the same class type.

An object consists of:

Name -- the variable name we give it
Member data -- the data that describes the object
Member functions -- behavior aspects of the object (functions related to the object itself)

Example of a class : in this example we created a new class called "Myclass" which now can be used to create 
objects out of it .This class contains one variable "new_variable" and one function "new_function".

```
class MyClass:
    new_variable = "blah"

    def new_function(self):
        print("This is a message inside the class.")
```

Example of a class and its object : As we can see we have the same class of the previous example but an object "myobjectx" in addition to that .
myobjectx now has every variable and function that MyClass have . 


```
class MyClass:
    new_variable = "blah"

    def new_function(self):
        print("This is a message inside the class.")

myobjectx = MyClass()
```
So we can use both of the "new_variable" Variable and the "new_function" function .
```
#Using the variable 
print(myobjectx.new_variable)
#Using the function
myobjectx.new_function()
```
        



---
## Thinking Recursively
- Revursive Functions in Python : 
Recursion is a common mathematical and programming concept. It means that a function calls itself. This has the benefit of meaning that you can loop through data to reach a result.

Example : 
```
def tri_recursion(k):
  if(k>0):
    result = k+tri_recursion(k-1)
    print(result)
  else:
    result = 0
  return result

print("\n\nRecursion Example Results")
tri_recursion(6)
```

### Just to make it a bit clear for you 
![image](https://user-images.githubusercontent.com/84404158/194764841-6a884dc4-fa4b-4975-9d86-d12be4a7e679.png)


Recursive function keeps calling it self until the base case is true . All of the calls that happened to it during the run , gets excuted as a stack(first in last out)
![image](https://user-images.githubusercontent.com/84404158/194764927-e435a256-317b-4b82-80b3-f1c2d49af9b2.png)




---
## Pytest Fixtures and Coverage 

In simple python tests using Pytest, we define unit tests for functions and so on, and we usually keep defining the required data for each function inside each unit test so that the test runs as expected. However, when we have more complex data structures like files and objects, it is better to define them in a way that they are available to all unit tests in the testing module, and that is basically the definition of a fixture.

To declare a function as a fixture, add a special decorator above it: @pytest.fixture, and then pass this function (which returns a piece of data we want to use in more than one unit test, possibly all) to the unit tests that require the data to function properly

Some examples : 

```

@pytest.fixture
def simple_file():
   return StringIO('\n'.join(['abc', 'def', 'ghi', 'jkl']))
   ```

```

@pytest.fixture(scope='module')
def simple_file():
   return StringIO('\n'.join(['abc', 'def', 'ghi', 'jkl']))
```
We can simply say that this fixture is representing our data . 

Moving on to coverage

### Coverage : 
#### How to get it 
There's a package called pytest-cov on PyPI that you can download and install. Once that's done, you can invoke pytest with the --cov option. If you don't say anything more than that, you'll get a coverage report for every part of the Python library that your program used, so I strongly suggest you provide an argument to --cov, specifying which program(s) you want to test. And, you should indicate the directory into which the report should be written. So in this case, you would say:
```
pytest --cov=mymul .
``` 
and by typing coverage html after the pytest command, you can display the report in a more readable format as an HTML page.

---

### Things I want to know more about : 
- Is using recursion the best practice  ? if yes then , what is the need of normal methods that has a loop .

>### Sources : 
[1](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)<br>

[2](https://www.cs.fsu.edu/~myers/c++/notes/classes.html#:~:text=A%20class%20is%20a%20user,from%20the%20same%20class%20type.)

[3](https://www.programiz.com/python-programming/recursion)

[4](https://www.learnpython.org/en/Classes_and_Objects)

[5](https://realpython.com/python-thinking-recursively/)




