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
java has data types like short, int, string, boolean, float, long, double, byte.

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

### What is JDBC how to connect with database?
JDBC is bridge to connect java applications with database
It has some steps.
1. Register driver class
2. Create and open connection
3. create statement object
4. write query
5. execute query
6. fetch results and process the data

### What is depedancy injection?
Dependancy injection is what we can call it as design pattern where spring container creates and inject the depedancies all over the code. so that developer need not to creeat object for those depedancies. we need to specify beans and autowire the depedancies wherever we need and spring container find those beans and creates object for us and inject it in our code.

### Whart are scopes of beans?
By defalut scope of beans is singleton, we can change it to prototype, session, reuqeust and global by spcifying scope in bean xml or by using @Scope("prototype")

### What is work flow of spring MVC?

Whenever clients make request with perticuar path it goes to dispature survlet so whenever any request comes dispacture servlet is resopnsible to process that request further thats why we call it as fron- controller. so what it does is passes to respective controller and their method. when data and view name recived by the controller method it passes that data and view name to the view resolver. so view resolver populates data into view and return path to view after appending and prefixing paths and extensions and that view then served to the client by dispature servlet.

### What is webservice and why we need web services?
Webservices is way to interact with homogenious or hetrogenious systems be it deffirent applications or any home automation sytem part.

### How do u implemented security in your webservice?
I have used spring security for security and used jwt based authentication, for that i needed to writh filters.

### What is difference between @Component and @Bean?
Targeted result can be achived using both but the difference i found is that, @Component can be used with class and @Bean can be used with methods.

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

### What is JPA?
JPA is specifiaction for interaction with ORM tools.




