# WEB-RESETPW-001 – Password reset email sent

## Description
Verify system behavior when submitting a valid email for password recovery


## Module
Password Recovery


## Preconditions
Email is registered in the system


## Test Data
Email: valid@example.com  


## Steps

1. Navigate to "Forgot your password?"
2. Enter a registered email
3. Click "Submit"


## Expected Result
System accepts the request and sends password reset email


## Actual Result
System redirects to login and reset email is received


## Status
Passed