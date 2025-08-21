# Aggregation repo #

## In Java, aggregation is an association between classes in which one class (the whole or container) contains a reference to another class (the part or component). Aggregation represents a “has-a” relationship, where one class contains objects of another class as part of its internal structure. In this repository, we have 2 examples of how to use it. To improve the readability of both the examples in this repository, I created 2 Java packages. The first is a lib package storing the object classes, and the second one is a main package where we can find classes that run our programs ##

### Employee register ###

The goal of this simple project is to list all the employees in the specific department. Also, the program gives us the full names of the people working in the department, given by the developer. Finally, it provides us with the number of employees who work in that department, and sums up all the salaries that they earn. Based on that, the program divides the total salaries of the employees by the number of employees to show us what is the average salary of an employee in that department.

Classes located in the lib package:

+ Date (Represents the date of birth of the employee)
+ Employee (It provides us with a name, start day, and a salary)
+ EmployeeRegister (An actual representation of how aggregation works)
+ Name (First and family name of the employee)
  

### Playlist ###
