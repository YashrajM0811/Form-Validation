# Form Validation using JavaScript

This project demonstrates the implementation of form validation using JavaScript. The form includes fields for username, email, password, and password confirmation. This README file provides an overview of the project, its structure, and the core JavaScript concepts utilized.

## Introduction

Form validation is a crucial aspect of web development, ensuring that users submit correct and complete information. This project demonstrates how to validate form inputs using JavaScript, providing real-time feedback to users about the validity of their entries.

## Getting Started

To get started with this project, clone the repository or download the files. Open the `index.html` file in your browser to see the form validation in action.

## Files Included

- `index.html`: Contains the structure of the form.
- `style.css`: Contains the styles for the form.
- `script.js`: Contains the JavaScript code for form validation.

## HTML Structure

The `index.html` file defines the structure of the form.

## CSS Styling

The `style.css` file is used to style the form. Customize the appearance of the form by modifying this file.

## JavaScript Functionality

The `script.js` file contains the JavaScript code that validates the form inputs. 

### Explanation of the JavaScript Code

1. Selecting Elements: Variables are used to reference different elements in the DOM, such as the form, username, email, password, and confirm password fields.
2. Form Submission: An event listener is added to the form to prevent the default form submission and call the `validateInputs` function instead.
3. Validating Inputs: The `validateInputs` function checks the values of each input field. If a field is empty or invalid, it calls the `setError` function. If a field is valid, it calls the `setSuccess` function.
4. Setting Error Messages: The `setError` function displays an error message and adds an error class to the input field's parent element.
5. Setting Success Messages: The `setSuccess` function removes the error message and adds a success class to the input field's parent element.
6. Email Validation: The `isValidEmail` function uses a regular expression to check if the email address is valid.

## How to Use

1. Open the `index.html` file in your web browser.
2. Fill in the form fields with appropriate values.
3. Click the "Submit" button to validate the form inputs.
4. Observe the real-time validation feedback for each field.

## Conclusion

Form validation is an essential aspect of web development. This project demonstrates how to validate form inputs using JavaScript, providing real-time feedback to users and ensuring data accuracy. By understanding and modifying this project, you can enhance your JavaScript skills and create robust form validation for your web applications.