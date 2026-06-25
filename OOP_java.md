## OOP JAVA:

<img src="Image/int3.jpeg" alt="App Screenshot" width="300" height="200">

## Q.1) What is Object-Oriented Programming?
State its properties.
### Answer: 
Object-oriented programming or popularly known as OOPs is a programming model or approach where the programs are organized around objects rather than logic and functions
In other words, OOP mainly focuses on the objects that are required to be manipulated instead of logic. This approach is ideal for the program's large and complex codes and needs to be actively updated or maintained.
Following are the main pillars/properties of OOP,
1) *Inheritance*: Inheritance is a process where one class acquires the properties of another.

2) *Encapsulation*: Encapsulation in Java is a mechanism of wrapping up the data and code together as a single unit.

3) *Abstraction*: Abstraction is the methodology of hiding the implementation details from the user and only providing the functionality to the users.

4) *Polymorphism*: Polymorphism is the ability of a variable, function, or object to take multiple forms.

<img src="Image/cute.jpeg" alt="App Screenshot" width="200" height="200">

## Q.2) Comment on method overloading and overriding in Java.
### Answer: 
In Java, method overloading is made possible by introducing different methods in the same class consisting of the same name.
Still, all the functions differ in the number or type of parameters. It takes place inside a class and enhances program readability. The only difference in the return type of the method does not promote method overloading.

### Method overriding 
It is the concept in which two methods having the same method signature are present in two different classes in which an inheritance relationship is present. A particular method implementation (already present in the base class) is possible for the derived class by using method overriding

<img src="Image/int1.jpeg" alt="App Screenshot" width="300" height="200">

## Q.3) What is the Java instanceOf operator?
### Answer: 
The instanceof in Java is also known as type comparison operator because it compares the instance with type. It returns either true or false. If we apply the instanceof operator with any variable that has a null value, it returns false Consider the following example,

*class Data{
public static void main(String args[]){
Data data =new Data();
System.out.println(data instanceof Data);
  }
}*

<img src="Image/int.jpeg" alt="App Screenshot" width="300" height="200">

 ## Q.4) What is the abstract class?
### Answer: 
A class that is declared as abstract is known as an abstract class. It needs to be extended and its method implemented.
It cannot be instantiated. It can have abstract methods, non-abstract methods, constructors, and static methods. It can also have the final methods which will force the subclass not to change the body of the method.

<img src="Image/int1.jpeg" alt="App Screenshot" width="300" height="200">

## Q.5) What is Inheritance in Java?
### Answer: 
Inheritance is a mechanism by which one object acquires all the properties and behavior of another object of another class. It is used for code reusability and method overriding.
The idea behind inheritance in Java is that you can create new classes that are built upon existing classes. When you inherit from an existing class, you can reuse methods and fields of the parent class.
Moreover, you can add new methods and fields to your current class also. Inheritance represents the IS-A relationship which is also known as a parent-child relationship. There are five types of inheritance in Java,

### Single-level Inheritance
### Multi-level Inheritance
### Multiple Inheritance
### Hierarchical Inheritance
### Hybrid Inheritance

