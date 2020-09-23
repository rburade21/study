# OOPS Concepts

## Abstraction
Abstraction means using simple things to represent complexity
for example button on TV we cant turn on/off tv by just pushing it without bothering how in works internally.
In java classes, objects, variables represents underlying complex data and code.

## Encapsulation
Encaptulation restricts access to implement security. Creating private feilds in class and providing limited access using other means like getters.
It creates protective barrier to keep data and code safe within class itself.

## Inheritance
Inheritance provides means to create new class having existing properties and attributes of it existing parent class.
It provides reusability in any language

## Polymorphism
Polymorphism is something in which programer provides multiple form to same type of object, method using features like method overloading, overriding.

## OOPs Interview Questions & Answers
### 1. What is OOPs?

OOPs refer to Object-Oriented Programming system in which programs are treated as a collection of objects. Each object is nothing but an example of a class.


### 2. Difference between Procedural programming and OOPs?

* Procedural Programming:

It is based on functions.
It reveals the data to the entire program.
It offers less scope of code reuse.
It follows a top-down programming paradigm.
It is complicated in nature, so it is hard to modify, extend and maintain.
* Object-oriented programming:

It is based on real-world objects.
It encapsulates the data.
It provides more scope of code reuse
It follows a bottom-up programming paradigm.
It is less complicated in nature, so it is easier to modify, extend and maintain.


### 3. What are the basic concepts of OOPs?

The basic concepts of OOPs are:

Inheritance
Encapsulation
Polymorphism
Abstraction

### 4. What is Abstraction?

Abstraction is an OOPs approach to construct the structure of the real-world objects. During the construction, only the general states and behaviours are taken, and more specific states and actions are left aside for the implementers.


### 5. What is Encapsulation?

Encapsulation is an OOPs concept to create and define the restrictions and permissions of an object and its member variable and methods. It is very simple to explain the concept is to make the member variables of a class private and providing public getter and setter methods.


### 6. What is Polymorphism?

Polymorphism is an instance of something in various forms. Java supports multiple forms of polymorphism like polymorphic method, polymorphic reference variable, polymorphic return types and polymorphic argument types.


### 7.  What is inheritance and its types?

A subclass can inherit the behaviours and states of its superclass are known as inheritance. There are various types of inheritance:

Hybrid Inheritance
Multiple Inheritance
Single Inheritance
Multi-level Inheritance
Hierarchical Inheritance

### 8. What is an object, method and class?

Object: An object is an instance of a class. It has its own identity and behaviour.
Class:  Class is a user-defined data type that contains variables, properties and methods.  It determines the properties of an object.
Method:  It is a set of instructions, also called a procedure that is to be performed on the given data.

### 9. What is Static Binding and Dynamic Binding?

Static Binding is a binding in which name can be combined with the class during collection time, and it is also called as early binding.

Dynamic Binding is a binding in which name can be identified with the class during execution time, and it is also known as Late Binding


### 10. What are a constructor and its types?

A constructor is a special kind of method that has the same name as the class and is used to initialize objects of that class. Type of constructor differs from language to language:

Private Constructor
Default Constructor
Copy Constructor
Static Constructor
Parameterized Constructor

### 11. Define overloading and overriding in OOPs?

Overloading is static binding, whereas overriding is productive binding. Overloading is the same method with different arguments, and it may or may not return the equal value in the same class itself.
Overriding is the same method names with the same arguments and return types identified with the class and its child class.

### 12. What are the access modifiers?

Access modifiers define the scope of the method or variable that can be accessed from other various objects.


### 13. What is an abstract class?

An abstract class cannot be proved. Formation of an object is not possible with an abstract class, but it can be inherited. An abstract class can only contain an abstract method, and java allows only abstract method in abstract class while other languages allow non-abstract method as well.


### 14. What are all the operators that cannot be overloaded?

The operators that cannot be overloaded are:

