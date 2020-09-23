[<- Back to index](https://github.com/rburade21/study)

### Types of variables in java
There are three types of variables in Java:

* local variable -
A variable declared inside the body of the method is called local variable. You can use this variable only within that method and the other methods in the class aren't even aware that the variable exists.
A local variable cannot be defined with "static" keyword.


* instance variable - 
A variable declared inside the class but outside the body of the method, is called instance variable. It is not declared as static.
It is called instance variable because its value is instance specific and is not shared among instances.
* static variable - 
A variable which is declared as static is called static variable. It cannot be local. You can create a single copy of static variable and share among all the instances of the class. Memory allocation for static variable happens only once when the class is loaded in the memory.

### Data Types
There are 8 types of primitive data types:

* boolean data type
* byte data type
* char data type
* short data type
* int data type
* long data type
* float data type
* double data type


### Questions

#### Can we overload the main method?
Yes, but we can not call it

#### A Java Constructor returns a value but, what?
It return current instance of class

#### Can we create a program without main method?
Yes we can do it using static block

#### What are the 6 ways to use this keyword in Java?
* this can be used to get the current object.
* this can be used to invoke current object's method.
* this() can be used to invoke current class constructor.
* this can be passed as a parameter to a method call.
* this can be passed as a parameter to a constructor.
* this can be used to return the current object from the method.

#### Can we override static methods in java?
We can declare static methods with same signature in subclass, but it is not considered overriding as there won't be any run-time polymorphism. Hence the answer is 'No'

#### What is the covariant return type?
covariant return type of a method is one that can be replaced by a "narrower" type when the method is overridden in a subclass

#### Why use instance initializer block?
Instance Initializer block is used to initialize the instance data member. It run each time when object of the class is created. The initialization of the instance variable can be done directly but there can be performed extra operations while initializing the instance variable in the instance initializer block.

#### What is a marker or tagged interface?
A marker interface is an interface that has no methods or constants inside it. It provides run-time type information about objects, so the compiler and JVM have additional information about the object. A marker interface is also called a tagging interface

#### What is runtime polymorphism or dynamic method dispatch?
Method overriding is one of the ways in which Java supports Runtime Polymorphism. Dynamic method dispatch is the mechanism by which a call to an overridden method is resolved at run time, rather than compile time.

#### What is object cloning?
The object cloning is a way to create an exact copy of an object. For this purpose, the clone() method of an object class is used to clone an object
 
[Advance Java ->](https://github.com/rburade21/study/blob/master/advance_java.md)
