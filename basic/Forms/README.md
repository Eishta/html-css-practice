# HTML Forms

---
**Form**
```HTML
<form> .... </form>

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form> 
 ```
**Attributes of form element**

1. action - defines the action to be performed when the form is submitted.
2. target - specifies where to display the response that is received after submitting the form.- _blank, -self, _parent
3. method- specifies the HTTP method to be used when submitting the form data.- _get , _post
4. autocomplete - specifies whether a form should have autocomplete on or off. - _on, _off
5. novalidate - boolean - the form-data (input) should not be validated when submitted.
6. enctype - encryption type of the data when submitted as _post.

**Form elements**
[Link](https://www.w3schools.com/html/html_form_elements.asp)
* input
* label
* select
* textarea
* button
* fieldset
* legend
* datalist
* output
* option
* optgroup

---

1. The ```<label>``` Element
* defines a label for many form elements.
* The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.
---  
2. The ```<input>``` Element

* name attribute is important , then only it can be submitted.
* type of input field can be 
    * button - _shows a normal button_
    * checkbox - _shows checkbox_
    * color - _color picker_
    * date - _allows selecting a date_
    * datetime-local - _allows selecting the date and time_
    * email - _adds valiadtions of email to input field_
    * file - _allows importing of files_
    * hidden - _not visible on UI but can be seen in developer tools(not for secure data)_
    * image - 
    * month - _allows selecting a month_
    * number - _allows selecting a number, min, max, step_ 
    * password - _does not show the input value on screen_
    * radio - _radio buttons_
    * range - _shows a progress bar within the range_
    * reset - _button that reset the value of the form fields _
    * search - _works same as input field_
    * submit - _button that triggers submit of from_
    * tel - _input field that takes the numbers and can format with given pattern_ 
    * text - _normal input field_
    * time - _allows selecting time_
    * url - _allows typing the url and also applies the validation_
    * week - _allows selecting week_
* Attributes of input
    * value
    * size
    * maxLength
    * required
    * readOnly
    * autocomplete
    * disabled
    * min and max
    * multiple
    * pattern
    * placeholder
    * step
    * autofocus
    * width and height
    * list
   
  

  
  
