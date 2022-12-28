# Liskov substitution principle
## Short
This principle suggests that it should be possible to use a subclass in place of a superclass without affecting the correctness of the program. This can help to ensure that the program is flexible and maintainable.
## Long
The Liskov Substitution Principle (LSP) is a software design principle that states that subtypes should be substitutable for their base types. This means that if a class is a subtype of another class, it should be able to be used in the same way as the base class without causing any problems.

The idea behind the LSP is to encourage designers and developers to create software that is easy to modify and extend, by creating a hierarchy of classes that can be easily substituted for one another. By following the LSP, designers can create software that is more flexible and maintainable, as new functionality can be added without breaking the existing code.

One way to apply the LSP is to use inheritance to define the relationships between different classes in a system. For example, you could create a base class that defines the core functionality of a component, and derived classes that extend this functionality in specific ways. By following the LSP, you can ensure that the derived classes are substitutable for the base class, and can be used in the same way without causing any problems.

Another way to apply the LSP is to use interfaces to define the relationships between different classes in a system. An interface can define a set of methods that a class must implement, but it does not define the implementation of those methods. This allows for flexibility, as different classes can implement the same interface in different ways, and new functionality can be added to a system by implementing a new interface.

Overall, the Liskov Substitution Principle is a useful guideline for designing software that is easy to modify and extend, and that is less prone to errors and inconsistencies. By following the principle, designers can create software that is more flexible and maintainable, and that is easier to understand and maintain.
## Explain with examples from non-programming activities
Imagine you are in charge of organizing a sports league for a group of children. You want to create a system that allows children of different ages and skill levels to participate in the league, but you also want to make it easy to add new types of sports to the league in the future.

One way to apply the LSP to this task would be to use inheritance to define the relationships between different types of sports in the league. For example, you could create a base class called "Sport" that defines the core properties and behaviors of a sport, such as the number of players, the type of equipment needed, and the rules of the game. You could then create derived classes that extend this functionality, such as "Soccer," "Basketball," and "Tennis," which could add additional methods or behaviors specific to those sports. By following the LSP, you can ensure that the derived classes are substitutable for the base class, and can be used in the same way without causing any problems.

Another way to apply the LSP to this task would be to use interfaces to define the relationships between different types of sports in the league. For example, you could create an interface called "TeamSport" that defines a set of methods that a class must implement in order to be a team sport, such as "numberOfPlayers()" and "getTeamSize()." You could then create classes that implement this interface, such as "Soccer," "Basketball," and "Baseball," which could implement the methods in
