# myRetail-RESTful-service

## Technologies
Java JDK 1.8.0
Spring 2.0.2 Release
Maven 4.0.0
MonogoDB 3.6.4

## Database
database=products
collecitons=products
mongodb host=localhost
mongodb port=27017

## Local Build
Built using Eclipse, Run As Spring Boot App
http://localhost:8080/

## Directory
http://localhost:8080/products/ - shows all products
http://localhost:8080/products/{1} - getsProductByID and gets external API Info, Shows External API ID, Name, Local DB Price
http://localhost:8080/products{1} - PUT - Updates Price By ID
http://localhost:8080/about - Author Page
