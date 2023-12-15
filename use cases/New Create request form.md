# Procurement Requestor - New Create Request Form Use Case

## Actors
- **Requestor**

## Description
To streamline the process of initiating procurement requests by providing requestors with an intuitive and feature-rich new request form. The form includes essential details for order creation, such as delivery date, department, location, priority, and notes. Users can also manage order line items seamlessly. The form features buttons for submitting, deleting, and adding items, ensuring a user-friendly experience.

## Trigger Point
The trigger point for this use case is when a procurement requestor intends to initiate a new request.

## Precondition
The user must have valid login credentials and appropriate access rights to access the procurement requestor portal.

## Normal Flow

1. **Login:**
   - The requestor logs in to the procurement requestor portal using valid credentials.

2. **Access New Request Form:**
   - The requestor navigates to the new request form section.

3. **Top Panel Entry:**
   - The requestor fills in the top panel details:
     - Required Delivery Date: Selected from a calendar dropdown menu.
     - Select Department: Chosen from a dropdown menu.
     - Select Location: Chosen from a dropdown menu.
     - Select Priority: Chosen from a dropdown menu.
     - Notes: Any additional information is entered in a free-text field.

4. **Order Approval Indication:**
   - The requestor indicates whether the order requires approval by checking the "This order needs your approval" checkbox.

5. **Action Buttons:**
   - The requestor can choose to:
     - Click the "Submit" button to submit the request.
     - Click the "Delete" button to discard the request.

6. **Adding Items:**
   - The requestor clicks the "Add Items" button to add details for each item.

7. **Order Line Details (For Each Item):**
   - The requestor fills in details for each item in the order line, including item name, quantity, unit, price, and any additional actions.

8. **Attachment Document:**
   - The user has the option to attach relevant documents to the requisition.

9. **Comment:**
   - The user can add comments to provide additional information or context.

## Post Condition
Upon successful submission, the new request is added to the procurement system, and relevant stakeholders are notified. If deleted, the request is discarded.

## Alternative Flow

1. **Invalid Login:**
   - If the user enters incorrect login credentials, the system triggers an authentication error message, prompting the user to enter valid credentials.

2. **Cancel Request:**
   - Instead of submitting, the requestor clicks the "Delete" button to discard the new request.

3. **Error in Item Entry:**
   - If there's an error or omission in the details of an added item, the system triggers an error message, guiding the user to correct the information.

## Benefits
- **Efficient Data Entry:**
  Dropdown menus and calendars facilitate quick and accurate data entry.
  
- **Flexible Order Management:**
  Users can easily add, edit, or remove line items to customize their request.
  
- **Approval Control:**
  The checkbox allows requestors to explicitly indicate whether approval is required.
  
- **Intuitive Navigation:**
  Clear buttons guide users through the submission and deletion process.

By following this use case, organizations can ensure a smooth and effective process for requestors to initiate and manage procurement requests.
