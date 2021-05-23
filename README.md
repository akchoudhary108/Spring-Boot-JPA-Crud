# Spring-Boot-Crud-JPA

### 1. Open Eclipse -> Open Project from File System

### 2. Right click on project in eclipse and then Maven -> Update Projects 

### 3. Import src/main/java/resources/book.sql into MySQL database

### 4. Update database credential and other configuration into application.properties available in src/main/java/resources

### 5. Right click on Application.java file and run as Java Application

### 6. To get list of books call following endpoint with GET Request "http://localhost:8080/bookservice/books"

### 7. To Create New Book Use following url with POST Request "http://localhost:8080/bookservice/books" 

	set content type as in header as `application/json` and then set request body as raw with JSON 
	{
	    "name": "Java",
	    "author": "Anjani",
	    "publication": "IT Solution",
	    "category": "Programming",
	    "pages": 2000,
	    "price": 100
	  }

### 8.To get a particular book, use following url with `GET` request type in postman "http://localhost:8080/bookservice/books/id"

### 9.To update Book in database, use following url with `PUT` request type in postman "http://localhost:8080/bookservice/books/id"

	set content type as in header as `application/json`
	set request body as raw with JSON payload

	 {
	    "name": "Java",
	    "author": "Anjani",
	    "publication": "IT Solution",
	    "category": "Programming",
	    "pages": 2000,
	    "price": 100
	  }

### 10.To delete a particular Book from database, use following url with `DELETE` request type in postman "http://localhost:8080/bookservice/books/id"
