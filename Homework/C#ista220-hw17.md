## Ricardo Rosa

### ISTA220 Homework 17

### C# 

***Read chapter 17, pages 369 – 398 in the C# Step by Step book.***

##### 1. What is a type parameter?
is a placeholder for a specific type that a client specifies when they instantiate a variable of the generic type.

##### 2. What does a type parameter do?
Specifies the types of objects on which they operate.

##### 3. How many type parameters can a generic class have?
Multiple types
Example: the Generic Dictionary class defined in the System.Collections.Generic namespace in the .NET Framework class library expects twotypes parameters: one type for keys, and another for the values.

##### 4. What is the difference between a generic class and a generalized class?
Generic class uses type parameters.

Generalized class take parameters of type object

##### 5. What is a constraint? How do you specify a constraint?
Limits the types types of parameters of a generic class to those that implement a particular set of interfaces and therefore provide the methods define by those interfaces.

##### 6. What is a generic method? How do you define a generic method?
Specify the types of the parameters and the return type by using a type parameter in a manner similar to that used when you define a generic class.

They are frequently used in conjunction with generic classes.

You define a generic method by using the same type parameter syntax you use when you create generic classes

##### 7. What do we mean when we say that a generic type interface is invariant?
Means that you can use only the type originally specified; so an invariant generic type parameter is neither covariant nor contravariant.

##### 8. What do we mean when we say that a generic type interface is covariant?
Enables you to use a more derived type than originally specified.

##### 9. Does covariance work with value types? Does it work with reference types?
No for Value types.


##### 10. What do we mean when we say that a generic type interface is contravariant?
It enables you to use a generic interface to reference an object of type B through a reference type A as long as type B derives from type A.
