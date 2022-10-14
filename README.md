# Tryy3

Problem Statement - To create a Spring Boot Rest API using Spring Data Jdbc with PostgreSQL Database for a Tutorial application that:
Each Tutorial has id, title, description, published status.
Apis help to create, retrieve, update, delete Tutorials.
Apis also support custom finder methods such as find by published status or by title.
These are APIs that we need to provide:

Methods	Urls	Actions
POST	/api/tutorials	create new Tutorial
GET	/api/tutorials	retrieve all Tutorials
GET	/api/tutorials/:id	retrieve a Tutorial by :id
PUT	/api/tutorials/:id	update a Tutorial by :id
DELETE	/api/tutorials/:id	delete a Tutorial by :id
DELETE	/api/tutorials	delete all Tutorials
GET	/api/tutorials/published	find all published Tutorials
GET	/api/tutorials?title=[keyword]	find all Tutorials which title contains keyword.
– We make CRUD operations & finder methods with Spring Data Jdbc.

– The database will be PostgreSQL by configuring project dependency & datasource.
 
 Aim was to understand - 1. How to configure Spring Data JDBC to work with Database
2. How to define Data Models and Repository interfaces
3. Way to create Spring Rest Controller to process HTTP requests
4. Way to use Spring JdbcTemplate to interact with PostgreSQL Database. 
