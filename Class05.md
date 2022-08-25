# Putting it all together


## Part One:(React Docs - Thinking in React)<br><br>
**                                         **
> ### 1-What is the single responsibility principle and how does it apply to components?<br><br>
Its when the component have only on thing that it should do as the method for example.<br><br>
**                                         **

> ### 2-What does it mean to build a ‘static’ version of your application?<br><br>
Its when we deploy the UI but without any kind of interaction activated in it .<br><br>
**                                         **
> ### 3-Once you have a static application, what do you need to add?<br><br>
We will have to add the functionality by passing states .<br><br>
**                                         **
> ### 4-What are the three questions you can ask to determine if something is state?<br><br>
-If its a passed from the parent through props<br><br>
-Can it be computed based on the other props or states in our component <br><br>
-Does it stay unaltered over the long run<br><br>
**                                         **
> ### 5-How can you identify where state needs to live?<br><br>
Recognize each part that renders something in view of that state.<br><br>
Track down a typical proprietor part (a solitary part over every one of the parts that need the state in the order).<br><br>
Either the normal proprietor or another part higher up in the progressive system ought to possess the state.<br><br>
In the event that you can't find a part where it's a good idea to claim the state, make another part exclusively<br><br>
 for holding the state and add it some place in the ordered progression over the normal proprietor part.<br><br>
**                                         **

**                                         **

## Part Two : (Higher-Order Functions)
**                                         **
> ### 1-What is a “higher-order function”?<br><br>
A function that depends on other functions in one of two ways :<br><br>
-returning them <br><br>
-taking them as arguments <br><br>
**                                         **
> ### 2-Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?<br><br>
It does return a new function if the passes parameter in smaller than the parameter in the to be return method<br><br>
**                                         **
> ### 3-Explain how either map or reduce operates, with regards to higher-order functions.<br><br>
Map() : It iterates the whole array under a condition of a callback function that applies changes on each element in the array <br><br>
and it also return a new array without modifying the original array .<br><br>
**                                         **
**                                         **

>> ## Sources :
>>> https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK
>>> 
>>> https://reactjs.org/docs/thinking-in-react.html

