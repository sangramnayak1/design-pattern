# Java Design Pattern


GoF Design Pattern Types:
----------------------------
GoF Design Patterns are divided into three categories:

    Creational: The design patterns that deal with the creation of an object.
    Structural: The design patterns in this category deal with the class structure such as Inheritance and Composition.
    Behavioral: This type of design patterns provides solutions for the better interaction between objects, promoting loose coupling, and flexibility to extend easily in future.


Creational Design Patterns:
----------------------------
Creational patterns are concerned with the process of object creation. Their primary goal is to abstract the instantiation process, making the system independent of how its objects are created, composed, and represented. This helps to hide the complexities of object creation, provide more control over the creation process, and increase the system’s flexibility. By decoupling the client from the concrete classes it instantiates, these patterns allow for easier modification of object creation logic without affecting the client code.

There are 5 design patterns in the creational design patterns category:

Pattern Name | Description
-------------|------------
Singleton 	| Ensures that a class has only one instance and provides a global point of access to that instance. Useful for managing shared resources or configurations.
Factory 	| Defines an interface for creating an object, but lets subclasses decide which class to instantiate. It centralizes object creation while allowing flexibility for different product types.
Abstract Factory 	| Provides an interface for creating families of related or dependent objects without specifying their concrete classes. It’s a “factory of factories.”
Builder 	| Separates the construction of a complex object from its representation, allowing the same construction process to create different representations. Ideal for objects with many optional parameters.
Prototype 	| Creates new objects by copying an existing object (the prototype) instead of creating new instances from scratch. This is often more efficient for complex object creation.


Structural Design Patterns:
----------------------------
Structural patterns deal with the composition of classes and objects to form larger structures. Their focus is on how objects are put together to build more complex systems while ensuring flexibility and efficiency. These patterns help in organizing classes and objects into larger structures, making the system more robust and easier to maintain. They often involve concepts like inheritance and composition to define relationships between entities, ensuring that changes to one part of the system have minimal impact on others.

There are 7 structural design patterns defined in the Gang of Four design patterns book:

Pattern Name | Description
-------------|------------
Adapter 	| Allows two incompatible interfaces to work together by wrapping one around the other. It acts as a bridge between disparate systems.
Composite 	| Composes objects into tree structures to represent part-whole hierarchies. Clients can treat individual objects and compositions of objects uniformly, simplifying client code.
Proxy 	| Provides a surrogate or placeholder for another object to control access to it. This can be for security, lazy loading, remote access, or logging.
Flyweight 	| Minimizes memory usage by sharing as much data as possible with other similar objects. It’s used for large numbers of fine-grained objects, like characters in a text editor.
Facade 	| Provides simplified, high-level interface to a complex subsystem. It hides the complexity of a system from the client.
Bridge 	| Decouples an abstraction from its implementation, allowing them to vary independently. This is useful when both the abstraction and its implementation can change.
Decorator 	| Attaches new responsibilities to an object dynamically, providing a flexible alternative to subclassing for extending functionality. It wraps an object to add new behaviors.


Behavioral Design Patterns:
----------------------------
Behavioral patterns are concerned with the algorithms and the assignment of responsibilities among objects. They describe how objects communicate and interact with each other to accomplish a task. The goal is to define efficient, flexible, and loosely coupled communication channels between objects, allowing them to collaborate without becoming overly dependent on each other’s concrete implementations. These patterns focus on the flow of control and data between objects, enabling dynamic behavior and easier extension of functionality.

There are 11 behavioral design patterns defined in the GoF design patterns:

Pattern Name | Description
-------------|------------
Template Method 	| Defines the skeleton of an algorithm in an operation, deferring some steps to subclasses. It lets subclasses redefine certain steps without changing the algorithm’s structure.
Mediator 	| Defines an object that encapsulates how a set of objects interact, reducing direct dependencies between them. It promotes loose coupling by centralizing communication.
Chain of Responsibility 	| Avoids coupling the sender of a request to its receiver by giving multiple objects a chance to handle the request. The request is passed along a chain until an object handles it.
Observer 	| Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically. Key for event-driven systems.
Strategy 	| Defines a family of algorithms, encapsulates each one, and makes them interchangeable. It allows the algorithm to vary independently from clients that use it.
Command 	| Encapsulates a request as an object, thereby allowing for parameterization of clients with different requests, queuing, logging, or support for undoable operations.
State 	| Allows an object to alter its behavior when its internal state changes. The object will appear to change its class based on its state.
Visitor 	| Represents an operation to be performed on the elements of an object structure. It lets you define a new operation without changing the classes of the elements on which it operates.
Interpreter 	| Given a language, defines a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
Iterator 	| Provides a standard way to access the elements of an aggregate object sequentially without exposing its underlying representation.
Memento 	| Captures and externalizes an object’s internal state without violating encapsulation, so that the object can be restored to this state later. Useful for undo mechanisms or saving states.

## Factory Design Pattern
<img width="675" height="785" alt="image" src="https://github.com/user-attachments/assets/dd7148b2-fbdb-43ee-80ab-a1e2f19bb4fe" />


## Abstract Factory Design Pattern
<img width="1342" height="810" alt="image" src="https://github.com/user-attachments/assets/9fdeeb12-f194-4370-b3be-ed2b44efa3a7" />

## Builder Design Pattern
<img width="1036" height="843" alt="image" src="https://github.com/user-attachments/assets/b14d9af4-251b-48ac-b6bf-ec26ad7d65eb" />


