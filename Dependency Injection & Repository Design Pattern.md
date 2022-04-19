# Dependency Injection & Repository Design Pattern

![img](https://miro.medium.com/max/741/1*VPKY-RbVhLZierPrCwRiKQ.png)

### What is Dependency injection in simple words?

It's having an instance of a class that has a function inside of it that can be used for other objects, where other objects depending on this instance of an object to complete functionalitiy.

Example: An object of a car class, could depend on another object instantiated from the engine class to run, A human Object depending on Organs objects, and so on.

This is very useful to create a manager net that connects our project components to each other, but could also present a lot of complications if it was over practiced.


<br><hr><br>

### Repositry Pattern

Repositories are classes that hold logic needed to access data sources.  

Why is it useful?  
* Easy to test application logic,
* Ability to do unit tests without needing to connect to database.
* Multiple operations can be handled in a single transactions.
* Increased performance & reduced inconsistency.

<br><hr><br>
### Principles

* SRP(): Each method should have a single functionality (Does only one thing).
* OCP(): Methods & Classes should be open for extension but closed for modification.
* LSP(): An object in your application should be able to be replaced with a type derived from it without breaking the application.
* ISP(): Making interfaces more specific so that clients don't use interfaces they don't want.
* DIP(): Our code should depend on abstractions and not concrete implementations.

