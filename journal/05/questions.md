# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, and Delete. It refers to the functions that are needed to implement persistent storage.

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Create => Post
  > Read => Get
  > Update => Put
  > Delete => Delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object Relational Mapping. Relational.

04. Which two `HTTP` request types include a body?

  > Put & Post.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > Asynchronys | Synchronys

06. What are the three types of data relationships? Provide an example of each.

  > One-to-One - A "street" has a "name"
  > One-to-Many - A "burger" has "ingredients"
  > Bucketing - This is a combination of the two above. It alows you to peform something once and get a bunch of results
  > Many-to-Many - A "food item" may be made by many "chefs" but the "chef" can also make many "food items" 

07. What is middleware?

  > code will be passed through different peices of middleware in various places throughout the code, like a invisible checkpoint.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > Request | Response

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > ['tag', 'winter']

10. What is a ***virtual property***?

  > Virtual properties are meant to define certain objects so that you only have to concatenate once. 
