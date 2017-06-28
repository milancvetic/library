Day 2 Project startup and introduction to Spring framework, MVC pattern, REST, JUnit
====================================================================================

Project startup
---------------

Today we will start the project, make sure you have everything installed from the previous day, but at the minimum:

 *  JDK
 *  Eclipse IDE
 *  Gradle build system
 *  Git version control system


Reading - official docs
-------

*   [Spring framework](https://spring.io/docs)
*   [Dependency injection](https://martinfowler.com/articles/injection.html)
*   [MVC pattern](link here**)
*   [Domain and Service layer](link here**)
*   [REST and HTTP protocols](link here**)
*   [JUnit](www.junit.org)

Concepts
--------

*   Spring beans, containers, bean wiring
*   Dependecy injection example
*   Basic CRUD operations (Create, Read, Update, Delete)
*   Naming conventions
*   Gradle configuration/tasks
*   Request mapping/REST endpoints
*   Unit testing

Step 1 - Project startup
------------------------

1.  Create new Java Web project in Eclipse and choose Gradle as build system and name it library, with the directory
of your choosing (your working default directory will be just fine)
2.  Configure Gradle to for first-time build.

Step 2 - Creating domain and service layers
-------------------------------------------

1.  Create base package and create an additonal package named 'domain'
2.  Create two domain classes: Category
3.  Add the corresponding service layer
4.  Add in-memory implementation for Category entity, which later will be replaced with persistance layer.

Step 2 - Assignment
-------------------

Add the Book entity to project with the folowing properties: Id, Name, Category, ISBN
No. of pages, publish date.

Step 3 - Unit testing
---------------------

1.  Add unit tests for service in-memory implementation for Category.

Step 3 - Assignment
-------------------

Add unit tests for Book service implementation.

Step 4 - Adding controller
--------------------------

1.  Add controller with appropiate request mappings.
2.  Retrieve the in-memory date with Restful client (Postman) and examine the result set (JSON)

Step 4 - Assignment
-------------------

Add book controller with request mappings /books and /books/id and implement CRUD operations.
Test the new controller with REST client Postman.