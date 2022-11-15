# 2. Elementary Concept of Objects and Classes

### Objects

Software objects are conceptually similar to real-world objects that are created while writing a java program. They all have **_state_** and **_behavior_**. They store their _state_ in variables and expose their _behavior_ through methods.

<br>

**An object consists of**

- **_State:_** it is represented by attributes of an object.
- **_Behaviour:_** it is represented by methods of an object.
- **_Identity:_** it gives a unique name to an object and enables one object to interact with other objects.

<br>

**The 3 Steps to Create a new Object**

when creating an object from a class −
- **_Declaration_** − A variable declaration with a variable name with an object type.
- **_Instantiation_** − The 'new' keyword is used to create the object.
- **_Initialization_** − The 'new' keyword is followed by a call to a constructor.

----

### Message Passing

The objects can interact with each other. An object can pass information to another object and receive information as well.

----

### Class

A class is the blueprint from which individual objects are created. _It contains all the statements to create an object, its attributes, as well as statements to describe the operations that the object will be able to perform._ Thus, a class is also called **_object factory_**.

<img src="/Images/fruit-shop.png" alt="fruit shop (class and objects)" width="400"/>
Where the fruit shop is the class which contains fruits which are objects in that class.

----

### Difference Between Class and Objects

Objects | Class
:-------------:|:-------------:
Object is an instance of a class | Class is a template from which objects are created
Object is a real world entity | Class is a group of similar objects
Object is a physical entity | Class is a logical entity
Object is created through new keyword | Class is declared using class keyword
Object is created many times as per requirement | Class is declared once
Object allocates memory when it is created | Class doesn't allocated memory when it is created

----