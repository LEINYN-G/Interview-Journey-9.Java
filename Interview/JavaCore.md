## Java Core

<img src="Image/interview.jpeg" alt="App Screenshot" width="300" height="200">

### Q.1.) Explain the use of the "final" keyword in variable, method, and class.

#### Answer: 
In Java, the final keyword is used as defining something as constant /final and represents the non-access modifier

final variable: When a variable is declared as

##### *1) final in Java, the value can't be modified once it has been assigned. If any value has not been assigned to that variable, then it can be assigned only by the constructor of the class.*

##### 2) final method: A method declared as final cannot be overridden by its children's classes. A constructor cannot be marked as final because whenever a class is inherited, the constructors are not inherited. Hence, marking it final doesn't make sense.

##### 3) final class: No classes can be inherited from 3 the class declared as final. But that final class can extend other classes for its usage.

<img src="Image/int.jpeg" alt="App Screenshot" width="400" height="200">

### Q.2.) What are constructors in Java?

#### Answer: 
In Java, a constructor refers to a block

of code that is used to initialize an object. It must have the same name as that of the class. Also, it has no return type and it is automatically called when an object is created

There are two types of constructors:

##### Default Constructor: 
*In Java, a default constructor is the one that does not take any inputs. In other words, default constructors are the no-argument constructors which will be created by default in case no other constructor is defined by the user. Its main purpose is to initialize the instance variables with the default values.*
##### Parameterized Constructor: 
*The parameterized constructor in Java is capable of initializing the instance variables with the provided values. In other words, the constructors which take the arguments are called parameterized constructors.*

<img src="Image/int2.jpeg" alt="App Screenshot" width="400" height="200">

 ### Q.3.) What is an object-oriented paradigm?

#### Answer: 
It is a programming paradigm based on objects having data and methods defined in the class to which it belongs. The object-oriented paradigm aims to incorporate the advantages of modularity and reusability.

Objects are the instances of classes that interact with one another to design applications and programs. These are the following features of the object-oriented paradigm

*Follows the bottom-up approach in program design.*

Focus on data with methods to operate upon the object's data

Includes concepts like encapsulation and abstraction which hides the complexities from the user and show only functionality.

Implements the real-time approach like inheritance, abstraction, etc.

<img src="Image/int1.jpeg" alt="App Screenshot" width="400" height="200">

### Q.4.) What is an exception in Java?

#### Answer:
An exception is an event that occurs during the execution of a program that disrupts the normal flow of the program's instructions

When an error occurs within a method, the method creates an object and hands it off to the runtime system. The object, called an exception object, contains information about the error, including its type and the state of the program when the error occurred.

Creating an exception object and handing it to the runtime system is called throwing an exception.

After a method throws an exception, the runtime system attempts to find something to handle it. The set of possible "somethings" to handle the exception is the ordered list of methods that had been called to get to the method where the error occurred. The list of methods is known as the call stack.

<img src="Image/int3.jpeg" alt="App Screenshot" width="400" height="200">

### Q. What is an array in Java?

#### Answer: 
An array in Java is a data structure that allows us to store multiple values in a single variable. In simple words, using an array, we can group various data items into a single container

More precisely, an array is a fixed-size sequential collection of elements. These elements have to be of a similar type, this means an array can store multiple values of the same data type. These elements are stored in contiguous memory locations as illustrated in the above image.

<img src="Image/cute.jpeg" alt="App Screenshot" width="210" height="200">

##### *Yayy! Believe In Urself!!*
