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

	Import statement enables you to use simple names instead of fully qualified names for classes and interfaces defined in separate packages
	
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
