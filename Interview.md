## INTERVIEW ( Java Basics)

<img src="Image/interview.jpeg" alt="App Screenshot" width="300" height="200">

*Q.1.) Talk about the main() method in Java. Explain all its parts and concepts involved in it.*
### Answer:
The main() method in Java is the entry point for any Java program. It is always Written as puboic static void main(String[] args). Here,
#### public: 
It is an access modifier, which is used to specify who can access this method.
Public means that this method will be accessible by any class.
#### Static: 
It is a keyword in Java that identifies it as class-based. The main() is made static in Java so that it can be accessed without
creating the instance of a class. In case, the main() is not made static then the compiler will throw an error as main() is caled by the JVM before any objects are made and only staic methods can be directly invoked via the class.
#### void:
It is the return type of the method. The void signifies that the method will not return any value.
#### main:
It is the name of the method which is searched by JVM as a starting point for an application with a particular signature only . It is the method where the main execution occurs.
#### String args[]:
It is the parameter passed to the main method.

<img src="Image/int.jpeg" alt="App Screenshot" width="400" height="200">

*Q.2.) What do you understand about the Java Virtual Machine? State the difference between JDK, JRE, AND JVM.
### Answer:
Java Virtual Machine is a virtual machine that enables the computer to run the Java program . It acts like a run-time engine which calls the main method present in the Java code

JVM is the specification that must be implemented in the computer system. The Java code is compiled by JVM to be a bytecode that is machine-independent and close to the native code.
#### JVM:
It is an acronym for Java Virtual Machine. It is an abstract machine that provides the runtime environmentin which the Java bytecode can be executed.
#### JRE:
It stands for Java Runtime Envirionment. It is the implementation of JVM. The Java Runtime Environment is a set of software tools that are used for developing Java applications. It is used to provide the runtime environment. It is the implementation of JVM. It physically exists and contains a set of libraries + other files that JVM uses at runtime.
#### JDK:
It id an acronym for Java Development Kit. It is a software development encironment that is used to develop Java applications and applets. It physically exists and contains JRE + development tools.

<img src="Image/int1.jpeg" alt="App Screenshot" width="400" height="200">

*Q.3.) What are the various access specifiers in Java?
### Answer:
In Java, access specifiers are the keywords that are used to define teh access scope of the method, calss , or variable. In Java, there are four access specifiers as given below

#### public:
The classes, methods, or variables which are defined as public, can be accessed by any calss or method.
#### protected:
Protected members can be accessed by the class of the same package, or by the sub-class fo this class, or within the same class.
#### default:
The default members are accessible within the package only. By default, all the classes, methods, and variables are of default scope.
#### private:
The private class, methods, or variables defined as private can be accessed within the class only.

<img src="Image/int2.jpeg" alt="App Screenshot" width="400" height="200">

*Q.4.) What is an infinite loop in Java? Explain with an example.*
### Answer
An infinite loop is an instruction sequence in Java that loops endlessly when a functional exit isn't ment. This type of loop can be teh result of a programming error or may also be a deliberate action based on the application behavior.

An infinite loop will terminate automatically once the application exits
_demo:_

##### public class Demo {
#####   public static void main(String[] arg) {
#####    for(;;) {
#####      System.out.println("Welcome to Java X!");
#####     }
#####    }
#####  }

<img src="Image/int3.jpeg" alt="App Screenshot" width="400" height="200">

*Q.5.) What do you understand about an instance variable and a local variable?*
### Answer
Instance variables are those variables that are accessible by all the methods in teh calss. They are declared outside the methods and inside the class. These variables describe the properties of an object and remain bound to it at any cost

All the objects of the class will have their copy of the variables for utilization. If any modification is done on these variables, then only that instance will be impacted by it, and all other class instances continue to remain unaffected.

<img src="Image/cont.jpeg" alt="App Screenshot" width="400" height="100">

Next to Java-core.md file



