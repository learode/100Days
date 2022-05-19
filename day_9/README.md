# Day 9 Of 100Days

Date: _Wednesday, 19th May 2022_

### Asynchronous code
Js being a language for the web, there are task that takes long to complete e.g. fetching data from an API.Therefore having to wait for a fetch is no good UX, thus the implementation of _Asynchronous Coding_.
_Asynchronous code or function_ is a block of code or function that runs in the background while the rest of the main code is being executed.
This is done is `Js`, is the intepreter create a separate thread for runing the _asyn code_

- #### Callbacks
In the early days of asynchronous coding, actions of this code were handled by *callback*
A callback is simply a function passed as a parament into another funtion and executed later in the function.
These callbacks, in _asyn coding_ were executed in a later time.
 - The callback was ran/so when the asynchronous code is returned or resolved.
 - These callbacks were used like an alert system to signal that an async action is completed.
 - Callback stepdown when an _asyn action_ calls another async action, which in turn calls yet another async action, yet another and so on. this multiple call lead to what is called **callback hell** or **Pyramid of doom**
 - Another downside of callback for asynchronous coding is that, the async action might be a success or a failure; meaning multiple callback (two different callbacks) which makes handling these complicated.
 - Callback makes identifying asynchronous function and normal functions confusing because this would depend on the function's context.
 With all this seemly discouraging facts about callbacks, there are pretty much is use today. For example, in the traditional `setTimeout()`, `.addEventListeners`

- #### Promise


### Resources used
- [JavaScript.info](https://javascript.info/async)
- The Odin Project [Asynchronous code](https://www.theodinproject.com/lessons/node-path-javascript-asynchronous-code)

### Challenge
I had to use multiple resources most which are not list to actually understand what this asynchronous coding is.