## Ricardo Rosa

### ISTA322 Homework 4

### ASP.NET MVC


***Read chapter 4, pages 67 – 94 in the Pro ASP.NET MVC 5 book.***

#### 1. Using automatic properties is a shortcut that avoids several explicit steps. List the steps that the use of automatic properties avoids.
you only need to write public fields.

#### 2. Using the object initializer syntax is a shortcut that avoids several explicit steps. List the steps that the use of object initializers avoids.


#### 3. What is the purpose of creating extension methods?
adds the functionality I needed when you can't modify the class itself

#### 4. What is the one feature of extension methods that will always allow you to identify a method as an extension method?
The this keyword.

#### 5. How do you create an extension method that filters the results returned by the method on a user specified criterion?
You use a Yield keyword.

public static IEnumerable<Product> FilterByCategory(
		this IEnumerable<Product> productEnum, string categoryParam) {
foreach (Product prod in productEnum) 
{

if (prod.Category == categoryParam) {
yield return prod;

#### 6. Explain the syntax of a lambda expression. The term “lambda expression” originates in the lambda calculus developed by the mathematician Alonzo Church in the 1930’s. There is a class of programming languages that are based on the fundamental ideas of lambda calculus.


#### 7. This will require some outside research. What is the distinction between an anonmously typed variable and a dynamically typed variable?
- Anonymous types allow you to neglect explicitly writing out the type of each variable, but are still enforced at compile time. 

- Dynamic types are like reflection on steroids. Instead of grabbing the type information, and invoking, you can just pretend that the item exists, and let it try at run time. 


#### 8. You are having a discussion about C# with a friend of yours that uses another language. You are telling him about C#’s LINQ library. How would you describe to him the difference between LINQ’s SQL-like notation and LINQ’s dot notation?
LINQ is a SQL-like syntax for querying data in classes.

#### 9. What, exactly, does the await keyword do?
Applying the await keyword means I can treat the result from the GetAsync method as though it were a regular method and just assign the HttpResponseMessage object that it returns to a variable.

#### 10. What is the connection between await and the async keywords?
