# Aggregation repo #

## In Java, aggregation is an association between classes in which one class (the whole or container) contains a reference to another class (the part or component). Aggregation represents a “has-a” relationship, where one class contains objects of another class as part of its internal structure. In this repository, we have 2 examples of how to use it. To improve the readability of both the examples in this repository, I created 2 Java packages. The first is a lib package storing the object classes, and the second one is a main package where we can find classes that run our programs ##

### Employee register ###

The goal of this simple project is to list all the employees in the specific department. Also, the program gives us the full names of the people working in the department, given by the developer. Finally, it provides us with the number of employees who work in that department, and sums up all the salaries that they earn. Based on that, the program divides the total salaries of the employees by the number of employees to show us what is the average salary of an employee in that department.

Classes located in the lib package:

+ **Date** (Represents the date of birth of the employee)
+ **Employee** (It provides us with a name, start day, and a salary)
+ **EmployeeRegister** (An actual representation of how aggregation works)
+ **Name** (First and family name of the employee)
  

### Playlist ###

I implemented a small representation of how a simple playlist can be made in Java. The main class allows us to create a playlist (you can name it as you want) and add songs of your choice. Then it calculates the total number of songs and how long it will take to listen to all the songs in the playlist (in seconds). We can also see which song is found given by the specific index, play each song, remove a song, or move a song to a different place on a playlist. If the order of a playlist is not the desired one, we can shuffle the songs in it too!!!

Classes located in the lib package:

+ **Song** (Represents the song title, the song's duration, and the artist)
+ **Playlist** (Collection of Songs)
