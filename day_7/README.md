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
    - `a` — Matches one character that is a (not b, not aa, and so on).
    - `abc` — Matches a, followed by b, followed by c.
    - `ab?c`— Matches a, optionally followed by a single b, followed by c. ( ac or abc)
    - `ab*c` — Matches a, optionally followed by any number of bs, followed by c. ( ac , abc, abbbbbc, and so on).
    - `a|b` — Matches one character that is a or b.
    - `abc|xyz` — Matches exactly abc or exactly xyz (but not abcxyz or a or y, and so on).