Member Selection
Scope Resolution
Member selection through a pointer to a function

### 15. What are manipulators?

Manipulators are the functions which can be used in conjunction with the insertion (<<) and extraction (>>) operators on an object. Examples are endl and setw

### 16. What is an Inline function?

An inline function is a technique used by the compilers and instructs to insert complete body of the function wherever that function is used in the program source code.

### 17. What is a virtual function?

A virtual function is a member function of a class, and its functionality can be overridden in its derived class. This function can be implemented by using a keyword called virtual, and it can be given during function declaration.

A virtual function can be declared using a token(virtual) in C++. It can be achieved in C/Python Language by using function pointers or pointers to function.

### 18. What is a friend function?

A friend function is a friend of a class that is allowed to access to Public, private, or protected data in that same class. If the function is defined outside the class cannot access such information.

A friend can be declared anywhere in the class declaration, and it cannot be affected by access control keywords like private, public, or protected.
### 19. What are the various types of constructors?

There are three types of constructors:

–  Default Constructor – With no parameters.

–  Parametric Constructor – With Parameters. Create a new instance of a class and also passing arguments simultaneously.

–  Copy Constructor – Which creates a new object as a copy of an existing object.

### 20. What are all the operators that cannot be overloaded?

Following are the operators that cannot be overloaded -.

Scope Resolution (::)
Member Selection (.)
Member selection through a pointer to function (.*)

### 21. What is static and dynamic Binding?

Binding is nothing but the association of a name with the class. Static Binding is a binding in which name can be associated with the class during compilation time, and it is also called as early Binding.

Dynamic Binding is a binding in which name can be associated with the class during execution time, and it is also called as Late Binding.

### 22. Which keyword can be used for overloading?

Operator keyword is used for overloading.
### 23. What is Object-oriented programming?

This is the most basic OOPs interview question. Your answer should be: 

Object-Oriented Programming refers to the programming paradigm defined using objects instead of only functions and methods. The objects contain data, called fields or attributes, and methods that provide the logic or supporting code. It provides capabilities such as inheritance, polymorphism, encapsulation, abstraction.
### 24. What are the advantages of Object-oriented programming?

Problems of any level of complexity can be supported by object-oriented programming.
Highly complex problems can be handled by object-oriented programming
It provides an efficient mechanism for code reuse using inheritance which reduces redundancy 
It provides a mechanism for hiding data
It is based on a bottom-up approach
It offers flexibility through polymorphism 
It improves maintainability of the code
### 25. What is Structural programming?

Structural programming refers to the traditional method of programming, which is based on functions. The overall program logic is divided into functions to provide a logical structure. It is based on a top-down approach. Structural programming is suitable for easy to moderately complex problems. 
### 26. What are the limitations of inheritance?

The inheritance requires more processing time for the programs as it has to navigate various classes during execution. Due to inheritance, the parent and child class are tightly coupled. When any changes are needed in the logic, it may require changes in both parent and child classes. 

If the inheritance is not correctly implemented, it can lead to undesired results. 

### 28. How do you explain the difference between overloading and overriding?

Overloading a method means that multiple methods share the same method name but have different arguments. However, in the case of the overriding, the child class can redefine the implementation of a method by retaining the same arguments. Another difference is that the overloading is resolved at compile-time while overriding is resolved at run time.

### 29. What is meant by an exception?

An exception is an event raised during a program execution caused by undesirable input or a condition that prevents further processing. An exception causes an interruption in the program’s normal execution and must be handled via exception handling logic to avoid the program’s termination

### 30. Should you always use Object-oriented programming? Are there any limitations of Object-oriented programming?

Though object-oriented programming offers many advantages, it has some disadvantages too. First of all, it has a steep learning curve compared to procedural programming. It may take a while to get used to thinking and program in terms of objects for many people. Secondly, it may take more experience to design a program in terms of objects. Using OOPs concepts for smaller programming tasks may not be efficient. 
