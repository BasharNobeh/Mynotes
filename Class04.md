> # React and Forms<br><br>


**                           **
# Part 1 : 
### 1-What is a ‘Controlled Component’?<br><br>
Its the component that is controlled by the component's state . its also keeps all of the component states in the React state . so we don't havve to rely on the Dom to retrieve any element value <br><br>
**                           **
### 2-Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.<br><br>
No we should wait just to avoid having any undefined attribues by using the change and submit handler . they can give us some control 
among the input of the user and we can just use the handlers inside the tags as with the eventListeners "onSubmit" and "onChange". <br><br>

**                           **
### 3- How do we target what the user is entering if we have an event handler on an input field?<br><br>
We can combine 2 by making a react state the single source of truth . Then the React part that renders a structure likewise controls what occurs there on ensuing client input. An input form component whose worth is constrained by React in this manner is known as a "controlled component".

<br><br>
# Part 2 : 
**                           **
### 1-Why would we use a ternary operator?<br><br>
it can make if condition much smaller and eaiser when the return values are 2  (true,false)
so we can add what the code will excute if its true and the same if its false .<br><br>
**                           **

### 2-Rewrite the following statement using a ternary statement: 

let temp = ((x===y) ? console.log(true) : console.log(false)
**                           **
**                           **
## **Source :**
> https://reactjs.org/docs/forms.html<br>
> https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff
