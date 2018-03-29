## Ricardo Rosa

### ISTA322 Homework 1

### ASP.NET MVC

***Read chapter 1, pages 1 – 10 in the Pro ASP.NET MVC 5 book.***

##### 1. What year was ASP.NET introduced?
2002

##### 2. Briefly describe ASP.NET Web Forms.
A set of UI components (pages, buttons, etc.) plus a stateful object oriented GUI programming model.

##### 3. Briefly describe ASP.NET.
A way to host .NET applications in IIS (Microsoft's Web Service Product), letting you interact with HTTP request and responses.

##### 4. Briefly describe .NET.
A multi-lenguage managed code platform (brand new at the time - a landmark own its own right)

##### 5. What is Representational State Transfer (REST)? This will take some independent research.
REST (REpresentational State Transfer) is an architectural style for developing web services. REST is popular due to its simplicity and the fact that it builds upon existing systems and features of the internet's HTTP in order to achieve its objectives, as opposed to creating new standards, frameworks and technologies.

##### 6. What is Agile Development? This will take some independent research.
Agile Software Development is an umbrella term for a set of methods and practices based on the values and principles expressed in the Agile Manifesto.

##### 7. What is unit testing?
Unit testing tools let you specify the behavior of individual classes or other small code units in isolation.

##### 8. What year was ASP.NET MVC introduced?
October 2007

##### 9. Describe URL routing. As part of your answer, discuss the concept of “clean URLs.”
Examine an incoming URL and figure out for which controller and action the request is intended.

Generate outgoing URLs. These are the URLs that appear in the HTML rendered from views so that a specific action will be invoked when the user clicks the link (at which point, it has become an incoming URL again).

Clean URLs give more weight to keywords meaning if you it would likely direct the user to the right URL

Easier to navigate by URLs

Easier to share when people understand it

It Doesn't expose technical details.

##### 10. What is the relationship between Microsoft’s .NET platform and ASP.NET MVC?
ASP.NET MVC platform addresses the weaknesses of ASP.NET Web Forms, its modern design delivers advantages to developers who want to write high-quality, maintainable code.

##### 11. Chapter 1 does not discuss the MVC pattern specifically, and in a sense this entire course is an extended examination of the MVC pattern. Using an independent resource (such as Wikipedia) briefly state the responsibility of 
##### (a) the model
Model objects are the parts of the application that implement the logic for the application s data domain. 

For example, a Product object might retrieve information from a database, operate on it, and then write updated information back to a Products table in SQL Server.
 
##### (b) the controller
Controllers are the components that handle user interaction, work with the model, and ultimately select a view to render that displays UI.

For example, the controller handles query-string values, and passes these values to the model, which in turn queries the database by using the values.

##### (c) the view
Views are the components that display the applications user interface (UI). 

An example would be an edit view of a Products table that displays text boxes, drop-down lists, and check boxes based on the current state of a Products object.
