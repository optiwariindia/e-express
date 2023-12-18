# e-express

This extension is a collection of snippets for express js application development. It can be used to create api routes, return promise and require packages very easily. User can use this snippet to create expressjs api faster.

## Features

This extension contains following snippets: 
    
- Require Packages
- Return Primise
- Express Router
- Generate API Routes
    
## Prerequisites

It is expected that you have setup server configuration and have imported the route from express.js application. This snippet collection will work only with common js files and it will not be applicable to module js files.

## Usage:
### Require Package
__e-require-package__

    const | require(|)
### Return Promise
__e-ret-promise__

    return new Promise((resolve,reject)=>{|})
### Create Express Route
__e-exp-router__

    const router=require("express").Router();
    |
    module.exports=router;
### Generate API Routes
__e-api__

    router
        .route("|")
        .get(...)
        .post(...)
        .put(...)
        .patch(...)
        .delete(...)
        .copy(...);
    router
        .route("|/:id")
        .get(...)
        .post(...)
        .put(...)
        .patch(...)
        .delete(...)
        .copy(...);
## Requests, Suggestions and Feedback 

Feel free to reach us at info@etutorials.co.in for any feedback or suggestion. We also welcome if you suggest more such snippets and let us know your common requirements that can be converted to snippets.
