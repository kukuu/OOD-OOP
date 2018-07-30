

# Object Oriented Design  & Object Oriented Programming

## Features of OOP

#### 1. Inheritance

Inheritance is a fundamental capability construct in OOP where you can use one class, as the base or basis for another class or many other classes. Doing this allows you to efficiently re-use the code found in your base class. 
Inheritance can make your code lighter, because you are re-using the same code in a number of different classes. 

The object-oriented development methodology places great stock in the concept of inheritance. This strategy promotes code re-usability and assumes that one will be able to use well-designed classes within numerous applications (design pattern).

A design pattern is the ability to have a reusable solution in solving a common occurrence problem. 


#### 2. Encapsulation

Programmers enjoy putting little things together as well as taking things apart. Although self satisfying, such in-depth knowledge of an item’s inner working is normally not a requirement. Millions of people use radio sets and computers, however not knowing the underlying architecture and procedures of how they work. Typical example is the radio. By changing a station, what you are actually doing is changing the 
signal to a different frequency associated with another radio station. Failing to understand this concept should not stop you from using the radio, because the interface takes care to hide such details.

In OOP, the practice of separating the user from the true inner workings of an application through well-known interfaces is known as encapsulation. The embodiment of the application is a number of independent components. These components are known as objects and objects are created from a blue print or templates called class.

Classes specify what sort of data (properties) the object might contain and the behavior (method) one would expect. This strategy offers the following advantages:
The developer can change the application implementation without affecting the object user, because the user’s only interaction with the object is via an interface.
Potential of user error is reduced because of the control exercised over the user’s interaction with the application.

#### 3. Polymorphism

Polymorphism in OOP is the ability to re-define a class ‘s characteristics or behavior depending upon the context in which it is used.

For example, a clockIn behavior in an Employee definition for a Clerk and Programmer will be dependent upon the context in which the “clockIn”  is implemented. The class Clerk could simply define clockIn  as using a time clock to timestamp a card. Whiles the class Programmer will accomplish this by signing onto the corporate network.
Another classic example of polymorphism uses an inheritance tree rooted in the Animal class. All Animal's have a makeNoise() method, but the Dog class and the Cat class implement it differently. This allows you to refer to any Dog's and Cat's using an Animal reference type.

Animal a = new Dog();

Animal b = new Cat();

Now you can call makeNoise() on either Animal instance and know that it will make the appropriate noise. This is particularly useful if you have a Collection of Animals, and you don't know at run time exactly what type each of them really is.

#### 4. Abstraction

An abstract class is a class that cannot be instantiated, it exists extensively for inheritance and it must be inherited. There are scenarios in which it is useful to define classes that is not intended to instantiate; because such classes normally are used as base-classes in inheritance hierarchies, we call such classes abstract classes.  Abstract classes cannot be used to instantiate objects; because abstract classes are incomplete, it may contain only definition of the properties or methods and derived classes that inherit this implements it's properties or methods. Polymorphism is a form of abstraction.  
Generally considered, abstraction is a focus to essential qualities, disregarding, ignoring or hiding details to capture some kind of commonality between different instances.


# Key OOD & Software Development Concepts:

#### 1. Class

OOP revolves around a construct called a 'class'.  Classes are blue prints or templates that are used to define objects.  They provide basis from which you can create specific instances of the entity the class models. For example, an employee management application may include an Employee class. You can then call upon this class to create and maintain specific instances or entities, say Peter and Josh (objects), for example.

Classes are intended to represent those real-life items that you’d like to manipulate within an application.


#### 2. Object

A class provides a basis from which you can create specific instances of the entity of the class model, better known as object. Objects are created from the process of instantiation Classes 

#### 3. S.O.L.I.D

S – Single-responsiblity principle:
A class should have one and only one reason to change, meaning that a class should have only one job.


O – Open-closed principle:
Objects or entities should be open for extension, but closed for modification.


L – Liskov substitution principle:
Every subclass/derived class should be substitutable for their base/parent class.


I – Interface segregation principle:
A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.


D – Dependency Inversion Principle:
Entities must depend on abstractions not on concretions. High level module must not depend on the low level module, but they should depend on abstractions.


#### 3. Composition over Inheritance

Composition over inheritance (or composite reuse principle) in object-oriented programming is the principle that classes should achieve polymorphic behavior and code reuse by their composition (by containing instances of other classes that implement the desired functionality) rather than inheritance from a base or parent class.

The use of interfaces allows this technique to support the Polymorphic behavior that is so valuable in object-oriented programming. Classes implementing the identified interfaces are built and added to business domain classes as needed. Thus, system behaviors are realized without inheritance.

Business domain classes may all be manifested as base classes without any inheritance at all.

# Advantages of Object Oriented Programming

In OOP, you think of software as being a series of virtual objects. A series of mini programs inside a larger one. The larger program is the entire script for the application that you are writing. This could be a blog or message board. A list of  mini programs within the application could be;

