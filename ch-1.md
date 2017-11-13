## Chapter 1
#### Object Oriented Design

>The purpose of design is to allow you to do design later, and it's primary goal is to reduce the cost of change.

[SOLID Design](http://en.wikipedia.org/wiki/SOLID_(object-oriented_design)):

* Single Responsibility Principle: a class should have only a single responsibility
* Open-Closed Principle: Software entities should be open for extension, but closed for modification (inherit instead of modifying existing classes).
* Liskov Substitution: Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.
* Interface Segregation: Many client-specific interfaces are better than one general-purpose interface.
* Dependency Inversion: Depend upon Abstractions. Do not depend upon concretions. See [Dependency Injection](http://en.wikipedia.org/wiki/Dependency_Injection)

Other principles include:
* Do Not Repeat Yourself: Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.
* Law of Demeter: A given object should assume as little as possible about the structure or properties of anything else.
