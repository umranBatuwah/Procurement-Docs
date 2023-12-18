# My Request Timeline Comment Use Case

## Actors
- **Requestor**

## Description
To provide users with a detailed timeline view of their requests, displaying key events and allowing users to comment and track the progress. The top panel shows the approval status, delivery status, and a comment box for users to add comments or view existing ones.

## Trigger Point
The trigger point for this use case is when a user accesses the "My Request Timeline" section to track the progress of their submitted requests.

## Precondition
The user must have valid login credentials and appropriate access rights to access the request timeline.

## Normal Flow

1. **Login:**
   - The user logs in to the system using valid credentials.

2. **Access My Request Timeline:**
   - The user navigates to the "My Request Timeline" section.

3. **Top Panel Overview:**
   - The top panel displays the following items:
     - Approved/Not Delivered status.
     - Comment box for users to add comments or view existing ones.

4. **Commenting:**
   - The user can add comments or view existing comments in the comment box.
   <p>
   <img src="images/commenting.jpg">
   </p>
5. **Request Timeline:**
   - The request timeline provides a chronological overview of the request's progress:
     - Initiated the Request: Created time 04/07/2023:08:00:00 am.
     - Initiated Request Approved: Approved time 04/07/2023:08:00:00 am.
     - Send for RFQ: Created time 04/07/2023:08:00:00 am.
     - Seek Quotes: Purchase Order Confirm - Created time 04/07/2023:08:00:00 am.
     - CAB Review: Waiting for Delivery - Created time 04/07/2023:08:00:00 am.
     - Implement Request Closed - Created time 04/07/2023:08:00:00 am. Validate.

6. **Order Line Details:**
   - The request timeline includes details for each item in the request:
     - Line Number (automatically assigned).
     - Item Name.
     - Quantity.
     - Unit.
     - Price.
     - Total Cost.

## Post Condition
The user has a comprehensive view of the request timeline, including approval status, delivery status, and comments. Any new comments are added to the system.

## Alternative Flow

1. **Invalid Login:**
   - If the user enters incorrect login credentials, the system triggers an authentication error message, prompting the user to enter valid credentials.

2. **Error in Request Timeline:**
   - If there's an error in retrieving or displaying the request timeline, the system triggers an error message, and the user is prompted to try again.

3. **No Comments Available:**
   - If there are no comments available for the request, the system displays a message indicating no comments.

4. **Error in Commenting:**
   - If there's an error in adding a new comment, the system triggers an error message, guiding the user to try again.

## Benefits
1. **Transparent Progress Tracking:**
   Users can monitor the progress of their requests through a detailed timeline.

2. **Interactive Commenting:**
   Users can provide and view comments, facilitating communication throughout the request lifecycle.

3. **Quick Overview:**
   The top panel provides a quick summary of the approval and delivery status.

By following this use case, organizations can enhance the user experience by providing a detailed and interactive timeline for users to track the progress of their requests.
