## Core JAVA and OOPS

### Explain JDK, JRE and JVM
JVM core engine of JRE responsible to run java program and which uses libraries provided in java runtime. so we can call it as subset of JRE
JRE is resposible to provide runtime environmet while executing java program. it contains JVM and some libraries required by JVM.
JDK is resposible to provide development tools to developer to develop, compile and document. it is superset of all JVM and JRE.

### What is OOPS?
OOPS stands for object oriented programing structure is prgraming pardigm. which adheres to some priciples like abstraction, encapsulation, inheritance and polymorphism

### What are OOPS concepts?
abstraction, encapsulation, inheritance and polymorphism these all are oops concepts.

### What is object oriented programing language?
Langugae adhereing to OOPS concepts is object oriented programing language. it means everything we have to do as objects and their behaviour.

### Do you think java is pure object oriented programing language?
No, its not pure object oriented language as it has primitive types which counters the thing that everything is as object in OOPL. But they do have workaround call wrapper class to convert primitive types into the object types.
example: Smalltalk is pure OOPL

### What are all data types in java?
java has data types like short, int, string, boolean, float, long, double, byte

### What is super in java?
super is keyword used to point object of immidiate parent class. whenever you create object of subclass it implicitly creates object of parent class supper keyword points to this object.

### Can you have virtual functions in Java?
Yes, All functions in java are virtual by default.

### What is a nested class?
The nested class can be defined as the class which is defined inside another class or interface. We use the nested class to logically group classes and interfaces in one place so that it can be more readable and maintainable. A nested class can access all the data members of the outer class including private data members and methods.

### What are the disadvantages of using inner classes?
Inner classes increase the total number of classes used by the developer and therefore increases the workload of JVM since it has to perform some routine operations for those extra classes which result in slower performance.
IDEs provide less support to the inner classes as compare to the top level classes and therefore it annoys the developers while working with inner classes.

### Can we access the non-final local variable, inside the local inner class?
No, it must be constant to access.

### Explain OOPS concepts in briefly.
There are four oops concepts as
Abstraction : Abstraction is concept which say to hide implementation details and expose the functionalities. In real life we can map it like, we have bike it has engine which starts with self button, user dont need any impletation details that how that self start button works and how engine fires up. so here presing that selft start button is a functionality part we can say which is exposed by the bike.
programatically abstraction is achivable using abtract class or interfaces.

Encapsulation : Encapsulation is binding datambers and its behaviour together inside class. so we are binding data with code at single place in class. so in capsulation is achived at implentation side.
In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as data hiding.

Inheritance : Aquring properties of some other class into existing class is called as inheritance. in java we have multilevel, multiple in terms of interfaces, hibrid and heirachical inheritance.

Polymorphism : Polymorphism means having multiple forms. So in terms of java we have and interface can have multiple implementations. so it states its polymorphic behaviour.
so there are two types of polymorphism
Static polymorphism: static ploymorphism canbe achived by overloading methods. reloving of methods happens at comple time thats why it is called as static polymorphism.
Dynamic polymorphism: dynamic polymorphis can be achived only by overriding methods of parent class, this reloving of methods happens at runtime that why we call it as runtime or dynamic polymorphism.

### What features introduced in java 8?
lambda expression in introduced in java 8 to implement functional interface.
stream APIs introduced in java 8 to manipulate data in collections
predicates are also introduced
Annotations on data types
references to methods
Base64 class added for related operations
default and static method in introduced in interface.

### what is difference between abstract class and interface?
before java 8 no implentation was allowed inside an interface but in abstract class we have option from earlier verions.
being class we can only extend one class as multiple inheritance is not supprted for classes in java but we can implemet multiple interfaces.
being class abstract classes do have contructor where interface can not have contructor
Abstract class can contain variables with any access modifiers but in interface only public final static variables are allowed

### Can we override private and static methods?
No, we cannot overried these methods. private methods are not visible inside child class so we can not override them and static methods are class level methods so we can not override static methods also.

### What are immutable objects?
These are objects of which we can not change value. for example string is immutable. which means we can not mutate or change value of string once declared.

### How to make class immutable?
We need to make class final so that it can not be extended. we need to make feilds private and final so once they are initialisez one can not change their values.

### What design paterns you followed so far?
I have used singleton, dependacy injection, factory pattern i follwed in terms of creational pattern,, appraty from this i have used MVC, DAO pattern in terms of structural pattern and used startgy patter in terms of behavioural pattern for example i have used Comparators while sorting lists.

### How to make use of singleton?
we need no make contructor private and write private static feild of that class, after that we can write static getter method to create instance of class only if not created earlier.

### Can we overload main method?
Yes we can overload method, but jvm calls only main method having signature like public static void main(String args[])

## Advance Java

### What is JDBC how to connect with database?
JDBC is bridge to connect java applications with database
It has some steps.
1. Register driver class
2. Create and open connection
3. create statement object
4. write query
5. execute query
6. fetch results and process the data

### What is the life-cycle of a servlet?
Servlet is loaded
servlet is instantiated
servlet is initialized
service the request
servlet is destroyed

