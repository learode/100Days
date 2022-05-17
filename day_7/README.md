# Form Validation
* Verification if the inputed data in the form control is the in the required format or within the constraints of the application
* Two types of form validation: `client-side` and `server-side validation`

## Client-side Form Validation
* The validation done at the browser level.
* Using `built-in HTML5 form validation` and/or `Javascript form validation`

### Why client-side form validation
 - Protect users' data
 - Protect the application
 - Reduce work load on the server side
 - Good for user experience

#### Using `Built-in HTML5` form validation
 - HTML5 Form control provide attributtes that helps in user form validation
 - ##### required
    - To show if a form control is optional
    - Takes no value
    - Its important to indicate to the user the form control required
    
    - if set, the UI pseudo-code
        - `:invalid` is matched if the form is empty
        - `:required` is matched whether there is inputed data or not.
        - `:valid` is matched if data is inputed.

 - ##### pattern