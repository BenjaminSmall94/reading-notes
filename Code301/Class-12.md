# CRUD

[Home](../index.md)

## Status codes and REST methods

1. In your own words, describe what each group of status code represents:
   - 100’s = Informational Status codes
   - 200’s = Success codes, the request passed initial validation or sometimes all validation
   - 300’s = Redirection codes, the requested resource is not at the same location
   - 400’s = Client error codes, something the client did made the request fail
   - 500’s = Server error codes, something went wrong with the server and if the client retries the same reqest later, it probably will work

2. What is a status code 202?
   The request has passed initial validation and has been accepted for processing.

3. What is a status code 308?
   Permanent Redirect, the resource has moved locations permanently

4. What code would you use if an update didn’t return data to a client?
   Error Code 204

5. What code would you use if a resource used to exist but no longer does?
   Error Code 410

6. What is the ‘Forbidden’ status code?
   Error Code 403

## Build a REST API with Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
   So that we can reference it from an environmental variable. That way you can also specify it as an environmental variable in your deployed server.

2. What is middleware?
   Code that runs when the server gets a request but before it gets passed to your routes.

3. What does app.use(express.json()) do?
   It lets our server accept JSON as a body instead of a get element or post element. 

4. What does the /:id mean in a route?
   The colon means it is a parameter that can be accessed by accessing the request object

5. What is the difference between PUT and PATCH?
   PUT updates all the data about a resource and PATCH only updates certain parts of the resource

6. How do you make a default value in a schema?
   Mongoose makes it really easy with the mongoose.Schema class. Just simply use that.

7. What does a 500 error status code mean?
   Server Error

8. What is the difference between a status 200 and a status 201?
   Successefully created an object as opposed to just a generic success/ok.

## Things I want to know more about

After watching this video along with his videos on Promises and Async/Await I am feeling pretty good about the content so far!
