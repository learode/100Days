
# Day 8 of 100Days

Date : Wednesday, 18th May 2022


### Form validation cont.
Today I continued with form validation, built-in HTML5 form control attributtes
- `pattern`:
    * Accept a `Regular Expression` to check the inputed data follows the required pattern.
    * `:invalid` UI pseudo-code is matched as the form control is empty or the pattern is not matched.
    * Some form control need not have a `pattern` attribute as its type handles this. E.g. input of `type='email'`
    * Not supported in the `<textarea>` tag.

- `length`:
    - The number of character a form control can contain is can be control by setting the `minlength` and/or `maxlength` attributes.
    - Attributes work for form control of string type of input.
    - There behave just as the name indicates.
    - `:invalid` UI is matched if the number of character falls without or within the values for `maxlength` or `minlength`.
    - For good UX practiced, the character count for this type of form control is specified.

- `Value`:
    - Works for numerical type of inputs
    - Attributes are `min` and `max`.

        ``` html
        <input name="age" required min="16" max="65">
        ```
        <form>
        <label for="age">Name:<label> <input type="number" name="age" required min="16" max="65">
        <button type="submit"> Submit</button></form>
    - The inpured value can't be below 16 nor above 65, then the form is `:invalid`



#### Resources
- [MDN Client-side](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation#validating_forms_using_javascript) form validation
- W3school [Form validation]()
- HMTL [Fieldset](https://w3schools.com/tags/tag_fieldset.html)
#### Challenge
1. Understanding the code form __mdn__ pushed me to read about `fieldset`
2. I had to copy/paste the code from **mdn** to better understanding some for the structure of the form controls.
3. **til**: 
    ``` html
        <datalist id=matchAnInput> 
            <option>suggestions</option> 
            <option>suggestions</option> 
        </datalist>
    ```
    This struction is used to suggest input for a give input field with the same id matched.

