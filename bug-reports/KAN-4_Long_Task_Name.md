# KAN-4 — Long Task Name Overflows the To-Do List

**Issue type:** Bug (training example)  
**Priority:** Low  
**Verification status:** Not confirmed — requires reproduction  
**Tool:** Jira

## Description
A very long task name was previously observed extending beyond the To-Do List interface. The issue requires further verification using an exact 200-character input.

## Preconditions
- The To-Do List application is open.
- The task input field is available.

## Steps to Reproduce
1. Open the To-Do List application.
2. Enter a task name containing exactly 200 characters.
3. Click the "Add" button.
4. Observe how the task name is displayed.

## Expected Result
The complete task name remains readable and does not overflow the list container.

## Actual Result
Previous observation: a very long task name appeared to extend beyond the list container.

This result has not yet been confirmed with the exact 200-character test data.

## Environment
Not documented — to be completed during verification.

## Evidence
No verified screenshot attached.

## Next Steps
- Reproduce the issue using exactly 200 characters.
- Record the browser, operating system, and application version.
- Capture a screenshot if the issue occurs.
- Update the Jira issue with the verified result.

**Disclaimer:** This is a training bug report based on an earlier observation. It is not presented as a confirmed defect.
