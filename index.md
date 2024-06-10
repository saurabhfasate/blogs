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

# **Q3. How to handle exception in Java?**

**Throw exception:**
Use throws in the method signature or throw in the method body.

**Try Catch:**
Enclose code that might throw exceptions in a try block, and handle exceptions in the catch block.

There are two types of exceptions:

- **Compile-time exceptions**: Must be handled.
- **Runtime exceptions**: Require code or logic changes.

**Finally:**
Finally block is used after try-catch block. Closing connections, releasing file handelers etc. these types of activities are performed in finally block. This block will always execute exception one or two scenarios where system got exited or any abrupt stop of code due to some issue in the environment or server. 


# **Que. Database**
*What is normalization?*
  Normalization is a database design technique to organize the data to reduce redundancy in the database.
*What is indexing?*
  Indexing is an optimization technique which will use b-tree or hashtable internally to imporve the data  retrieval. 
*What is primary key?*
  An unique identifier of a row in a table.
*What is foreign key?*
  Foreign key is used when we want to create a relation between two tables. A primary key of a table will be foreign key for another table.


