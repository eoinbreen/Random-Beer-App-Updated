# Random Beer App Updated

The Random Beer App is a Spring Boot application with a Rest API. The data layer is using spring data
repository and JPA with an in-memory HSQL database.

The front end is done with html5, bootstrap CSS for responsive mobile frendly design. 

Jquery is used to send requests to the back end API

To build and start the app, open a command window in the root directory and run the following commands:

- mvn package

- cd target

- java -jar Random-Beer-App-0.1.0.jar


**api:** http://localhost:8080/api/getRandomBeer

**home page:**  http://localhost:8080/index.html


## How I could make this app better in the future

- Add a MySQL database to replace the in memory HSQL database. 

- Attempted to add image of each beer bottle to the front end, continuing to work on this.

- Add more to the database as it is very small now. 

- Add to the API with more features, eg. getbeerbyname
