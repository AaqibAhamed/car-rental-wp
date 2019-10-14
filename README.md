# Car-Rental-API : White Panda
A Car Rental Agency API using Nodejs, express, Firebase and Heroku.

## Description - 
This API uses Nodejs and Expressjs for backend functionalities. Firebase Realtime Database has been used to store all data in NoSQL format. Heroku platform is used to host the API based system. 

### Heroku Base URL -
  - This project is hosted on Heroku and it's base url is - https://car-rental-wp.herokuapp.com/ . **POSTMAN** has been used to test all the endpoints of API. The collection can be viewed at  [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/01df9583b863a5c395a4)
  
### Firebase Database URL -
  - Firebase Real Time Database can be accessed by collaborators at url - https://car-rental-wp.firebaseio.com

### Model / Classes -

  - User 
    - Name
    - PhoneNo (unique ID)
    
  - Car
    - Vehicle Number (unique ID)
    - Model
    - Seating Capacity
    - Rent Per Day
    
### Endpoints -
  - Add Car (POST Request with body params)
  - Book Car based on availability (PUT Request with body params)
  - Search Cars using filters (GET Request with query params)
  - See Car Bookings (GET Request with query params)
  - Delete a Car (DELETE Request with query and in-path params)
  - User Registration and Authorization (POST Request with body params)

### Nodejs modules used - 
  - express
  - moment
  - method-override
  - body-parser
  - firebase-admin
  
### Concepts used - 
  - middlewares
  - validation handling
  - defining routers 
  - handling json and form data
  - handling params and headers
  
### How to run the application ?
  Open the POSTMAN collection and execute the sample requests for each of the 6 endpoints discussed above. [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/01df9583b863a5c395a4)