### Lifcycle methods of servlets?
public void init(ServletConfig config)	It is invoked only once when first request comes for the servlet. It is used to initialize the servlet.
public void service(ServletRequest request,ServletResponse)throws ServletException,IOException	It is invoked at each request.The service() method is used to service the request.
public void destroy()	It is invoked only once when servlet is unloaded.

### Difference between forward() method and sendRedirect() method ?
forward() method	sendRedirect() method
1) forward() sends the same request to another resource.	1) sendRedirect() method sends new request always because it uses the URL bar of the browser.
2) forward() method works at server side.	2) sendRedirect() method works at client side.
3) forward() method works within the server only.	3) sendRedirect() method works within and outside the server.

### What are the life-cycle methods for a JSP?
public void jspInit()	It is invoked only once, same as init method of the servlet.
public void _jspService(ServletRequest request,ServletResponse)throws ServletException,IOException	It is invoked at each request, same as service() method of the servlet.
public void jspDestroy()	It is invoked only once, same as destroy() method of the servlet.

### What are the JSP implicit objects?
1) out	JspWriter
2) request	HttpServletRequest
3) response	HttpServletResponse
4) config	ServletConfig
5) session	HttpSession
6) application	ServletContext
7) pageContext	PageContext
8) page	Object
9) exception	Throwable

### What is Spring?
Its is framework of java to design enterprise application.

### What are the advantages of spring framework?
Predefined Templates
Loose Coupling
Easy to test
Lightweight
Fast Development
Powerful Abstraction
Declarative support

### What is the difference between BeanFactory and ApplicationContext?
BeanFactory is the basic container whereas ApplicationContext is the advanced container. ApplicationContext extends the BeanFactory interface. ApplicationContext provides more facilities than BeanFactory such as integration with spring AOP, message resource handling for i18n

### What is depedancy injection?
Dependancy injection is what we can call it as design pattern where spring container creates and inject the depedancies all over the code. so that developer need not to creeat object for those depedancies. we need to specify beans and autowire the depedancies wherever we need and spring container find those beans and creates object for us and inject it in our code.

### What is IOC?
It is a technique which spring container follows. traditionally we have been creating objects by our own which is very tedious job. so what spring controller does is it takes this control to handle these object in its own way. this is what we call as inversion control.

### Whart are scopes of beans?
By defalut scope of beans is singleton, we can change it to prototype, session, reuqeust and global by spcifying scope in bean xml or by using @Scope("prototype"), global
1)	singleton	The bean instance will be only once and same instance will be returned by the IOC container. It is the default scope.
2)	prototype	The bean instance will be created each time when requested.
3)	request	The bean instance will be created per HTTP request.
4)	session	The bean instance will be created per HTTP session.
5)	globalsession	The bean instance will be created per HTTP global session. It can be used in portlet context only.

### What is work flow of spring MVC?

Whenever clients make request with perticuar path it goes to dispature survlet so whenever any request comes dispacture servlet is resopnsible to process that request further thats why we call it as fron- controller. so what it does is passes to respective controller and their method. when data and view name recived by the controller method it passes that data and view name to the view resolver. so view resolver populates data into view and return path to view after appending and prefixing paths and extensions and that view then served to the client by dispature servlet.

### What is the front controller class of Spring MVC?
Dispature Servlet is called as front controller which is responsible to handel all client requests

### What does @Controller annotation?
This annotation is used to mark it as controller class

### What does @RequestMapping annotation?
It is used to map the url with controller method

### What is webservice and why we need web services?
Webservices is way to interact with homogenious or hetrogenious systems be it deffirent applications or any home automation sytem part.

### How do u implemented security in your webservice?
I have used spring security for security and used jwt based authentication, for that i needed to writh filters.

### What is difference between @Component and @Bean?
Targeted result can be achived using both but the difference i found is that, @Component can be used with class and @Bean can be used with methods.

## Hibernate

### What is ORM?
Object relational mapping is used to store java object to the database, so class is mapped with table and its properties are mapped as columns in table.

### What is hibernate?
Hibernate is one of the ORM tool to store java objects in database.

### What are the types of object relationship in hibernate?
OneToMany, ManyToOne, OneToOne and ManyToMany

### What are states of object in hibernate?
Transient, Persisted and detached

## What are fetch policies present in hibernate?
There are two, One is lazy by default and egger.

### How do manage transaction in hibernate?
hibernate provides some methods related to transaction like gettransaction and beginTransaction and method to commit transactions

### How caching implemented in hibernate?
hibernate have two caches as level 1 and level 2 cache.
by default level 1 cache is enabled which is session scope and developer dont have to control over it. we need to enable level 2 cache using hibernate configuration properties and use tools like echcache, OScache, Swam etc. level 2 cache called as global because they share data among different session.
Also we need to mark classes with @Cacheable explicitly

### What is the difference between session.save() and session.persist() method?
save() - returns the identifier (Serializable) of the instance.	
persist() - Return nothing because its return type is void.

### What is the difference between get and load method?
1)	Returns null if an object is not found.	Throws ObjectNotFoundException if an object is not found.
2)	get() method always hit the database.	load() method doesn't hit the database.
3)	It returns the real object, not the proxy.	It returns proxy object.
4)	It should be used if you are not sure about the existence of instance.	It should be used if you are sure that instance exists.

### What is JPA?
JPA is specifiaction for interaction with ORM tools.






