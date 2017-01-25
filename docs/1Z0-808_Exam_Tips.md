# Exam Tips

* The classes and interfaces can be defined in any order of occurrence in java source code file

* Name of the source file should match the public class or interface defined in it

* More than one public class or interface can not be defined in a source file

* Classes and Interfaces defined in the same Java source code file can not be defined in separate packages.

* Classes and Interfaces imported using the import statement are available to all the classes and interfaces in the same Java source code file

* Command line parameters or Command line values are values that are passed to main method from the command line.

* All members from java.lang package is implicitly available without an import statement

* Members of named package can not access classes and packages defined in the default package

* Derived class can inherit and access protected members of its base class, regardless of the package in which its defined.

* Derived class in a separate package can not access protected members of its base class using reference variables.

* Watch out for invalid combinations of a java entity and an access modifier. Such code wont compile.

* An abstract class may or may not define an abstract method. But a concrete class can not define an abstract method.

* A method with an empty body is not an abstract method

* abstract modifier can not be applied to variables

* Static members can be accessed using object reference as well as by class names. Since static members belong to class and shared by all objects, its better to access by Class name. static and final modifiers are together used to define constants

* Static methods and static variables can not access instance members of a class.

* Static methods and static variables can be accessed using null references
