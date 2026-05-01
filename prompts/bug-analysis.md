# AI Prompt: Bug Analysis

## Purpose
Use AI to analyze bugs, improve bug reports, and identify missing test scenarios.

## Prompt

Act as a Senior QA Engineer.

Analyze the following bug and provide:

- Bug Title
- Severity
- Priority
- Business Impact
- Steps to Reproduce
- Expected Result
- Actual Result
- Additional Test Scenarios

---

## Example Bug

During user registration, no email verification, OTP, or confirmation message is received after successful registration.

---

## AI Output Example

### Bug Title
User does not receive verification or confirmation after registration

### Severity
High

### Priority
High

### Business Impact
- User confusion
- Security risk
- Reduced trust

### Steps to Reproduce
1. Go to registration page  
2. Enter valid details  
3. Submit  

### Expected Result
User should receive verification or confirmation  

### Actual Result
No verification or confirmation received  

---

## Additional Test Scenarios

- Verify email delivery
- Verify OTP generation
- Verify retry option
- Verify duplicate registration