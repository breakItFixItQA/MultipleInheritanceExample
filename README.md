# MultipleInheritanceExample
Multiple Inheritance Using Interfaces Example in Java
📋 Overview
This project demonstrates Multiple Inheritance in Java using interfaces.
In Java, multiple inheritance (inheriting from more than one parent) is achieved through interfaces, not classes.

It shows:

How a single class (Child4) can implement multiple interfaces (Interface1 and Interface2).

How properties (constants) and methods from multiple interfaces can be accessed and implemented.

📂 Project Structure
Interface1:

Constant: commonTrait (String, public static final by default)

Abstract Method: method1()

Interface2:

Constant: uniqueSkill (String)

Abstract Method: method2()

Child4 class (implements Interface1 and Interface2):

Property: name (String)

Implements both method1() and method2() with custom behavior.

MultipleInheritanceExample class:

Contains the main() method.

Creates an instance of Child4.

Demonstrates calling properties and methods from multiple interfaces.

🚀 How It Works
The Child4 class:

Implements both method1() (from Interface1) and method2() (from Interface2).

Defines its own property name.

The main() method:

Creates an object of Child4.

Calls implemented methods and accesses interface constants.

🛠 Example Output
vbnet
Copy
Edit
Child's name: Alex
Method1 from Interface1
Method2 from Interface2
Common Trait: Hardworking
Unique Skill: Creative Thinking
📚 Concepts Demonstrated
Multiple Inheritance via Interfaces

Interface Constants and Methods

OOP Principles in Java
