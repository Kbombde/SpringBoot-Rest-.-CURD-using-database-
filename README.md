# SpringBoot-Rest-.-CURD-using-database-

Description of SpringBoot REST CRUD Application with Book Management : 
This project is a Spring Boot RESTful application designed to manage a collection of books, showcasing CRUD (Create, Read, Update, Delete) operations using a relational database. It demonstrates the use of Spring Boot, Spring Data JPA, and RESTful principles for seamless database interaction and service-oriented architecture.

Key Features
Book Management :-
1.Add, view, update, and delete book records.
2.Manage book details such as name, price, author, genre, and publication date.

Search and Filter Functionality :-
1.2.Search for books by genre, name, author, or publication date.
Display all books or fetch specific records by criteria.

Dynamic Updates and Deletion :-
1.Update book details by name.
2.Delete books based on a price range.

REST API Integration :-
1.Fully functional APIs following RESTful standards.
2.HTTP methods like POST, GET, PUT, and DELETE for CRUD operations.

Layered Architecture :-
1.Entity Layer: Defines the BookInfo entity with fields mapped to the database.
2.Repository Layer: Interfaces for interacting with the database using Spring Data JPA.
3.Service Layer: Encapsulates business logic and interacts with the repository layer.
4.Controller Layer: Provides RESTful endpoints for client interaction.

Technologies Used :-
Spring Boot: Framework for building the application.
Spring Data JPA: Simplifies database access and management.
H2/MySQL/PostgreSQL: Relational database for storing book data.
Lombok: Reduces boilerplate code for getter, setter, and constructor methods.
Jakarta Persistence API: Manages database entities and operations.

API Endpoints :-
HTTP    Method	Endpoint	                Description
POST	/add-record-book	                Add a new book to the database.
GET	  /show-all	                        Retrieve all book records.
GET	  /show-by-genre/{genre}	          Retrieve books by genre.
GET	  /show-by-book-name/{name}	        Search books by name (partial match).
GET 	/show-by-author/{author}	        Search books by author's name.
GET	  /show-by-published-date/{date}	  Search books by publication date.
PUT 	/update-book-by-name/{name}	      Update a book's details by its name.
DELETE /delete-by-price-range/{min}/{max}	Delete books within a price range.