```
An object to connect to  a database for the application

An object to handle validation

An object for handling user input

An object to build a table for the result of a query from a database

```
1. All these help to give you better organization and management of your code base. OOP allows you to create re-usable block/components of code if designed properly.

2. Easy to update OOP system as they are modular based. OOP systems are designed to be plug and play.

3. Since the whole application is segmented, you can adopt division of labor. Developers can work co-currently on different models/components to build objects for the application without interfering with one another. 

In short, it is easier to have multiple programmers working on code base and not worrying about touching or breaking code in other parts of the system.

4. You can eliminate a distinctive functional component from the system and should not affect other functional components of the system.

5. You can use the components to build a library. Most of the components of the library you build can be imported into other projects.

6. OOP principles are consistent in other languages, so it is easy to move from one OOP language say PHP to say Ruby or Java. Though syntaxes may vary and are quite minimal. The same is for frameworks like Zend, Pear, Smarty templates and many more.

# Software Development Life Cycle

There are following six phases in every Software development life cycle model:

		Requirement gathering and analysis

		Design

		Implementation or coding

		Testing

		Deployment

		Maintenance

1) Requirement gathering and analysis:  Business requirements are gathered in this phase. 

	This phase is the main focus of the project managers and stake holders. Meetings with managers, 
	stake holders and users are held in order to determine the requirements like; Who is going to use the system? 
	How will they use the system?  What data should be input into the system?  What data should be output by the system? 
	These are general questions that get answered during a requirements gathering phase. After requirement gathering 
	these requirements are analyzed for their validity and the possibility of incorporating the requirements 
	in the system to be development is also studied.

	Finally, a Requirement Specification document is created which serves the purpose of guideline for the next 
	phase of the model. The testing team follows the Software Testing Life Cycle and starts the Test Planning 
	phase after the requirements analysis is completed.

2)  Design:  

	In this phase the system and software design is prepared from the requirement specifications
	which were studied in the first phase. System Design helps in specifying hardware and system 
	requirements and also helps in defining overall system architecture. The system design 
	specifications serve as input for the next phase of the model.

	In this phase the testers comes up with the Test strategy, where they mention what to test,
    how to test.

3)  Implementation / Coding: 

	On receiving system design documents, the work is divided in modules/units and actual coding is started.
	Since, in this phase the code is produced so it is the main focus for the developer. 
	This is the longest phase of the software development life cycle.

4)  Testing:  
	
	After the code is developed it is tested against the requirements to make sure that the product is actually 
	solving the needs addressed and gathered during the requirements phase. During this phase all types of 
	functional testing like unit testing, integration testing, system testing, acceptance testing are done as 
	well as non-functional testing are also done. Reference is made to Test Pyramid Cycle and Coverage https://github.com/kukuu/AGILITY/blob/master/test-pyramid-coverage.jpg .

5)  Deployment: After successful testing the product is delivered / deployed to the customer for their use.

	As soon as the product is given to the customers they will first do the beta testing. If any changes are
	required or if any bugs are caught, then they will report it to the engineering team. Once those changes
	are made or the bugs are fixed then the final deployment will happen.

6)  Maintenance: 
    
    Once when the customers starts using the developed system then the actual problems comes up and 
    needs to be solved from time to time. This process where   the care is taken for the developed product
    is known as maintenance.

# Three Types of Design Patterns

Design Patterns are reusable solutions to commonly occuring problems(in the context of software design). Design patterns were started as best practices that are applied again and again to similar problems encountered in different contexts.

Working with design patterns during software development can be tricky at times. Their purpose is to provide guidelines for dealing with particular problems that might arise during development. 

## Behavioral patterns

Behavioral patterns describe interactions between objects and focus on how objects communicate with each other. They can reduce complex flow charts to mere interconnections between objects of various classes. Behavioral patterns are also used to make the algorithm that a class uses simply another parameter that is adjustable at runtime.

Behavioral patterns are concerned with algorithms and the assignment of responsibilities between objects. Behavioral patterns describe not just patterns of objects or classes but also the patterns of communication between them. 


These patterns characterize complex control flow that is difficult to follow at run-time. They shift your focus away from the flow of control to let you concentrate just on the way objects are interconnected. Behavioral class patterns use inheritance to distribute behavior between classes. 

### Examples 

#### Chain of Responsibility

Forces execution to follow a specific chain of command during execution, such that the first object is used, then the second, and so on. Often used as a failsafe in applications, checking the validity of the primary object, before moving onto the secondary object if the primary fails, and so forth.

#### Command 

Decouples the actions of the client from the behavior of the receiver. Often through the use of an interface, an object can specify individual behavior when a particular command is invoked, while a different object type can use that same command, but invoke its own unique behavior instead.

#### Interpreter

Defines a series of classes used to interpret language syntax from a provided sentence. Typically, each symbol is defined by one class, and then a syntax tree is used to parse (interpret) the overall sentence.

