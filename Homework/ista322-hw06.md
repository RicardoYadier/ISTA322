## Ricardo Rosa

### ISTA322 Homework 6

### ASP.NET MVC


***Read chapter 6, pages 119 – 154 in the Pro ASP.NET MVC 5 book.***

#### 1. What is the primary idea that underlies Dependency Injection?
the idea is to decouple the components in an MVC application.

#### 2. Describe the role of interfaces in implementing a dependency injection container.
In combination with DI, interfaces creates instances of objects by creating
implementations of the interfaces they depend on and injecting them into the constructor

#### 3. List the three stages of building basic Ninject functionality, and briefly define each stage.
    
**The first stage is to prepare Ninject for use**

create an instance of a Ninject kernel, which is the object that is responsible   for resolving dependencies and creating new objects.

When I need an object, I will use the kernel instead of the new keyword

**The second stage of the process is to configure the Ninject kernel so that it understands which implementation objects I want to use for each interface I am working with.**

This statement tells Ninject that dependencies on the IValueCalculator interface   should be resolved by creating an instance of the LinqValueCalculator class.

**The last step is to use Ninject to create an object**

The type parameter used for the Get method tells Ninject which interface I am interested in and the result from this method is an instance of the implementation type I specified with the To method a moment ago

#### 4. What is the purpose of a custom dependency resolver?
Create instances of the classes it needs to service requests.

By creating a custom resolver, you can ensure that the MVC Framework uses Ninject whenever it creates an object–including instances of controllers

#### 5. What is the purpose of conditional binding? Describe how it works.
allows to specify which classes the kernel should use to respond to requests for particular interfaces

#### 6. Why is setting the object scope important when using dependency injection?
helps tailor the lifecycle of the objects that Ninject creates to match the needs of tne application.

#### 7. Briefly describe the Test Driven Development approach in developing an application.
TDD inverts the traditional development process: you start by writing tests for the perfect implementation of a feature, knowing that the tests will fail. You then implement the feature, creating each aspect of its behavior to pass one or more tests.


#### 8. Consider the Assert class. How do you access the methods of that class?
use the Assert.AreEqual method

#### 9. Why is it useful to mock objects when developing software?
Mock objects let you narrow the focus of your tests so that you only examine the
functionality in which you are interested.

#### 10. Briefly describe the two main issues that arise when attempting to do Unit Tests without the aid of some sort of mocking library.
First, you made the unit test complex and brittle. 

Second, and most troubling, you have extended the scope of the unit test so that it implicitly includes the MinimumDiscountHelper class.