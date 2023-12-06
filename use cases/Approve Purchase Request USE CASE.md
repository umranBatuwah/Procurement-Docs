# Approve Purchase Request

## Use Case Description

The **Purchase Request Screen for Approver** is used to review and approve purchase requests submitted by requestors. The approver can view the request details, edit the request if necessary, approve the request, cancel the request, and add comments.

### Actor:
- Approver
- Requestor

### Trigger:
- The trigger for this use case is when a requestor submits a purchase request.

### Pre-Condition:
- The approver has logged in to the system.
- There is at least one pending purchase request in the system.
- The Approver has the necessary permissions to approve or reject the purchase requests.

### Postcondition:
- The purchase request is either approved or cancelled.
- The approver has added comments to the request if necessary.
- The system sends a notification to the Requester informing them of the decision.

## Normal Flow:

1. The Approver logs in to the system and navigates to the Purchase Request screen.
2. The Approver reviews the list of purchase requests in the table or applies filters to view specific requests.
3. The Approver selects a purchase request from the table by clicking on it.
4. The system displays the details of the selected purchase request, including the requestor's name, expected delivery date, location, total cost, and line-item details.
5. The Approver reviews the purchase request and any attached files, such as quotes or invoices.
6. If the purchase request meets the Approver's standards, they click the "Approve" button.
   - The system updates the status of the purchase request to "Approved" and sends a notification to the Requester.
7. If the purchase request does not meet the Approver's standards, they click the "Reject" button.
   - The system updates the status of the purchase request to "Rejected" and sends a notification to the Requester explaining the reason for rejection.
8. If the Approver wants to modify the purchase request, they click the "Modify" button.
   - The system allows the Approver to modify the purchase request and resubmit it for approval.
9. Once the Approver has taken action on the purchase request, they return to the Purchase Request screen to review any remaining purchase requests.

## Alternative Flow:

- If the Approver needs additional information about the purchase request, they add a comment to the request and contact the Requester to provide the necessary details.
