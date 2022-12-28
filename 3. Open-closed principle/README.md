# Open-closed principle
## Short
This principle suggests that it is important to design components or modules in a way that allows them to be extended without modifying their existing code. This can help to make the program more flexible and easier to maintain.
## Long
The Open/Closed Principle (OCP) is a software design principle that states that software entities (such as classes and modules) should be open for extension but closed for modification. This means that they should be designed in such a way that they can be extended to add new functionality, but their existing behavior should not be modified.

The idea behind the OCP is to encourage designers and developers to create software that is easy to modify and extend, without requiring changes to the existing code. By following the OCP, designers can create software that is more flexible and maintainable, as new functionality can be added without changing the existing code.

One way to apply the OCP is to use abstraction and inheritance to define the relationships between different components of a system. For example, a base class could define the core functionality of a component, and derived classes could extend this functionality by adding new methods or behaviors. This way, the base class remains closed for modification, but the derived classes are open for extension.

Another way to apply the OCP is to use interfaces to define the relationships between different components of a system. An interface can define a set of methods that a class must implement, but it does not define the implementation of those methods. This allows for flexibility, as different classes can implement the same interface in different ways, and new functionality can be added to a system by implementing a new interface.

Overall, the Open/Closed Principle is a helpful guideline for designing systems that are easy to modify and extend, without requiring changes to the existing code. By following the principle, you can create systems that are more flexible and maintainable, and that are less prone to errors and inconsistencies.
## Explain with examples from non-programming activities
Imagine you are in charge of organizing a school library. You want to create a system that allows students to borrow and return books, but you also want to make it easy to add new features and functionality to the system in the future.

One way to apply the OCP to this task would be to use abstraction and inheritance to define the relationships between different components of the system. For example, you could create a base class called "Book" that defines the core properties and behaviors of a book, such as its title, author, and whether it is currently checked out. You could then create derived classes that extend this functionality, such as "Textbook" or "Novel," which could add additional methods or behaviors specific to those types of books. This way, the base class remains closed for modification, but the derived classes are open for extension.

Another way to apply the OCP to this task would be to use interfaces to define the relationships between different components of the system. For example, you could create an interface called "Checkoutable" that defines a set of methods that a class must implement in order to be checked out, such as "checkOut()" and "return()." You could then create classes that implement this interface, such as "Book," "Textbook," and "Novel," which could implement the methods in different ways depending on their specific needs. This allows for flexibility, as new functionality can be added to the system by implementing a new interface.

