# Real-World QA Scenario (Anonymized)

## Feature: User Registration

## Scenario

During testing of a user registration flow, it was observed that after successful registration:

- No email verification was sent  
- No OTP was triggered  
- No confirmation message was displayed  

---

## QA Concern

This creates:

- Security risk (unverified accounts)  
- User confusion  
- Lack of trust  
- Unclear account creation status  

---

## Bug Title

User does not receive verification or confirmation after registration

---

## Severity

High

---

## Expected Result

After successful registration, user should receive:

- Email verification OR  
- OTP verification OR  
- Confirmation message  

---

## Actual Result

No verification or confirmation is received.

---

## Business Impact

- Risk of unauthorized account creation  
- Increased user support issues  
- Reduced user trust  

---

## Additional Test Scenarios

- Verify registration with valid email  
- Verify duplicate email handling  
- Verify invalid email validation  
- Verify weak password validation  
- Verify OTP delivery  
- Verify retry mechanism  
- Verify fallback message when email fails  