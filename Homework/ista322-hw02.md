## Ricardo Rosa

### ISTA322 Homework 2

### ASP.NET MVC

***Read chapter 2, pages 11 – 50 in the Pro ASP.NET MVC 5 book.***

##### 1. Describe what a controller does in the MVC design pattern.
In ASP.NET MVC, controllers are just C# classes

They handle incoming request.

Meaning you can invoke it from the Web via some URL to perform an action.

##### 2.  What does HomeController.cs do?
A controller is responsible for controlling the way that a user interacts with an MVC application.

##### 3. What is the name of the routing configuration file? Where is it located?
RouConfig.cs in the Appstart folder


##### 4. What is Razor? How does Razor treat an expression beginning with the at symbol (@)?
It reads the c#code and translates it to HTML

Razor is an Expression.

Razor looks for expressions like the one I added in the listing and processes them.

When an @ symbol is followed by a Razor reserved keyword, it transitions into Razor-specific markup

##### 5. How do View methods work?
It locates the Index.

##### 6. What is the purpose of MVC models?
Contains all the guts of what you do.

Everything should be contained in the model. 

##### 7. What is a strongly typed view and why do we use strongly typed views?
A strongly typed view is intended to render a specific domain type, and if I specify the type I want to work with (GuestResponse in this case), MVC can create some helpful shortcuts to make it easier.

##### 8. What is the purpose of setting a start page URL?
Can build out the contents of RsvpForm.cshtml to make it into an
HTML form for editing GuestResponse objects,

##### 9. Describe the differences between HTTP GET and HTTP POST.
HTTP GET

A GET request is what a browser issues normally each time someone clicks a link. This version of the action will be responsible for displaying the initial blank form when someone first visits /Home/RsvpForm.

HTTP POST

By default, forms rendered using Html.BeginForm() are submitted by the browser as a POST request. This version of the action will be responsible for receiving submitted data and deciding what to do with it.

##### 10. Describe the two approaches to validation in web applications.
Domain Model

User Interface

##### 11. What is the role of Cascading Style Sheets (CSS) in web development?
 When changes are made in one style sheet, CSS enables these changes across all the style sheets, much like the cascading or ripple effect of a waterfall.