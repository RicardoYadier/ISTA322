## Ricardo Rosa

### ISTA220 Homework 14

### C# 

***Read chapter 14, pages 305 – 328 in the C# Step by Step book.***

##### 1. What is the difference between a managed resource and an unmanaged resource?
 The basic difference between a managed and unmanaged resource is that the garbage collector knows about all managed resources.

##### 2. When is memory for an object (reference type) allocated? When is the memory deallocated?
Memory is allocated when "New" is used. When the reference count goes to zero.

##### 3. What is a destructor?
Performs any tidying up that's required when an object is garbage collected.

##### 4. What is the difference in syntax between a constructor and a destructor?
the syntax for writing a destructor is tilde (~) followed by the name of the class.

##### 5. Give some examples of scarce resources. Why would you want to manage scarce resources?
Memory, Database Connections, File Handles

##### 6. What is exception-safe disposal?
Release the resource yourself

##### 7. How do you think that the using statement works for resource management? Give an informal, English language, explanation of how it works.
Provides a clean mechanism for controlling the lifetime of resources.

##### 8. What ill effects could result from attempting to dispose of a resource more than once?


##### 9. We will look at threads later in the term. For now, what is your understanding of how threads interact with resource management? A good guess is a sufficient answer to this question.


##### 10. Why does the book recommend not attempting to force the garbage collector? Are their any exceptions to this recommendation?
because you can seriously impair the performance.