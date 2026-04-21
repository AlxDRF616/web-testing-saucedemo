# WEB-REGISTRO-004 – Weak validation on First Name / Last Name

## Description
Verify system behavior when entering minimal length input in name fields.


## Module
User Registration


## Preconditions
User is on the "Sign Up" page


## Test Data
First Name: A  
Last Name: B  
Email: test@example.com  
Password: Test1234  


## Steps

1. Navigate to "Sign Up"
2. Fill all required fields
3. Enter only 1 character in First Name and Last Name
4. Click "Create"


## Expected Result
The system should enforce a minimum length validation (e.g., at least 2–3 characters)


## Actual Result
The system accepts the input and allows account creation


## Status
Failed


## Notes
This may lead to poor data quality and affect downstream processes