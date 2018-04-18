## Ricardo Rosa

### ISTA322 Homework 5

### ASP.NET MVC


***Read chapter 5, pages 95 – 118 in the Pro ASP.NET MVC 5 book.***

#### 1. What is a view engine?
takes in code spits out html

#### 2. What is Razor?
is a markup syntax that lets you embed server-based code into web pages using C# and VB.Net.

#### 3. What do views do? List two specific things in your answer to this question.
accepts input displays out.



#### 4. How does Razor respond when it encounters statements that begin with the at character (@)? Be specific.
it reads the code


#### 5. How does Razor respond when it encounters statements that begin with the at character followed by the colon (@:)? Be specific.
The @: characters prevent Razor from interpreting this as a C# statement, which is the default behavior when it encounters text.

#### 6. Describe how you implement a standard formatting for all pages in an ASP.NET application.
specify a layout

#### 7. What is the difference in using Razor to interpolate data values as stand-alone HTML elements and as attributes to HTML elements. What is the similarity?
it detracts from the patter of mvc

#### 8. What is a view start file and where is it located?
finds every view that refers to a layout

The views folder

#### 9. What is a Razor code block? What is the syntax of a Razor code block?
sets the value of the Layout property to null

@{ and closed with }

#### 10. Describe the different roles of action methods and views.
The action method passes the myProduct object to the view method

Action Method 

Do - Pass a view model object to the view

Doesn't Do - Pass formatted data to the view

View

Do - Use the view model object to present content to the user

Doesn't Do - Change any aspect of the view model object

#### 11. Describe the use of the @using statement. Give an example of how you would use it.
import the Razor.Models namespace.

@using Razor.Models
@model Product[]

which means that I can remove the namespace from the @model expression and from within the foreach loop.