# Procurement Requestor - My Request Use Case

## Actors
- **Requestor**

## Description
To provide requestors with a comprehensive "My Request" dashboard, enabling them to view and manage their procurement requests efficiently. The dashboard includes key components such as creating a new request, filtering requests based on various criteria, searching for specific requests, and taking action on requests. Users can also navigate through pages and access detailed information for each request.

## Trigger Point
The trigger point for this use case is when a procurement requestor wants to access and manage their existing requests.

## Precondition
The user must have valid login credentials and appropriate access rights to access the "My Request" section.

## Normal Flow

1. **Login:**
   - The requestor logs in to the procurement requestor portal using valid credentials.

2. **Access My Request Dashboard:**
   - The requestor navigates to the "My Request" section.

3. **Top Panel Overview:**
   - The top panel displays the following options:
     - "Create New Request" button to initiate a new procurement request.
     - Numbers and categories for "All Request," "Pending Request," "Reject Request," "Approve Request," and "On Hold Request."

4. **Filtering Requests:**
   - The requestor interacts with the "Filter" dropdown button to select filtering criteria such as location, request type, creation date, delivery date, total cost, priority, and action status.

5. **Search Functionality:**
   - The requestor searches for specific requests using the "Search" function, entering keywords such as username or date.

6. **Status Action:**
   - The requestor selects an action status from the dropdown menu, choosing from options like "Pending," "Approve," "Reject," or "On Hold."

7. **Location, Request Type, Creation Date, Delivery Date, Total Cost, Priority:**
   - The requestor utilizes dropdown menus and input fields to filter requests based on specific criteria such as location, request type, creation date, delivery date, total cost, and priority.

8. **Action Icons:**
   - The requestor clicks on icons associated with each request to perform actions like viewing details, approving, rejecting, or putting a request on hold.

9. **Pagination:**
   - The requestor navigates through pages using the "Previous Page" and "Next Page" options to view additional requests.

## Post Condition
Upon performing actions or applying filters, the system updates the display to reflect the chosen criteria. Any changes made to the request status are reflected in the system.

## Alternative Flow

1. **Invalid Login:**
   - If the user enters incorrect login credentials, the system triggers an authentication error message, prompting the user to enter valid credentials.

2. **No Matching Requests:**
   - If the search or filter criteria do not match any requests, the system triggers a notification indicating no matching requests.

3. **Error in Action:**
   - If there is an error in performing an action (e.g., approval, rejection), the system triggers an error message, guiding the user to correct the information.

## Benefits
- **Efficient Request Management:**
  Users can quickly filter, search, and take action on their procurement requests.
  
- **Clear Status Overview:**
  The top panel provides a quick summary of request status categories.
  
- **Flexible Filtering:**
  Dropdown menus and input fields allow users to filter requests based on various criteria.
  
- **User-Friendly Pagination:**
  Users can navigate through multiple pages seamlessly.

By following this use case, organizations can ensure that requestors have a robust and user-friendly interface for managing their procurement requests effectively.
