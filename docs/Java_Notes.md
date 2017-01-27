## Java Basics

### Features of Java

#### Object Orientation

	Java emulates real-life object definition and behavior by defining classes, interfaces or enums.

#### Abstraction

	Java lets you abstract objects with only required properties and behavior.

#### Encapsulation

	Java classes encapsulate the state and behavior of an object.
	The state and behavior is protected from unwanted access and manipulation.

#### Inheritance

	Java classes can inherit other classes and implement interfaces.
	Interfaces can also inherit other interfaces.

#### Polymorphism

	Exhibiting different forms is known as Polymorphism. 
	Java enables instances of its classes to exhibit multiple behaviors for the same method calls.

#### Type Safety

	Varaibles must be desclared with the type before using it.
	Compile time checks ensure that variables are not assigned value of wrong type.

#### Automatic Memory Management

	Garbage collection is used for automatic memory management
	They reclaim memory from objects that are no longer in use.
	This also prevents memory leaks.

#### MultiThreading and Concurrency

	Java has support for mutithreading and concurrency through the classes and interfaces defined in the core API.

#### Security

* Java has multiple built-in security features to control access to the resources and program execution.
* It provides secure class loading and verification ensures execution of legitimate java code.
* It provides API for cryptography and public key infrastructure
* Java applications executing under Security manager controls access to resources using policy file.
* Java enables you to define digital signatures, certificates, key-stores to secure code and file exchanges.
* Signed code is distributed for execution

### Class

	A class is a design from which object is created.
	It is used to specify the attributes and behavior of an object.
	The attributes of an object are implemented using variables.
	The behavior is implemented using methods.

### Instance Variable

	Instance variables are used to store the state of an object.
	Each object has its own copy of instance variables.

### Static Variable
	
	Static variable is shared by all the objects of a class.

### Instance Method

	Instance Method are used to manipulate the instance variables.

### Static Method

	Static Method are used to manipulate the static variables.

### Constructor

	Constructor is used to create and initialize the objects of a class.
	A Class can define multiple constructors that accept different sets of method parameters


### Interface

* An interface specifies a contract for the classes to implement.
* Its a grouping of related methods and constants
* Methods can define default implementation. 
* If default implementation is not defined, Methods are implicitly abstract
* Interface can also define static methods

### Package

* Packages are used to group related set of classes and interfaces
* Packages also provide access protection and namespace management

### Import

	Import statement enables you to use simple names instead of fully 
	qualified names for classes and interfaces defined in separate packages
	
### Static Import

	Static Import statement enables you to import individual or all static members of a class

### Access Modifiers

* Access modifiers control the accessibility of a class or an interface and their members
* Local variables and method parameters can not be defined using access modifiers
* default, public, protected, private are the access modifiers 
* Members of Classes and Interfaces defined using public access modifier are accessible across all packages, from derived to unrelated classes
* Members of Classes and Interfaces defined using protected access modifier are accessible in the same package and in derived classes even if they are defined in separate packages
* Members of Classes and Interfaces defined using default access is visible and accessible only from within the package in which its defined. It can not be accessed from outside the package in which it resides.
* Members of Classes and Interfaces defined using private modifier is accessible only within themselves.

### Non Access Modifiers

* Non Access modifiers change the default behavior of a Java class and its members
* abstract
* final
* native
* static
* strictfp
* synchronized
* transient
* volatile

#### abstract

* This modifier can be used with classes, interfaces or methods 
* abstract class can not be instantiated
* abstract class can have zero or more abstract methods
* interface is an abstract entity by default
* abstract method does not have body. abstract method is implemented by derived class
* abstract modifier can not be applied to variables

#### final

* This modifier can be used with classes, methods or variables
* final modifier can not be applied to interfaces
* A class marked with final can not be extended by another class
* A variable marked with final can not be re-assigned a value. It can be assigned a value only once
* A reference variable marked with final can not be re-assigned another object, but you can call methods on its variable that modify its state.
* A final method defined in a base class can not be overridden by a derived class

#### native

* native method calls and makes use of libraries and methods implemented in other programming languages

#### static

* This modifier can be used with classes, interfaces, variables or methods
* Static variable is shared by all the objects of a class
* Static methods are not associated with objects of a class and can not use instance variables of a class. static methods are defined to manipulate static variables
* Non private static variables and methods are inherited by derived classes 
* Static methods and static variables can not access instance members of a class.
* Non static methods and variables can access the static variables and methods of a class.


#### strictfp

* Classes, interfaces and methods defined using this keyword ensure that calculations using floating point numbers are identical in all platforms
* This modifier can not be used with variables

#### synchronized

* synchronized method can not be accessed by multiple threads concurrently
* This modifier can not be used with classes, interfaces or variables 

#### transient

* transient variable is not serialized when the corresponding object is serialized.
* This modifier can not be used with classes, interfaces or methods 

#### volatile

* volatile variable's value can be safely modified by different threads
* This modifier can not be used with classes, interfaces or methods 

## Working with Java Data Types

### Primitive Data Types

* Numeric
** Signed
*** Integers
**** byte
**** short
****int
**** long
*** Floating Point
**** float
****double
** Unsigned
*** char
* Boolean
** boolean

