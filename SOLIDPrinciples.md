# S.O.L.I.D Design Principles

## Introduction:
In software development **``Object-Oriented Design``** plays important role for writing scalable, maintainable, flexible and reusable code. **``SOLID``**  principles is coding standard that every piece of code should follow.<br>

``SOLID Principles:``

1. Single Responsibility Principle (SRP)
2. Open/Closed Principle
3. Liskov’s Substitution Principle (LSP)
4. Interface Segregation Principle (ISP)
5. Dependency Inversion Principle (DIP)


### 1. Single Responsibility Principle (SRP):
According to this principle ``every class should have a single responsibility or single job or single purpose. i.e It should have only one reason to change.``


### 2. Open/Closed Principle:
This principle states that ``software entities i.e class or modules or function should be open for extension but closed for modification``.

### 3. Liskov’s Substitution Principle (LSP):
This principle states that the, ``Derived or child classes must be substitutable for their base or parent classes.`` i.e any class that is child of a parent class, should be usable inplace of its parent class without any exception/error/issue.

### 4. Interface Segregation Principle (ISP):
This principle states that ``don't force a client to implement a method which is irrelevent to them.``
Here purpose of this principle is that we should not keep large no of methods in just on interface rather than we should create multiple interface having small no of functions.

### 5. Dependency Inversion Principle (DIP):
Below are two key points about **``Dependency Inversion Principle :``**
* High-level modules/classes should not depend on low-level modules/classes. Both should depend upon abstractions.
* Abstractions should not depend upon details. Details should depend upon abstractions.

i.e if a high module or class will be dependent more on low-level modules or class then your code would have tight coupling and if you will try to make a change in one class it can break another class which is risky at the production level.<br><br>



## References:
[1.] GeekForGeeks: [SOLID Principle in Programming: Understand With Real Life Examples](https://www.geeksforgeeks.org/solid-principle-in-programming-understand-with-real-life-examples/)<br>
[2.] Bob Martin: [Design Principles: Papers by Bob Martin](https://condor.depaul.edu/dmumaugh/OOT/Design-Principles/)

