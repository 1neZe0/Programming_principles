# Command-query separation
## Short
This principle suggests that a method or function should either perform an action or return a value, but not both. This can help to make the program more predictable and easier to understand and maintain.
## Long
The command-query separation (CQS) principle is a software design principle that states that a method or function should either perform an action (a command), or return a value (a query), but not both. The idea behind the CQS principle is to create systems that are easier to understand and maintain, by separating the responsibilities of different methods and functions.

One way to apply the CQS principle is to use methods that only perform actions, and do not return any values. These methods are called "commands," and they are used to perform tasks such as updating the state of an object, or triggering an action in the system. By using commands to perform actions, you can ensure that the methods are focused on a specific responsibility, and that they are easier to understand and maintain.

Another way to apply the CQS principle is to use methods that only return values, and do not perform any actions. These methods are called "queries," and they are used to retrieve information or data from the system. By using queries to retrieve information, you can ensure that the methods are focused on a specific responsibility, and that they are easier to understand and maintain.

Overall, the CQS principle is a useful guideline for designing software that is easy to understand and maintain. By following the principle, designers can create systems that are more flexible and modular, and that are less prone to errors and inconsistencies. By separating the responsibilities of different methods and functions, designers can ensure that the system is easier to understand and maintain, and that it is more resilient to change.
## Explain with examples from non-programming activities
Imagine you are in charge of organizing a school bake sale. You want to create a system that allows you to manage the bake sale, track sales, and communicate with volunteers and customers.

One way to apply the CQS principle to this task would be to use methods that only perform actions, and do not return any values. For example, you could create a "ProcessSale()" method that handles the process of processing a sale, and a "UpdateInventory()" method that handles the process of updating the inventory. These methods would only perform actions, and would not return any values. By using these methods to perform actions, you can ensure that they are focused on a specific responsibility, and that they are easier to understand and maintain.

Another way to apply the CQS principle to this task would be to use methods that only return values, and do not perform any actions. For example, you could create a "GetInventory()" method that returns the current inventory, and a "GetTotalSales()" method that returns the total sales for the bake sale. These methods would only return values, and would not perform any actions. By using these methods to retrieve information, you can ensure that they are focused on a specific responsibility, and that they are easier to understand and maintain.
