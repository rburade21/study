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

### Static Keyword
The static keyword in Java is used for memory management mainly. We can apply static keyword with variables, methods, blocks and nested classes. The static keyword belongs to the class than an instance of the class.

The static can be:

1] Variable (also known as a class variable) - 
The static variable can be used to refer to the common property of all objects, The static variable gets memory only once in the class area at the time of class loading.

2]  Method (also known as a class method) - 
If you apply static keyword with any method, it is known as static method.

* A static method belongs to the class rather than the object of a class.
* A static method can be invoked without the need for creating an instance of a class.
* A static method can access static data member and can change the value of it.

3] Block - 
* Is used to initialize the static data member.
* It is executed before the main method at the time of classloading.

4] Nested class

### Abstract class 

Points to Remember
An abstract class must be declared with an abstract keyword.
* It can have abstract and non-abstract methods.
* It cannot be instantiated.
* It can have constructors and static methods also.
* It can have final methods which will force the subclass not to change the body of the method.
* Abstract class can have final, non-final, static and non-static variables.
* Abstract class can provide the implementation of interface.

### Interface

Java Interface also represents the IS-A relationship. It cannot be instantiated just like the abstract class.
* Since Java 8, we can have default and static methods in an interface.
* Since Java 9, we can have private methods in an interface.
* Interface has only static and final variables.

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

#### Why is the Java main method static?
It is because the object is not required to call a static method. If it were a non-static method, JVM creates an object first then call main() method that will lead the problem of extra memory allocation



[Advance Java ->](https://github.com/rburade21/study/blob/master/advance_java.md)
