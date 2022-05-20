# Day 10 Of 100Days

Date: _Friday, 20 May 2022_

### Promise
- Promise is an object that takes an asynchronous action and produce a value in the future
- Promise solves the issues of _callback hell_, therefore no need in passing down two functions into successive action.
- Promises give our code the ability to finish a task and it then let the code decide on the next action.
- A new promise has the following internal properties:
  - `state`: initially the _state_ is set to `pending`, then to `fulfilled` if the promised action was a success or `rejected` if the action was a failure.
  - `result`: initially, the _result_ is `undefined` then changed to the promised `action value` or an _error message_
- Constructor syntax for a promise is thus
    ``` js
        let promise = new Promise(function(resolve, reject) {
            // Async action
        })
    ```
    `promise` is a Promise object. The function passed into the Promise contructor is called the **executor function** and it runs automatic
    NB: All constructors in `Js` starts with a cap.


#### Challenge
- No electricity, i am limited to thoeries.