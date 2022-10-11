# OOP Part02
---
## What are Design Patterns
- Software design patterns are reusable solutions to common problems in software development. As the name suggests, however, a software design pattern is not code – rather, software design patterns act as a guide or paradigm to help software engineers create products following best practices.

-In the case of object-oriented programming paradigm, design patterns are generally aimed at solving the problems of object generation and communication, rather than the larger scale problems of overall software architecture.

- ## There is 3 major types of design patterns:

Creational Patterns:
- Factory Method : In the Factory pattern, we create objects without exposing the creation logic to the client and the client uses the same common interface to create a new type of object.

![image](https://upload.wikimedia.org/wikipedia/commons/4/43/W3sDesign_Factory_Method_Design_Pattern_UML.jpg)

- Singleton : The Singleton pattern ensures that a class has only one instance and provides a global point of access to that instance.

![image](https://www.tutorialspoint.com/design_pattern/images/singleton_pattern_uml_diagram.jpg)

- Abstract Factory : Provides interfaces for creating families of related or dependent objects without specifying their concrete classes.

![image](https://www.tutorialspoint.com/design_pattern/images/abstractfactory_pattern_uml_diagram.jpg)



Structural Patterns:
- Facade :Facade pattern hides the complexities of the system and provides an interface to the client using which the client can access the system.

![image](https://user-images.githubusercontent.com/84404158/195134914-08ec527b-358d-471e-b0f8-3a828544801d.png)

- Adapter :used so that two unrelated interfaces can work together. The object that joins these unrelated interface is called an Adapter.

![image](https://media.geeksforgeeks.org/wp-content/uploads/classDiagram.jpg)

- Decorator :decorator pattern is a design pattern that allows behavior to be added to an individual object, dynamically, without affecting the behavior of other objects from the same class.

![image](https://media.geeksforgeeks.org/wp-content/uploads/20210224164225/Decoratordesignpattern4x.png)



Behavioral Patterns:
- Observer :is a Behavioral design Pattern which allows you to define or create a subscription mechanism to send the notification to the multiple objects about any new event that happens to the object that they are observing.

![image](https://www.tutorialspoint.com/design_pattern/images/observer_pattern_uml_diagram.jpg

- Mediator : is a behavioral design pattern that lets you reduce chaotic dependencies between objects. The pattern restricts direct communications between the objects and forces them to collaborate only via a mediator object.

![image](https://refactoring.guru/images/patterns/diagrams/mediator/structure-indexed.png?id=a82d4cf1b92a4f72af32f231ffd21131)
- Chain of Responsibility : is a behavioral design pattern that lets you pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain.

![image](https://media.geeksforgeeks.org/wp-content/uploads/desigmpatternuml1.png)





---
## Risk Analysis 
- Risk analysis is the process of identifying and analyzing potential issues that could negatively impact key business initiatives or projects. This process is done in order to help organizations avoid or mitigate those risks.

- Risk Analysis allows you to examine the risks that you or your organization face, and helps you decide whether or not to move forward with a decision.

- Risk Identification : 

There are different sets of risks included in the risk identification process. Those are as follows:
- Business Risks : any exposure a company or organization has to factor(s) that may lower its profits or cause it to go bankrupt.

- Testing Risks

- Premature Release Risk : a fair amount of knowledge to analyze the risk associated with releasing unsatisfactory or untested software is required

- Software Risks :  probability of occurrence for uncertain events and their potential for loss within an organization.

- Risk Assessment : is the process of identifying what hazards currently exist or may appear in the workplace.

The perspective of Risk Assessment 

- Effect  : To evaluate risk based on the effect. If you identify a condition, event, or action and try to assess its significance.

- Cause : Assessing risk by Cause is the inverse of assessing risk by Effect. Begin scanning the problem and working your way to the point where you believe the most likely cause is.

- Likelihood : To assess risk using Likelihood means to say that there is a chance that a requirement will not be met.

How to Conduct a Risk Analysis

There are three steps to take:

- Looking for the danger

- Examining the consequences of each individual risk

- Risk mitigation strategies



---
## Dependency Injection

Dependency injection is a technique in which one object (or static method) provides the dependencies of another. A dependency is a reusable object (a service).

#### Dependency injection is classified into three types:
- Dependencies are provided via a class constructor via constructor injection.
- Setter injection occurs when the client exposes a setter method to the injector, which the injector uses to inject the dependency.
- Interface injection: the dependency includes an injector method that injects the dependency into any client that is passed to it. Clients must implement an interface that exposes a dependency-accepting setter method.


So it is now the responsibility of the dependency injection to:

Make the objects
Determine which classes require those objects and provide them with all of them.

#### The use of DI aids in unit testing.
- Because the injector component handles dependency initialization, boiler plate code is reduced.
- Extending the application becomes less difficult.
- Allows for loose coupling, which is essential in application programming.

#### The Drawbacks of DI
- It's a bit difficult to learn, and overuse can lead to management issues and other issues.
- Many compilation errors are propagated to run-time.
- Reflection or dynamic programming are used to implement dependency injection frameworks. This can make it difficult to use IDE automation features like "find references," "show call hierarchy," and safe refactoring.


#### Libraries and Frameworks that implement DI
- Spring (Java)
- Google Guice (Java)
- Dagger (Java and Android)
- Castle Windsor (.NET)
- Unity(.NET)



---
>### Sources : 
[1](https://medium.com/@Mahmoud_Zalt/software-design-patterns-simplified-8a72232d52b1)<br>
[2](https://www.edureka.co/blog/risk-analysis-in-software-testing/)<br>
[3](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)<br>
[4](https://www.tutorialspoint.com/design_pattern/observer_pattern.htm)<br>
[5](https://apps.urban.org/features/risk-assessment/)<br>
[6](https://refactoring.guru/design-patterns/mediator)<br>
[7](https://refactoring.guru/design-patterns/abstract-factory)<br>
[8](https://en.wikipedia.org/wiki/Software_design_pattern)<br>



