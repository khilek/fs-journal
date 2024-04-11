# Intro to Server side concerns with JavaScript

1.  What do the letters of the acronym `CRUD` stand for?

> Create, Read, Update, Delete

2.  Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

C - Post
R - Get
U - Put
D - Delete

3.  What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

> Object-Relational Mapping

4.  Which two `HTTP` request types include a body?

> Post & Put

5.  In a/an **\_\_\_** coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an **\_\_\_** coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run. Fill in the blanks.

> Synchronous & Asynchronous

6.  What are the three types of data relationships? Provide an example of each.

> 1:1 - Author : Address
> 1:N - Blog : Comments
> N:M - Book : Author

7.  What is middleware?

> Body parser - middleware – takes in request bodies and makes sure they are in a usable format

8.  The **request** pipeline delivers information from the client while the **response** pipeline returns it. Fill in the blanks.

> Request & Response

9.  Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

> ?tag=winter

10. What is a **_virtual property_**?

> They are additional model functions returning values based on the default schema fields.
