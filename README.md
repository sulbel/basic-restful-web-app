# basic-restful-web-app
A simple RESTful web app with stack: Node.js, Express, MongoDB

## Goals 
The goals of this project are:
* Become acquainted with REST
* Store and retrieve JSON data in MongoDB using HTTP POST and HTTP GET
* Remove data from the collection using HTTP DELETE
* Use AJAX for data operations

### Some notes on REST
* HTTP Methods:
  * `GET` To retrieve data
  * `POST` To create data
  * `PUT` To update/change data
  * `DELETE` To delete data
* Stateless
  * "Don't store state information on the server"
    * Save it on the client side e.g. with cookies
* Exposes directory structure-like URIs
* Transfer JSON and/or XML
  * Easily manipulate this data in the presentation layer without hitting the server, unless new data is needed..

