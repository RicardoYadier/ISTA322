

## Ricardo Rosa

### ISTA220 Homework 13

### C# 

***Read chapter 13, pages 277 – 293 in the C# Step by Step book.***

##### 1. What is an interface as the term is used on object-oriented programmoing?
does not contain any code or data; it just specifies the methodand properties that a class inherits from the interface must provide.

##### 2. How do you define an interface?
you use the interface keyword instead of the class keyword.

##### 3. Can an interface have variables, fields, or properties?
No 

##### 4. How do you define a method in an interface?
exactly as as in class or a structure , except that you never specify an access modifier.

##### 5. Can you instantiate an object through an interface? Why or why not?
Yes. You remove the dependency on a concrete code.

##### 6. Using the new keyword, can you declare a reference to an interface?


##### 7. Can an object inherit from multiple interfaces? Can a class implement multiple interfaces? If so, how can it do so?
A class can implement an unlimited number of interfaces.

##### 8. What does it mean to explicitely implement an interface?


##### 9. What are the restrictions on interfaces?
You're not allowed to define any fields in an interface, not even static fields.

You're not allowed to define any constructor in an interface.

You're not allowed to define a destructor in an interface. a destructor contains the statements used to destroy an object instance.

You can't specify an access modifier for any method.

You can't nest any types inside an interface.

An interface is not allowed to inherit from a structure class, although an interface can inherit from another class.

##### 10. What is the difference between an abstract class and an interface?
An abstract class can contain abstract methods.


##### 11. What is an abstract method?
Similar in principle to a virtual method, except that it does not contain a method body.

##### 12. What is an sealed class?
Prevent a class from being used as a base class.

##### 13. What is an sealed method?
a method that can;t be override. 
You can only sealed a method declared with the override keyword and you declare the method as sealed override.