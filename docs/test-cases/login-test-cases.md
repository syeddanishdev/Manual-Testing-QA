Login Test Cases
TC001_Login_ValidCredentials

Title: Verify successful login with valid credentials
Preconditions: Registered user account
Steps:
Navigate to login page.
Enter valid email and password.
Click "Login."


Expected Result: User redirected to homepage.
Priority: High
Type: Functional
Risk Level: High
Requirement: US-101

TC002_Login_InvalidCredentials

Title: Verify error on login with invalid credentials
Preconditions: Login page accessible
Steps:
Navigate to login page.
Enter invalid email or password.
Click "Login."


Expected Result: Error: "Invalid email or password."
Priority: High
Type: Negative
Risk Level: High
Requirement: US-101

TC003_Login_XSSAttack

Title: Verify login resists XSS attack
Preconditions: Login page accessible
Steps:
Navigate to login page.
Enter email: "alert('hack')".
Enter password: "password123".
Click "Login."


Expected Result: Input sanitized, no script execution.
Priority: Critical
Type: Security
Risk Level: Critical
Requirement: US-103
