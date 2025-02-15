OrangeHRM Live Project - Login Page Testing
-
This guide covers the manual testing of the Login Page for the OrangeHRM demo. Ensure the login process works as expected, including handling both valid and invalid login scenarios.

Key Areas to Test
-
1.	Successful Login:
o	Test with valid credentials (e.g., admin/admin123).
o	Verify successful redirection to the dashboard.

2.	Invalid Login:
o	Test with invalid credentials (wrong username/password).
o	Ensure error message displays (e.g., "Invalid login credentials").

3.	Blank Fields:
o	Test login with blank username or password fields.
o	Check for appropriate error message (e.g., "Please enter your username and password").

4.	Password Masking:
o	Ensure the password field masks characters.

5.	Forgot Password:
o	Verify that the Forgot Password link works and redirects to the recovery page.

6.	UI/UX:
o	Ensure proper alignment of form elements and labels.
o	Test that the Login button is only active when both fields are filled.

Test Cases Summary
-
•	TC1: Login with valid credentials.
•	TC2: Login with invalid credentials.
•	TC3: Leave fields blank and verify prompt.
•	TC4: Check password masking.
•	TC5: Verify Forgot Password functionality.
•	TC6: Check UI/UX layout.

Reporting Bugs
-
If you find issues, create a detailed bug report with steps to reproduce, expected vs. actual behavior, and any screenshots/logs.

Credentials
-
•	Username: admin

•	Password: admin123


