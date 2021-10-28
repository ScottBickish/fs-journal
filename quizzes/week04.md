# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
async runs off the path if you will, takes a detour and connects back on the original path. synchronous code runs in a strait line top to bottom.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
written like this (ProxyState.on('cars')_drawCars) the PS listener will look for any changes with the first argument and then follow a function. its a great way to check for multiple things without calling functions to update all over the place.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
open closed principle.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
a callback is a function that is passed to another function as a parameter and is executed inside it.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
a promise represents the eventual completion or failure of an async operation and its resulting value. it all starts with an async function with a try catch try is the promise and catch is the error if there is one. that happens in the controller and is sent off to the service with another async function thats where the await happens.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
post, put, delete
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
application. program. interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
the service primarily. or before that the axios service will set the baseurl and your service will import that and call to the api.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
to keep your code from being manipulated by users. its passing off copies of the file that doesnt affect the original copy.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
it will typically show as a 200.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
server error responses.
```