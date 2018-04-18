## Ricardo Rosa

### ISTA220 Homework 15

### C# 



***Read chapter 15, pages 329 – 352 in the C# Step by Step book.***

##### 1. What is the difference between a property and a field?
A property looks like a field but acts like a method.
A property can contain two block of codes.

##### 2. What is the difference between a property and a method?
properties are a special way f writing methods. it is about the expressing intent

##### 3. What is your understanding of encapsulation?


##### 4. Some languages are case insensitive, that is, an ‘a” and an “A” are considered to be the same letter. C# is case sensitive. What implications does this have regarding the naming of variables, methods, and other identifiers? Do you think that the difference in case in the initial character of two different identifiers is sufficient to distinguish them¿


##### 5. Give an example that is not in the book of an instance where you might want to use a read-only property. Give an example not in the book of an instance where you might want to use s write-only property.


##### 6. Can you think of a reason why you might ever want to make getters and setters private? Give an example. Also, make a case why getters and setters should never be private.


##### 7. What are restrictions on the use of properties?
You can assign value through a property of a structure or class only after the structure or class has been initialize.

You can't use a property as a ref or an out argument to a method.

A property can contain at most one get accesor and one set accesor. a property can't contain other methods, fields, or properties.

The get and set accesors can't take any parameters. The data being assigned is passed to the set accesor automatically by using the value variable.

You can't declare properties by using const.

##### 8. What is an object initializer? What is the syntax for an object initializer?