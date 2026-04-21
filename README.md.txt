# Web Testing Portfolio – Alex Rodriguez

This project contains manual testing performed on a Shopify-based e-commerce demo site:

https://sauce-demo.myshopify.com/

The focus was on validating user flows such as registration, login, and password recovery.


## Testing Scope

- Form validation
- User input handling
- Error messaging
- UX behavior
- Security considerations


## Tools Used

- Browser (manual testing)
- DevTools (basic inspection)


## Key Findings

|   ID             |   Issue                               | Severity |  Type           |
--------------------------------------------------------------------------
| WEB-REGISTRO-004 | Weak name validation                  |  MEDIUM  | Data validation |
| WEB-LOGIN-002    | Ambiguous error message + input reset |   LOW    |        UX       |
| WEB-RESETPW-002  | Account enumeration risk              |  MEDIUM  |     Security    |


## Learnings

- Input validation must be consistent across all fields
- Error messages should be user-friendly but not reveal sensitive data
- Security considerations are critical even in simple flows


## Structure

- '/test-cases'
- '/bug-reports'
- '/evidence'