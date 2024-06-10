# blogs

Popular Core Java Interview Questions

# **Q1. What is the difference between Method Overloading and Method Overriding?**

**Method Overloading:**
  This occurs when two methods in the same class have the same name but different parameters. For example, we can have add(int a, int b), add(int a, int b, int c), and add(double a, double b).

**Method Overriding:**
  This occurs when a child class has a method with the same name and parameters as a method in its parent class but provides a different implementation. This allows the child class to override the behavior defined in the parent class.

# **Q2. What is the difference between Interface and Abstract class?**

**Abstract method:**
  This method is present in abstract class with a **abstract** keyword. It has no body only declaration. abstract method must me overridden in a child class extending Abstract class.

**Abstract class:**
  Abstract class is a class can have **0 or more** abstract methods or normal methods also.
  
**Interface:**
  Interface has atleast one abstract method. a keyword abstract is not needed in interface.
  All the methods in abstract class are abstract except static methods.  
