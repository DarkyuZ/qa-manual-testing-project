# Login Test Cases



## TEST CASE ID: TC-001

Title:
Valid Login with Correct Credentials

Module:
Authentication - Login

Priority:
High

Severity:
Critical

Preconditions:
- User is registered in the system
- User is on Login page
- Internet connection is stable

Test Steps:
1. Open Login page.
2. Enter valid username/email.
3. Enter valid password.
4. Click Login button.

Test Data:
Username: testuser@example.com  
Password: ValidPassword123

Expected Result:
- User should be authenticated successfully.
- User should be redirected to Dashboard/Home page.
- Success message or user profile should be visible.

Actual Result:
- User is redirected to Dashboard page successfully.
- Welcome message is displayed.

Status:
PASS


