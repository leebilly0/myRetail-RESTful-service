# myRetail-RESTful-service

## Technologies
Java JDK 1.8.0<br>
Spring 2.0.2 Release<br>
Maven 4.0.0<br>
MonogoDB 3.6.4<br>

## Database
database=products<br>
collecitons=products<br>
mongodb host=localhost<br>
mongodb port=27017<br>

## Local Build
Built using Eclipse, Run As Spring Boot App<br>
http://localhost:8080/<br>

## Directory
http://localhost:8080/products/ - shows all products<br>
http://localhost:8080/products/{1} - getsProductByID and gets external API Info, Shows External API ID, Name, Local DB Price<br>
http://localhost:8080/products{1} - PUT - Updates Price By ID<br>
http://localhost:8080/about - Author Page<br>

## Screenshots
![alt text](https://github.com/leebilly0/myRetail-RESTful-service/blob/master/1_Data_in_Mongo_DB_exposed_through_API.png)
