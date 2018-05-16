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
Launch Mongodb<br>
Built using Eclipse, Run As Spring Boot App<br>
http://localhost:8080/ for Application<br>
http://localhost:27017/ for DB<br>

## Directory
http://localhost:8080/products/ - shows all products<br>
http://localhost:8080/products/{1} - getsProductByID and gets external API Info, Shows External API ID, Name, Local DB Price<br>
http://localhost:8080/products{1} - PUT - Updates Price By ID<br>
http://localhost:8080/about - Author Page<br>

## Screenshots (Download images to see them more clearly)
Working MongoDB showing all products when http://localhost:8080/products/ is hit<br>
![alt text](https://raw.githubusercontent.com/leebilly0/myRetail-RESTful-service/master/1_Data_in_Mongo_DB_exposed_through_API.png)<br>

JSON INFO of ID 13860428<br>
![alt text](https://raw.githubusercontent.com/leebilly0/myRetail-RESTful-service/master/2_Data_By_ID_13860428.png)<br>

Before and After External API piece was added to update name of product<br>
![alt text](https://raw.githubusercontent.com/leebilly0/myRetail-RESTful-service/master/3_Before_After_External_API.png)<br>

Image of Current DB<br>
![alt text](https://raw.githubusercontent.com/leebilly0/myRetail-RESTful-service/master/4_Mongo_DB.png)<br>
