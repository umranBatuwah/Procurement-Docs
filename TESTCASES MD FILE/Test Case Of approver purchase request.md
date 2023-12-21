**Test Case: Approver - Purchase Request.**

**Objective:** 

- To verify that the approver can successfully review and approve a purchase request in the procurement web application.

**Preconditions:**

- The procurement web application is accessible, and the user has a valid internet connection.
- The user has appropriate role-based access as an approver.
- A purchase request is created and pending approval.

**Test Steps:**

**1. Login as Approver:**

- Log in to the procurement web application with valid approver credentials.
- Ensure that the login is successful.

**2. Navigate to Purchase Requests:**

- Locate and click on the "Purchase Requests" or similar section in the application menu.

**3. View Pending Purchase Requests:**

- Verify that a list of purchase requests is displayed.
- Confirm that there is at least one purchase request in a "Pending Approval" status.

**4. Positive Test Case - Approve Purchase Request:**

- Select a purchase request in "Pending Approval" status.
- Review the details of the purchase request, including items, quantities, and cost.
- Click on the "Approve" button.
- Confirm that the system prompts for confirmation before approval.
- Verify that the purchase request is now marked as "Approved."

**5. Positive Test Case - View Approved Purchase Request:**

- Navigate back to the list of purchase requests.
- Confirm that the previously approved purchase request is now marked as "Approved" in the list.

**6. Verification of Notification**:

- Confirm that the requester receives a notification when their purchase request is approved or rejected.
- Verify that the notification includes relevant details such as the status of the request and any comments provided by the approver.

**Postconditions:**

- The purchase request is successfully approved or rejected based on the actions performed by the approver.
- The system maintains an accurate record of the approval/rejection actions in the audit trail.
- The requester is appropriately notified of the approval or rejection of their purchase request.

