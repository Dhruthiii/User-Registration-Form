# User-Registration-Form
![image](https://github.com/Dhruthiii/User-Registration-Form/assets/141212789/ce5fecea-928d-451c-bd2b-74d7a668a001)

The HTML registration form is a user interface component comprising input fields for capturing personal information such as name, email, password, contact details, and gender, typically styled with CSS for presentation and validation.

HTML document with a registration form containing input fields for first name, last name, email, password, etc.

CSS styles are applied to elements for layout, spacing, colors, borders, and alignment to enhance visual appeal.

JavaScript Form Validation ensures data integrity by verifying user input before submission. It validates fields like passwords, emails, and selections, providing alerts for invalid data, and enhancing user experience and data accuracy.

APPROACH:

-> Data Retrieval: It retrieves the values of various form fields like name, email, password, and address using document.forms.RegForm.
Data Validation:
-> Name Validation: Checks if the name field is empty or contains any digits.

-> Email Validation: Verifies if the email field is not empty and contains the ‘@’ symbol.

-> Password Validation: Validates that the password field is not empty and has a minimum length of 6 characters.
Course Selection Validation: Ensures that a course is selected from the dropdown.

-> Error Handling:
If any of the validation criteria fail, it displays an alert message using window.alert.
Sets focus back to the respective field that failed validation, ensuring the user’s attention is drawn to the problematic field.

-> Submission Control:
Returns true if all validation checks pass, indicating that the form can be submitted. Otherwise, it returns false, preventing form submission.
-> Focus Adjustment:
Sets focus to the first field that failed validation, ensuring the user’s attention is drawn to the problematic field.

Example: Here is an example of above explained approach.

![image](https://github.com/Dhruthiii/User-Registration-Form/assets/141212789/6d06a255-7a09-48a0-a3d7-808e3036c42a)
 In case the email is entered wrong It will show as above image email should contain @ symbol


 ![image](https://github.com/Dhruthiii/User-Registration-Form/assets/141212789/39e5820e-056f-4b33-bd0f-1e07885243eb)
 If in case password is wrong then it shows password does not match


OUTPUT:

 ![image](https://github.com/Dhruthiii/User-Registration-Form/assets/141212789/599cdfbf-e70c-4a33-90a7-3c0096e7bcec)
 
  After everything entered is correct then it proceeds to registration successfull




