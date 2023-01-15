# Documentation
# First MicroTask
It is an API that does error handling by showing a error message.

#### Repo Link
    https://github.com/Olindam20/MicroTask-1

#### Deta Link
    https://m5xgtl.deta.dev/api/error

#### Clone the git repository
    git clone https://github.com/Olindam20/MicroTask-1

#### Navigation
    cd MicroTask-1 

#### Installation
    npm i

#### Runserver
    npm start


#### Endpoints
    /api/error


# Second MicroTask
### It is a microservice which accumulates three different microservice APIs : ErrorHandler,Authentication and Visitor counter

# Repo Link
    https://github.com/Olindam20/MicroTask-2
    
#### Clone the git repository
    git clone https://github.com/olindam20/MicroTask-2

#### Navigation
    cd MicroTask-2
    cd AuthAPI or cd ErrorHandler or cd ViewCounter

#### Installation
    npm i

#### Runserver
    npm start

## API Reference

### ErrorHandler

#### Get a random error message which is handled by a dummy ErrorHandler middleware
    
    GET http://localhost:3000/api/error

### Authentication

#### Sign-up(Returns token )

    POST http://localhost:3000/api/sign-up


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|



#### Log In(Returns token)
    GET http://localhost:3000/api/sign-in


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|

### View Counter
    POST http://localhost:3000/api/get-views

# Third MicroTask
It is an MicroService in which user's current address is automatically shown at first and when the form is filled with any address, corresponding latitude and longitude is shown.

#### Repo Link
    https://github.com/Olindam20/MicroTask-3

#### Deta Link
    https://vx9xkl.deta.dev/get-address


### API Refernce

#### Clone the git repository
    git clone https://github.com/Olindam20/MicroTask-3

#### Navigation
    cd MicroTask-3  

#### Installation
    npm i
    npm start


#### Endpoints
    /get-address
 
## Author
-[@olindam20](https://github.com/Olindam20)
