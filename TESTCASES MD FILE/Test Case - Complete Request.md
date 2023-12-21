**Test Case: Procurement Web Application - Complete Request**

**Objective:** 

- To verify the end-to-end functionality of creating, tracking, and managing a procurement request in the web application.

**Preconditions:**

- User is logged into the procurement web application.
- The application is accessible and responsive.

**Test Steps:**

1. **Create Request:**
- Click on the "Create Request" button in the top panel.
- Fill in all required fields such as request type, department, priority, location, request cost, and final approver.
- Add order lines with item name, quantity, unit, price, and any other necessary details.
- Attach a document to the request.
- Add a comment if applicable.
- Click on the "Submit" or "Save" button.

**Track Request:**

- Navigate to the "Track Request" section in the top panel.
- Enter the request number (e.g., Request No 06) in the provided field.
- Click on the "Track" button.
- Verify that the request details are displayed correctly.

**Attachment:**

- In the request overview, verify that the attached document is accessible.
- Download the attached document and confirm its content.

**Comment:**

- Add a new comment to the request.
- Check that the comment is successfully added and displayed in the request overview.

**Success Message:**

- After submitting the request, verify that a success message is displayed.
- Confirm that the request is successfully stored in the system.

**Edit Request:**

**Navigate to the "Request Overview."**

- Click on the "Edit" button.
- Modify some details in the request (e.g., change the priority).
- Save the changes and confirm that the request is updated.

**Repeat Request:**

- Click on the "Repeat Request" button.
- Verify that the new request inherits details from the original request.
- Modify some details if necessary and submit the repeated request.

**Delete Request:**

- Navigate to the "Request Overview."
- Click on the "Delete Request" button.
- Confirm the deletion and verify that the request is removed from the system.

**Expected Results:**

- The request creation process is smooth without errors.
- The tracking functionality provides accurate and up-to-date information.
- Request overview displays all relevant details correctly.
- Attachments and comments are accessible and functional.
- Success messages confirm the successful execution of actions.
- Editing and repeating requests work as expected.
- Deletion of requests removes them from the system.

**Postconditions:**

- The application state is consistent after performing the test.
- The user is returned to the home page or relevant page after completing each test step.

