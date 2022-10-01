# Intro to Python
---
## Big O :
### - What is Big O  ?
<font size="2"> Big O notation is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity.</font> 
![image](https://user-images.githubusercontent.com/84404158/193421175-f1dad4cc-8767-40c2-b776-d1e2d0243846.png)

![image](https://user-images.githubusercontent.com/84404158/193421209-e4708c0f-fb3c-4f8d-8b15-0c4d5443796f.png)<br><br>
There are actually quite a few rules That we shoukd follow when it comes to big O :
1. O(1) has the least complexity
2. O(log(n)) is more complex than O(1), but less complex than polynomials
3. Complexity of polynomials increases as the exponent increases 
4. Exponentials have greater complexity than polynomials as long as the coefficients are positive multiples of n
5. Factorials have greater complexity than exponentials

- Big O notation is a notation that is agreed upon which is primarily used to describe the worst case scenario when it comes to an algorithm or an expression in terms of time and space (memory) that is going to be spent and so on.

  
---
##  Facts and Myths about Python names and values :

 Since everything in Python is an object, we should reiterate that assigning a variable to another variable does not actually copy the value's content; rather, it copies the reference to the value or memory location that the other variable refers to in memory. Reassigning a different value to a variable again does not mean that we just replaced the original value; rather, it means that we actually broke the first link or reference and added a new one to a different memory location. In conclusion, assignment does not copy data, whichAdditionally, this indicates that operations take place not on the variables themselves but rather on data or values.
 When a variable has a value of an immutable type, changing that value or performing operations on it, such as adding to it or assigning a new value, breaks the reference and creates a new one for the new value because we cannot change the value in place.
While changing an immutable type results in rebinding, we can rebind mutable types in some ways, such as by adding to a list, so change and mutation are not always synonymous.The assignment, on the other hand, is the same for both types.
A lot of things, like defining a class or assigning the iterator in a for loop, are assignments, and assigning is not just limited to the equal sign "=."
Because local variables are destroyed after a job is finished, we should exercise caution when passing arguments to functions or local scopes, such as by reference and value.Even if the values passed are mutable, we should always try to avoid generating side effects by copying them, especially if they are.
Names are not restricted to particular types of values; they can be reassigned dynamically without difficulty, and a variable can reference a regular number and then a function without difficulty.
Moreover, despite the fact that the subject of the video appears to be straightforward, I believe it to be of crucial importance.

---
### Sources : 
https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/

https://www.codenewbie.org/basecs/8

https://www.youtube.com/watch?v=_AEJHKGk9ns&ab_channel=PyCon2015
