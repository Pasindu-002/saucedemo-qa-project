 SauceDemo - Login Requirements

 Feature

Login

 R-LOGIN-001 - Valid Login

The system should allow a valid user to log in using valid credentials.

 R-LOGIN-002 - Invalid Username

The system should prevent login when an invalid username is entered.

 R-LOGIN-003 - Invalid Password

The system should prevent login when an incorrect password is entered.

 R-LOGIN-004 - Empty Username

The system should not allow login when the username field is empty.

 R-LOGIN-005 - Empty Password

The system should not allow login when the password field is empty.

 R-LOGIN-006 - Empty Credentials

The system should not allow login when both username and password fields are empty.

## R-LOGIN-007 - Password Masking

The password entered by the user should be hidden/masked.

 R-LOGIN-008 - Authentication Protection

A user who has not successfully logged in should not be able to access protected application functionality.

 R-LOGIN-009 - Error Handling

When login fails, the system should display appropriate feedback to the user.

 R-LOGIN-010 - Login Usability

The username field, password field, and Login button should be clearly visible and usable.

 R-LOGIN-011 - Input Robustness

The login functionality should handle unexpected or malformed input without crashing.

 R-LOGIN-012 - Compatibility

The login functionality should behave consistently in supported environments.

---

 Test Credentials

 Valid Credentials

Username: `standard_user`

Password: `secret_sauce`

 Invalid Credentials

Username: `invalid_user`

Password: `wrong_password`
