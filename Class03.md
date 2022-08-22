# Passing Functions as Props
**                                                    **


## **Part 1:** <br>

**1- All of the elements inside the array starting from index 0 and it returns a new array with the element.**<br><br>
**                                                    **
**2- We should first create the array and then save the map value of it inside of another array 
after looping through the old one to build hte collection of elements that we will save 
in the new arrayx** <br>
**                                                    **
**3-key**<br><br>

**                                                    **

**4-it helps react to idetify the changes among the items (changing, adding,removing)**<br>
<br>
**                                                    **
**                                                    **
## **Part 2:** <br>

**1- -What is the spread operator? Its a useful sytax that was added in Js ES6 it takes iterable (like an array)<br><br> and separates them into individual elements**<br><br>
**                                                    **
2- <br><br>
**-List 4 things that the spread operator can do
A-Coying an array
B- Adding new items to a lisat
C- Combining objects
D- Converting NodeList to an array**<br><br>
**                                                    **
**3-Give an example of using the spread operator to combine two arrays.
Const array = [1,2,3]
const array2=[4,5,6]
const newArray = [...array,...array2]
// new array will be = [1,2,3,4,5,6]** .<br><br>
**                                                    **
**4-Give an example of using the spread operator to add a new item to an array.**
**const array= [1,2,3]**
**const array2= [5,6,7,... array]**
**array2 will be equal to [5,6,7,1,2,3]**
**                                                    
 <br>                         
<br>
<br>
**5-**
**-Give an example of using the spread operator to combine two objects into one.**

const objectOne = {hello: Hello }
const objectTwo = {world: user}
const objectThree = {...objectOne, ...objectTwo, laugh: haha}

objectThree is now equal to (hello: Hello ,world: user,laugh : haha)**
**                                                    **
**                                                    **
## Video Part : 

-In the video, what is the first step that the developer does to pass functions between components?<br><br>
He created a function where the state is <br><br>
-In your own words, what does the increment function do?<br><br>
it has a parameter which is the name and it takes it as a key to look for and when it finds the requested name , it will increase the count of that object<br><br>
-How can you pass a method from a parent component into a child component?<br><br>
it works the same way as props so we can call it using "this" .<br><br>
-How does the child component invoke a method that was passed to it from a parent component?<br><br>
By calling the method as if its a props into another method in the child<br><br>



**                                                    **

**                                                    **




## Things I want to know more about
The idea of passing between the parent and the child 
**                                                    **
## **Sources :**
> https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

>https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab
