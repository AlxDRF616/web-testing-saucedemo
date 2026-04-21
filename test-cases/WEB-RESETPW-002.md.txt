# WEB-RESETPW-002 – Password reset reveals account existence

## Description
Verify system response when attempting password reset with invalid or empty email


## Module
Password Recovery


## Preconditions
User is on "Forgot Password" page


## Test Data
Email: (empty) or unregistered email


## Steps

1. Navigate to "Forgot your password?"
2. Leave email empty or enter unregistered email
3. Click "Submit"


## Expected Result
The system should return a generic message:
"If the email is registered, you will receive a reset link"


## Actual Result
The system displays:
"No account found with that email"


## Status
Failed


## Notes
This behavior exposes whether an email is registered (user enumeration risk)