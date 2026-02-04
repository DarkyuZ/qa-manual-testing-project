# Negative Login Test Cases

# TEST CASE ID: TC-NEG-001

# Title:
Login attempt with invalid credentials

# Preconditions:

- User is on the login page  
- Application is running normally  
- Internet connection is active  

# Test Steps:

1. Navigate to the login page  
2. Enter an invalid username  
3. Enter a valid password  
4. Click the Login button  

# Expected Result:

- System should display a specific error message indicating incorrect credentials  
- User should remain on the login page  
- No access to protected areas should be granted  

# Actual Result:

- System displays a generic error message  
- No indication of which field is incorrect  

# Status:

FAIL  

# Priority:

Medium  

# Severity:

Low  

# Notes:

Improving error message clarity would enhance user experience and reduce login confusion.
