
# Bug Report #2

## Title  
Password field allows submission with empty input


## Bug ID  
BUG-002


## Environment  

- Platform: Web Application  
- Browser: Google Chrome (Latest Version)  
- Operating System: Windows 11  
- Test Environment: Staging  


## Priority  
High

## Severity  
Major   


## Description  

The system allows the user to submit the login form even when the password field is left empty. This behavior may lead to improper validation and potential security issues.


## Preconditions  

- User is on the login page  
- Internet connection is active  


## Steps to Reproduce  

1. Open the login page  
2. Enter a valid email address  
3. Leave the password field empty  
4. Click on the "Login" button  


## Expected Result  

The system should prevent form submission and display a validation error message indicating that the password field is required.


## Actual Result  

The system allows the login attempt to proceed without showing any validation error.


## Test Evidence  

No error message is displayed when submitting the form with an empty password field.


## Status  

Open



