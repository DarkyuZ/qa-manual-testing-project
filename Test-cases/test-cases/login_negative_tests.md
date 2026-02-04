## TEST CASE ID: TC-002

Title:
Login Attempt with Invalid Password

Module:
Authentication - Login

Priority:
High

Severity:
Major

Preconditions:
- User exists in the system
- User is on Login page

Test Steps:
1. Open Login page.
2. Enter valid username/email.
3. Enter invalid password.
4. Click Login button.

Test Data:
Username: testuser@example.com  
Password: WrongPassword999

Expected Result:
- User should NOT be logged in.
- Error message should be displayed.
- System should not redirect user.

Actual Result:
- Login page reloads without displaying error message.
- User receives no feedback about incorrect credentials.

Status:
FAIL

Related Bug:
BUG-002-invalid-login.md

