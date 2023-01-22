# nc-eshop-app-client

## Description
eShop-app-client is the client part of the CRM system for the buy of goods. 
The application consists SPA for clients and works with API server part. 
In this project I used basic CRUD operations. 
The application downloads information about currency exchange from the external `bank.gov.ua` API in xml format.
The customer can pay for the product in another currency. 
This project made to show my skills in Spring boot, Spring, JDBC, REST, OOP, SOLID, SQL. 

## Technologies
- Java 8
- Spring boot
- Spring
    - Spring security
- Oracle
- Flyway
- Lombok
- JAXB
- Thymeleaf
- TomCat

## How to use
- First, run the project. 
- You can see a list of products with quantity and price.
- You can change currency on the page.
- After that, you can complete the order and send it to the store manager.

## Setup
- Clone this project
- Prepare DB Oracle 
- Add your db configurations in application.properties (username, password, url)
````-
    spring.datasource.url=DB_URL
    spring.datasource.username=USER_NAME
    spring.datasource.password=USER_PASSWORD
````