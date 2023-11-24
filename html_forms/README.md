# Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

What HTML forms are
Examples of HTML form elements and their attributes (eg: input, radio buttons, checkboxes, dropdowns, etc)
How to implement basic form validation using HTML5 attributes, such as required, minlength, maxlength, pattern, and more.

## Tasks

### 0. Simple Contact Form

Create an HTML form for a basic contact form with the following requirements:

Include fields for the user’s name, email address, and message.
Apply appropriate HTML5 validation attributes to ensure the name and email fields are required and that the email field accepts a valid email format.
Use a <textarea> element for the message field to allow for a long description and not limit it to just one line.
Add a submit button to submit the form.

### 1. Registration Form

Design an HTML registration form with the following specifications:

Include fields for the user’s name, email, password, and confirm password.
Implement HTML5 validation attributes to ensure all fields are required,
And the email field accepts a valid email format, and the password fields match.
Use appropriate input types (e.g., email, password) and labels for each field.

### 2. Subscription Form with Radio Buttons

Build an HTML form for a subscription with the following criteria:

Include fields for the user’s name, email, and subscription preference (monthly, yearly).
Utilize radio buttons for the subscription preference and ensure that the user can only select one option.
Apply HTML5 validation to ensure all fields are required and the email field accepts a valid email format.

### 3. Feedback Form with Checkboxes and File Upload

Develop an HTML feedback form with checkboxes to capture user opinions and the ability to upload a file:

Include fields for the user’s name, email, checkboxes for various feedback options (e.g., excellent, good, average, poor), and a file upload field.
Ensure that the user can select multiple checkboxes.
Specify the file upload field using the <input type="file"> element.
Implement HTML5 validation to ensure the name, email, at least one checkbox, and a file are filled out.

### 4. Survey Form with Select Dropdown, Time, and Date Selection

Design an HTML survey form with a select dropdown to collect user preferences, along with time and date selection:

Include fields for the user’s name, email, a select dropdown for their favorite color (options: red, blue, green), and separate fields for time and date selection.
Apply HTML5 validation to ensure all fields are required, including the select dropdown, time, and date fields.

To implement the time and date selection, use the following input types:

For time: <input type="time">

For date: <input type="date">

# Evaluation Quiz

0. What is the HTML attribute used to set the minimum length of an input field?

minlength

1. What are some common validation techniques used in form submissions?

Checking for empty fields, validating email addresses, and enforcing password requirements

2. How can you make an input field required in HTML5?

By adding the required attribute to the <input> element

3. What is the purpose of form submissions in web development?

To collect user input data for further processing

4. What are some common validation techniques for checking email addresses in form submissions?

Checking for the presence of an "@" symbol and a valid domain name
Checking the length of the email address string
Verifying the format of the email address using regular expressions
All of the above

5. How can you provide a default selected option in a dropdown menu in HTML?

By using the selected attribute on the desired <option> element

6. How can you group related radio buttons together in HTML?

By using the <input type="radio"> element with the same name attribute

7. Which HTML input type is used for single-line text input?

text

8. How can you specify a pattern that the input value must match in HTML5?

By using the pattern attribute with a regular expression

9. Which HTML input type is used for selecting multiple options from a list?

checkbox

10. What is an HTML form used for?

To gather user input and send it to a server

11. What is the purpose of form field validation?

To ensure that the entered data meets specific criteria or constraints
To display error messages to the user in case of invalid input
To prevent the submission of incomplete or incorrect data

12. Which HTML element is used to create a form?

<form>

13. How can you perform basic form validation using HTML5 attributes?

By using the required and other validation attributes on input elements
