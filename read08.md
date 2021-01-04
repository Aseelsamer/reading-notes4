
## True or false: The route handler is middleware?
False.

## In what ways can a middleware function end the process and send data to the browser?
once the request comes the auth middleware will do some authentication logic that we have written inside it.Once authentication successful then remaining routed must be called using next()


## At what point in the request lifecycle can you “inject” middleware?
One of the most crucial reasons that we use middleware is that it allows both systems to operate independently.


## What can cause express to error with “Request headers sent twice, cannot start a second response”
The error "Error: Can't set headers after they are sent." means that you're already in the Body or Finished state, but some function tried to set a header or statusCode. When you see this error, try to look for anything that tries to send a header after some of the body has already been written.


-------------------------------------------

## Term:

Middleware:a web server is a function that inputs a request and outputs a response. middlewares are functions executed in the middle after the incoming request, which then produces an output.

Request Object:A new body object containing the parsed data is populated .

Response Object:which is Express app sends when it gets an HTTP request.

Application Middleware:is software that provides common services and capabilities to applications outside of what's offered by the operating system.

Routing Middleware:refers to how an application’s endpoints (URIs) respond to client requests.
 You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function