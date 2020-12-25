### Array.map() --> The map() method creates a new array with the results of calling a function for every array element.

The map() method calls the provided function once for each element in an array, in order.

map() does not execute the function for array elements without values.

----------------------

### Array.reduce() -- > from the name of it REDUCE it reduces the array into single number,the result will depend on what the function you wrote (for example: summation , subtract )and it works from left to right .

The reducer function takes four arguments:

1-Accumulator
2-Current Value
3-Current Index
4-Source Array

Your reducer function's returned value is assigned to the accumulator, whose value is remembered across each iteration throughout the array, and ultimately becomes the final, single resulting value.

-----------------------------

### SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js! , with superagent
you can uset .get .put .delete .post .set and ofcourse .then which is the important thing 
as when you use superagent in the function the .then will work after the superaget and will the 
condition or will get the data you want .


### Why await/async?
Everyone who’s done any amount of JS async programming has been up against callback hell. Do a google image search for “pyramid of doom” and you’ll see a lot of really contrived examples, nested 20 deep.

The normal way of dealing with these nested callbacks is to hoist the callbacks out into separate functions. This makes the individual callbacks easier to deal with, but completely destroys apparent control flow, and debugging is a serious chore.

Promises are a bit better, in that you chain things together linearly (as opposed to nesting) to express that one action follows another.

request.doSomething()
    .then(() => doSomethingElse())
    .then(() => doSomethingForTheThirdTime())
Both approaches get really bogged down if there’s any branching control flow. And error handlingreallysucks in both approaches.

Async functions fix all that:

You write your code in an imperative style, and decorate calls to async functions (that you want the result from) with await. You decorate the surrounding function with async.
No callbacks.
You can use try/catch in your async code. You can use loops without recursion.
Stack traces actually work.

----------------------

### Promise 
A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

A Promise is in one of these states:

pending: initial state, neither fulfilled nor rejected.
fulfilled: meaning that the operation was completed successfully.
rejected: meaning that the operation failed.
A pending promise can either be fulfilled with a value or rejected with a reason (error).When either of these options happens, the associated handlers queued up by a promise's then method are called.

-----------------------

### Are all callback functions considered to be Asynchronous? Why or Why Not?

No callback functions are not always considered to be Asynchronous
Async callbacks are functions that are specified as arguments when calling a function which will start executing code in the background. When the background code finishes running, it calls the callback function to let you know the work is done, or to let you know that something of interest has happened. Using callbacks is slightly old-fashioned now, but you'll still see them in use in a number of older-but-still-commonly-used APIs.

