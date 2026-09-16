# Cravio – Testing & UAT

This section documents the testing and User Acceptance Testing (UAT) approach for the **Cravio – Online Food Delivery Platform**.

Testing activities are used to verify that the proposed solution meets the documented functional requirements and business expectations.

---

## Testing Approach

The project follows a structured validation flow:

```text
Development
     ↓
QA Testing
     ↓
Bug Identification
     ↓
Bug Fix
     ↓
Retesting
     ↓
UAT
     ↓
UAT Sign-off
     ↓
Go Live
```

---

## Test Scenarios

A **Test Scenario** describes what needs to be tested at a high level.

Example:

**Scenario:** Verify customer registration functionality.

Possible areas to validate:

* Valid registration details
* Invalid registration details
* Mandatory field validation
* Duplicate email/mobile validation
* Password validation
* Successful account creation

---

## Test Cases

A **Test Case** defines the detailed steps required to verify a specific functionality.

Typical Test Case fields include:

| Field           | Description                        |
| --------------- | ---------------------------------- |
| Test Case ID    | Unique identifier                  |
| Test Scenario   | Functionality being tested         |
| Objective       | Purpose of the test                |
| Preconditions   | Conditions required before testing |
| Test Data       | Data used during testing           |
| Test Steps      | Detailed execution steps           |
| Expected Result | Expected system behavior           |
| Actual Result   | Observed system behavior           |
| Status          | Pass / Fail                        |

---

## Positive Testing

Positive testing verifies that the system works correctly when valid inputs and expected user actions are provided.

**Example:**

A customer enters valid registration details and successfully creates an account.

**Expected Result:**
The customer account should be created successfully.

---

## Negative Testing

Negative testing verifies how the system handles invalid inputs, incorrect actions, or exceptional conditions.

**Example:**

A customer attempts to register using an already registered email address.

**Expected Result:**
The system should display an appropriate validation message and prevent duplicate registration.

---

## Bug Management

When a test case fails, the issue can be recorded as a Bug in Jira.

```text
Test Case
    ↓
Fail
    ↓
Bug Created
    ↓
Developer Fix
    ↓
Retest
    ↓
Pass
    ↓
Done
```

---

## UAT – User Acceptance Testing

**User Acceptance Testing (UAT)** is performed to verify whether the solution satisfies the agreed business requirements and is acceptable for business use.

UAT focuses on business workflows from the perspective of intended users or business representatives.

### Example UAT Scenario

**Scenario:** Customer places an online food order.

The UAT flow may include:

1. Customer logs in.
2. Customer browses restaurants.
3. Customer selects food items.
4. Customer adds items to the cart.
5. Customer completes checkout.
6. Customer makes payment.
7. Customer receives order confirmation.
8. Customer tracks the delivery.

**Expected Outcome:**
The complete business workflow should function according to the agreed requirements.

---

## Business Analyst Role in UAT

The Business Analyst supports UAT by:

* Preparing UAT scenarios and test cases.
* Explaining business requirements.
* Coordinating with business users.
* Clarifying requirements with QA and development teams.
* Documenting UAT feedback.
* Coordinating issue resolution.
* Supporting UAT sign-off.

---

## QA Testing vs UAT

| QA Testing                                  | UAT                                            |
| ------------------------------------------- | ---------------------------------------------- |
| Focuses on system functionality and quality | Focuses on business acceptance                 |
| Usually performed by QA/Testers             | Performed by business users or representatives |
| Verifies functional behavior                | Verifies business requirements and workflows   |
| Identifies defects                          | Determines business readiness and acceptance   |

---

## Project Status

The testing and UAT section demonstrates the planned validation process for the Cravio portfolio project.

The artifacts provide a practical understanding of how requirements are validated before a solution moves toward production.