#### Iterator

Allows access to underlying elements of an object, without exposing those elements or their respective logic. A very commonly used pattern, often as a simple means of fetching the next item in a list or array of objects.

#### Mediator 

Generates a third party object (mediator) that acts as a go-between for interactions between two other similar objects (colleagues). Commonly, this is used when multiple objects need to communicate, but do not (or should not) be aware of the others respective implementation or behavior.

#### Memento

Stores the state of an object, allowing for restoration (rollback) of the object to a previous state. This behavior is well-known when using word processors that implement the undo feature.


#### Observer 

Creates an event-based dependency between objects, such that an update to the observed object causes the observer objects to be notified. Typically, this is found in many languages that utilize asynchronous functionality, which requires events to be observed and responded to outside of typical execution order.

#### State 

Allows for the behavior of a class to change based on the current state. While these states are often changed throughout execution, the implementation of each possible state is typically defined by a unique class interface.

#### Strategy 

Defines a pattern where logical strategy changes based on the current situation. This is merely an object-oriented extension of common if-else statements, by altering the execution of code based on the outcome of previous code.

#### Template

Allows for a skeletal template to be used as the basis for execution, without defining the inner-workings of any individual class or object. This is commonly seen in web applications, where the visual interface of the application is generated using templates, which are created using underlying data, but neither the template nor the underlying data are aware of the implementation of the other.

#### Visitor

Allows for new operations to be added to objects without modifying their original implementation structures. Typically, the visitor class defines unique methods that are shared between it and other objects, without the need for the other object to be aware of the additional functionality.

## Creational Patterns

Creational patterns are used to create objects for a suitable class that serves as a solution for a problem. Generally when instances of several different classes are available. They are particularly useful when you are taking advantage of polymorphism and need to choose between different classes at runtime rather than compile time.
Creational patterns support the creation of objects in a system. 

Creational patterns allow objects to be created in a system without having to identify a specific class type in the code, so you do not have to write large, complex code to instantiate an object. It does this by having the subclass of the class create the objects. However, this can limit the type or number of objects that can be created within a system.

### Examples

#### Abstract Factory 

Encapsulates groups of factories based on common themes. Often uses polymorphism, the concept in object-oriented programming that allows one interface to serve as a basis for multiple functions of different types.

#### Builder 

Splits up the construction of an object from its representation. This is usually done by defining a Builder object that presents methods to update the object, without directly interacting with the object itself.

#### Factory

Creates objects without the need to specify the exact class or type of object to be created. As the name suggests, this object instantiation is performed through a secondary Factory class, again using polymorphism.

#### Prototype

Creates new objects by prototyping or cloning a prototypical instance of an object. Effectively, an abstract Prototype class is created, and from that base prototype, new secondary inherited classes are defined.

#### Singleton

Restricts the total number of instances of a particular class to only one at a time. This is commonly used when global access to the object is required across the system, and any changes or queries to the object must be consistent and identical.

## Structural Patterns

Structural patterns focus on the composition of classes and objects. By using inheritance and interfaces, these patterns allow objects to be composed in a manner that provides new functionality. They form larger structures from individual parts, generally of different classes.


As a simple example, consider how multiple inheritance mixes two or more classes into one. The result is a class that combines the properties of its parent classes. This pattern is particularly useful for making independently developed class libraries work together. 

### Examples

#### Adapter

Allows for an interface, which is otherwise incompatible, to be adapted to fit a new class. Typically, this is performed by creating a new ClassNameAdapter class that implements the interface, allowing for compatibility across the system.

#### Bridge

Distinguishes between implementation and abstraction. Or, put another way, it’s a pattern that separates the “look and feel” of code from the “logical behavior” of it, which we often see in websites and other visual applications.

#### Composite

Groups of objects should behave the same as individual objects from within that group. Primarily useful when creating a collection of objects that inherit from the same type, yet are uniquely different types themselves. Since they are of the same composition type, their behavior should be identical when combined into a collective group.

#### Decorator

Dynamically modifies the behavior of an object at run time, typically by wrapping the object in a decorator class. This pattern is commonly used when an object is instantiated, but as code execution progresses, modifications must be made to the object before it is finalized.

#### Facade

Creates a front-end (facade) object that obfuscates and simplifies interactions between it and the more complicated interface behind it. Commonly used when a complex series of actions must take place to perform a task, where executing each and every task, in order, is too complicated. Instead, a simple facade replaces that series of tasks with a single task to be executed.

#### Flyweight

Reduces memory and resource usage by sharing data with other, similar objects. Often relies heavily on Factory-style patterns to access and store already generated data during future executions.

#### Proxy 

Defines a wrapper class for an object, which acts as an interface for the wrapped object. Typically, the proxy class attaches additional behavior onto the wrapped object, without the need to modify the base object class behavior.
Three Categories of Design Patterns
