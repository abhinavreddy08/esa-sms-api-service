# SMS Microservice


This is a simple API service that exposes the following 2 APIs that accepts JSON data as input. Use only POST HTTP method.If the API request is sent using any other HTTP method apart from POST, return HTTP 405.

Tech stack used – Node js , Express and MongoDB.


## Table of contents
* [Instructions to setup locally](#instructions-to-setup-locally)
    * [Installing modules](#installing-modules)
* [Authentication](#Authetntication)
* [APIs and their behavior](#apis-and-their-behavior)
* [Validations](#validations)
* [Connecting service through heroku](#Connecting-service-through-heroku)




## Instructions to setup locally
### Installing modules
- Run the following commands in your terminal to run this project :
```bash
$git clone https://github.com/abhinavreddy08/esa-sms-api-service.git
$ cd esa-sms-api-service
$ npm install
$ node server.js
```

## Authentication
A key named ```app-secret``` must be passed with the value ```Bearer 18528``` in the headers for each request for successful authorization.

## APIs and their behavior
The api behaviour is mentioned in ```ESA Assignment 4.pdf```,All the corner cases are implemented.

## Validations
Basic unit tests are written for all the existing functions using Mocha and Chai which can be viewed in the ```/test/sms.js``` file.

## Connecting service through heroku
You can use the sms-api-service with Postman Using Heroku.The Heroku service link in mentioned in ```Heroku.txt```




