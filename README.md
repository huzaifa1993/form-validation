# form-validation
 -This project is a simple form validation system that ensures that the user inputs the correct information in a form.<br>
 -It can help businesses improve the quality of the data they collect through online forms.<br>


Validation Rules<br> 
- The form validation project includes the following validation rules:<br>
  -Required fields: Fields marked as required must be filled out before the form can be submitted.<br>
  -Email validation: The email field must contain a valid email address.<br>
  -Password validation: The password field must meet certain requirements<br>
  -Confirmation validation: The password confirmation field must match the original password field.<br>


Technologies Used:<br>
 HTML, CSS, JavaScript<br>

Features:
 -Responsive Design: The application is optimized for different screen sizes, including desktops, laptops, tablets, and smartphones.

Styling:
 -Nunito font is used in this website and sans-serif font as default font.
 -Flex box is used for the layout.

Functions:
validateForm():
-this function is used to validate a web form.
-If the form is not valid, the function displays an error message to the user.
-The text content is set to "Please fill out all fields." using textContent.
-The color of the text is set to red using the style.color.
-he border color of the message container is also set to red using style.borderColor.
-it uses if statement to compare password1El and password2El
-If they match, the passwordsMatch variable is set to true, and the border color be green.
-If they do not match, the passwordsMatch variable is set to false,and the border color be red.
-does not take any parameter.
-it returns void.


processFormData(e):
-this function is used to process form data. It is called when the user submits the form.
-preventDefault() prevent the default form submission behavior.
-then the function calls the validateForm() function.
-it takes the event as parameter.
-it returns void.


storeformDate():
-this function is used to store form data. 
-the 'user' object contains the form field values from the name, phone, email, website, and password fields.
-does not take any parameter.
-it returns void.




