

## 1. Document Information

| Field | Details |
|---|---|
| Project Name | AI Chatbot Manual Testing |
| Document Name | Chatbot Test Plan |
| Version | 1.0 |
| Test Type | Manual Testing |
| Repository | `ai-chatbot-manual-testing` |
| Status | Draft |
| Prepared By | Add your name |
| Prepared Date | Add date |

---

## 2. Introduction

This test plan defines the manual testing approach for a basic AI customer support chatbot.

The chatbot is expected to help users with common support requests such as greetings, business opening hours, password reset guidance, customer support contact details, and unsupported questions.

The purpose of testing is to verify that the chatbot provides accurate, relevant, secure, consistent, and user-friendly responses.

---

## 3. Test Objectives

The objectives of this testing project are to verify that the chatbot:

- Understands supported user intents
- Provides correct and relevant responses
- Handles different ways of asking the same question
- Handles spelling mistakes and letter-case variations
- Maintains context during short conversations
- Handles unsupported and unclear questions safely
- Does not reveal private or confidential information
- Does not ask users to provide passwords
- Handles invalid and unusual inputs without crashing
- Responds within the expected response time
- Works correctly in supported browsers

---

## 4. Test References

The following project documents are used as testing references:

- `requirements/chatbot-requirements.md`
- `test-scenarios/chatbot-test-scenarios.xlsx`
- `test-cases/chatbot-manual-test-cases.xlsx`

---

## 5. Scope

### 5.1 In Scope

The following areas are included in this testing cycle:

- Greeting functionality
- Business opening hours
- Password reset guidance
- Customer support contact information
- Intent recognition
- Alternative question wording
- Conversation context
- Unsupported question handling
- Empty input handling
- Special-character input
- Numeric-only input
- Emoji input
- Spelling mistakes
- Uppercase and mixed-case input
- Long-message handling
- Repeated-message handling
- Response consistency
- Privacy protection
- Password security
- Basic usability
- Basic response-time testing
- Chrome and Microsoft Edge compatibility
- Defect reporting
- Retesting
- Regression testing

### 5.2 Out of Scope

The following areas are excluded from the first testing cycle:

- Automated testing
- Voice chatbot testing
- Multilingual testing
- Mobile application testing
- Payment processing
- Real customer account changes
- Live agent integration
- Large-scale load testing
- Stress testing
- Third-party system integrations
- Production environment testing
- Model training and retraining validation

---

## 6. Features to Be Tested

| Feature ID | Feature | Related Requirement |
|---|---|---|
| F-001 | Greeting responses | REQ-001 |
| F-002 | Business opening hours | REQ-002 |
| F-003 | Password reset guidance | REQ-003, REQ-014 |
| F-004 | Support contact information | REQ-004 |
| F-005 | Unsupported question handling | REQ-005 |
| F-006 | Empty input handling | REQ-006 |
| F-007 | Invalid character handling | REQ-007 |
| F-008 | Spelling mistake handling | REQ-008 |
| F-009 | Letter-case handling | REQ-009 |
| F-010 | Long-message handling | REQ-010 |
| F-011 | Repeated-message handling | REQ-011 |
| F-012 | Conversation context | REQ-012 |
| F-013 | Privacy protection | REQ-013 |
| F-014 | Response correctness and relevance | REQ-015 |
| F-015 | Response consistency | REQ-016 |
| F-016 | Response time | NFR-001 |
| F-017 | Usability and error handling | NFR-003, NFR-004 |
| F-018 | Browser compatibility and reliability | NFR-005, NFR-006 |

---

## 7. Test Approach

Manual testing will be performed using requirement-based, scenario-based, and exploratory testing techniques.

### 7.1 Requirement-Based Testing

Each requirement will be mapped to one or more test scenarios and test cases.

Every test case should include:

- Test Case ID
- Scenario ID
- Requirement ID
- Preconditions
- Test steps
- Test data
- Expected result
- Actual result
- Execution status
- Priority
- Severity if failed
- Evidence or defect ID

### 7.2 Positive Testing

Valid and clearly supported questions will be tested.

Example:

```text
How do I reset my password?