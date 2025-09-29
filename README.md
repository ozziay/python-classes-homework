# python-classes-homework
sports.py — Good Example
 The `Sports` class is designed properly using OOP principles
 It contains a list of 5 sports:
  ["Football", "Basketball", "Volleyball", "Handball", "Rugby"]
The class has a method show() that prints the list

Why this is good:
Each instance has its own copy of the sports list
Methods are clearly defined inside the class
Easy to extend or modify without affecting other instances

hospital.py - Bad Example
The show() method prints the list

Why this is bad:
The list is shared across all instances (class variable)
Changing the list in one instance affects all other instances
Not ideal for real-world OOP usage but works for simple examples

bakery.py - Ugly Example 
Why this is very bad:

Uses a global variable instead of instance variables
The show() function is not a class method
Only works with the single global object b
Not scalable or reusable; demonstrates poor OOP practice


