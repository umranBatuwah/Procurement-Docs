# Procurement Requestor Dashboard Use Case

## Actors
- **Requestor**

## Description
To provide a robust and user-centric procurement requestor dashboard that enables seamless monitoring and management of procurement requests. The dashboard includes key components such as request overview, requisition status, spending by category, and recent comment activity. Additionally, the dashboard offers detailed insights into the number of requests in different states: Approved, Pending, Reject, and On Hold.

## Trigger point
The user initiates the use case by logging into the system.

## Pre-conditions
- The user must possess valid login credentials.
- The user must have appropriate access permissions to view the procurement requestor dashboard.

## Postcondition
Upon completion of the normal flow, the user has gained insights into request overview, requisition status, spend by category, and recent comment activity.

## Normal Flow

1. **Dashboard Overview:**
   - Upon successful login, the user is directed to the dashboard, displaying the top panel and graphical representations.
   
2. **Detailed Request Numbers:**
   - For a more granular understanding, the dashboard provides specific request numbers for different states:
     - All Requests: Displays the number of requests that have been All Request.
     - Approved Requests: Displays the number of requests that have been approved.
     - Pending Requests: Displays the number of requests that are currently pending approval.
     - Rejected Requests: Displays the number of requests that have been rejected.

3. **Request Stats:**
   - The user explores the request status panel, utilizing the dropdown to select the desired time frame (day, week, month, year) and reviews the donut chart for request statistics.

4. **Request Trend:**
   - Presents a vertical bar graph illustrating the trend of procurement requests over a specified period.
   - Allows requestors to identify patterns and fluctuations in request activity.

## Alternative Flow

1. **Invalid Login:**
   - If the user enters incorrect credentials during login, an error message is displayed, and the user is prompted to enter valid credentials.

2. **No Recent Comments:**
   - In the "Recent Comment Activity" section, if there are no recent comments, a message is displayed indicating that there are currently no updates.

## Benefits
- **Data-Driven Decision Making:**
  The graphical representation of data empowers requestors to make informed decisions based on spending patterns and requisition status.
  
- **Time Efficiency:**
  The intuitive design and dropdown functionalities save time for requestors in gathering and analyzing procurement-related information.

- **Enhanced Collaboration:**
  The recent comment activity section promotes communication and collaboration among stakeholders involved in the procurement process.

By incorporating preconditions, postconditions, normal flow, and alternative flows, this use case ensures a user-friendly and resilient procurement requestor dashboard, contributing to effective procurement management.
