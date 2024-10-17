# SystemDesign_LLD
Notes on SOLID principles, UML diagrams, design patterns etc

Single Responsibility Principle -

A class should have only one reason to change

Open closed principle -

Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification

“Imagine you have a class called PaymentProcessor that processes payments for an online store. Initially, the PaymentProcessor class only supports processing payments using credit cards. However, you want to extend its functionality to also support processing payments using PayPal.”

Liskov substitution principle -

Derived or child classes must be substitutable for their base or parent classes

“One of the classic examples of this principle is a rectangle having four sides. A rectangle’s height can be any value and width can be any value. A square is a rectangle with equal width and height. So we can say that we can extend the properties of the rectangle class into square class.”

Interface Seggregation principle -

do not force any client to implement an interface which is irrelevant to them

Example: Waiter having different menus for vegetarian, non vegetarian and Beverages.


Dependency inversion principle -

High-level modules should not depend on low-level modules. Both should depend on abstractions

https://www.geeksforgeeks.org/solid-principle-in-programming-understand-with-real-life-examples/