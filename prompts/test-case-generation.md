# AI Prompt: Test Case Generation

## Purpose
Use AI to generate test cases from user stories and acceptance criteria.

## Prompt

Act as a Senior QA Engineer.

Analyze the following user story and acceptance criteria.

Generate:
- Test Case Title
- Preconditions
- Test Steps
- Expected Result
- Priority
- Type (Positive / Negative / Edge)

## Example

User Story:
User should be able to register with email and password.

Acceptance Criteria:
- Valid email should work
- Invalid email should show error
- Weak password should show validation

## Output Example

1. Verify registration with valid email → Positive  
2. Verify error for invalid email → Negative  
3. Verify weak password validation → Negative  
4. Verify empty fields → Edge case  