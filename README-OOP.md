

# Benefits of OOD & OOP

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
	well as non-functional testing are also done.

5)  Deployment: After successful testing the product is delivered / deployed to the customer for their use.

	As soon as the product is given to the customers they will first do the beta testing. If any changes are
	required or if any bugs are caught, then they will report it to the engineering team. Once those changes
	are made or the bugs are fixed then the final deployment will happen.

6)  Maintenance: 
    
    Once when the customers starts using the developed system then the actual problems comes up and 
    needs to be solved from time to time. This process where   the care is taken for the developed product
    is known as maintenance.

