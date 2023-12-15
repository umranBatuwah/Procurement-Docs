# My Request Timeline Overview Use Case

## Actors
- **Requestor**

## Description
To facilitate creating and tracking purchase requisitions, providing users with a comprehensive form that captures essential details, request timelines, and approval statuses. The top panel offers an overview of key information, including approval status, request overview, attachments, and comments.

## Trigger Point
The trigger point for this use case is when a user decides to create a new purchase requisition.

## Precondition
The user must have valid login credentials and appropriate access rights to access the purchase requisitions form.

## Normal Flow

1. **Login:**
   - The user logs in to the system using valid credentials.

2. **Access Purchase Requisitions Form:**
   - The user navigates to the purchase requisitions section.

3. **Top Panel Overview:**
   - The top panel displays the following items:
     - Approved/Not Delivered status.
     - Request Overview, Attachments, Comment sections.
     - Creation Date.
     - Required Delivery Date.
     - Request Type.
     - Product Type.
     - Department (Finance Department).
     - Requestor Name (e.g., justinseptimus@example.com), Request Cost: $200.
     - Approver Name (e.g., hariskaif@example.com), Final Approver.

4. **Request Timeline:**
   - The request timeline provides a chronological overview of the requisition's progress:
     - Initiated the Request: Created time 04/07/2023:08:00:00 am.
     - Initiated Request Approved: Approved time 04/07/2023:08:00:00 am.
     - Send for RFQ: Created time 04/07/2023:08:00:00 am.
     - Seek Quotes: Purchase Order Confirm - Created time 04/07/2023:08:00:00 am.
     - CAB Review: Waiting for Delivery - Created time 04/07/2023:08:00:00 am.
     - Implement Request Closed - Created time 04/07/2023:08:00:00 am.
     - Validate.

5. **Order Line Details:**
   - The user enters details for each item in the requisition:
     - Line Number (automatically assigned).
     - Item Name.
     - Quantity.
     - Unit.
     - Price.
     - Total Cost.

## Post Condition
Upon successful submission, the requisition is added to the system, and relevant stakeholders are notified. The request timeline is updated based on the progress of the requisition.

## Alternative Flow

1. **Invalid Login:**
   - If the user enters incorrect login credentials, the system triggers an authentication error message, prompting the user to enter valid credentials.

2. **Error in Form Entry:**
   - If there's an error or omission in the form entry, the system triggers an error message, guiding the user to correct the information.

3. **Cancel Request:**
   - If the user decides to cancel the creation of the requisition, the system cancels the operation, and the requisition remains unchanged.

4. **Request Timeline Error:**
   - If there's an error in the request timeline progression, the system triggers an error message, and the user is prompted to review and correct the timeline entries.

## Benefits
1. **Comprehensive Overview:**
   Users get a clear overview of the requisition's key details, status, and timeline.
   
2. **Efficient Tracking:**
   The request timeline provides a step-by-step view of the requisition's progress.
   
3. **Detailed Line Items:**
   Users can specify details for each line item, ensuring accurate procurement information.

By following this use case, organizations can enhance the procurement process, allowing users to create and track purchase requisitions seamlessly.
