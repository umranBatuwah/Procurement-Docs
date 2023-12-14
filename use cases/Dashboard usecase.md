# Use Case: Procurement Admin Dashboard

## Actor:
- Admin

## Use Case Description:
This procurement dashboard acts as the central nerve centre for overseeing and managing procurement activities. The dashboard has various modules that provide a comprehensive overview of the entire procurement landscape, enabling the admin to make informed decisions.

## Trigger Point:
The procurement admin initiates this use case when a thorough understanding of the current state of the procurement process is needed.

## Preconditions:
- The admin is a registered user with valid credentials to log into the system.
- The procurement data is up-to-date and synchronized with the dashboard.

## Post-Condition:
Upon successful completion of the use case:
- The admin acquires access to the procurement admin dashboard.
- The dashboard displays the latest procurement data and analytics.

## Normal Flow:

1. The admin starts the process by logging into the system using their valid credentials.
2. The dashboard loads, presenting an initial overview with the top panel displaying key metrics:
   - Purchase Requisitions
   - Purchase Orders
   - Invoice Count
   - Total RFQs

3. The admin explores detailed insights through various panels:

   A. **Spend Analysis Panel:**
      - Views a dynamic horizontal bar graph representing the top spending categories. This provides a visual breakdown of where the procurement budget is allocated.

   B. **Requisition Stats Panel:**
      - Examines a detailed donut chart offering insights into requisition statistics. The admin moves to the Requisition Stats Panel, now enhanced to provide more detailed information.
      - Within the donut chart, different segments represent the status of requisitions:
         - Approved Requisitions
         - In Progress Requisitions
         - Rejected Requisitions

   C. **Purchase Order Panel:**
      - Analyses a complete line graph that illustrates the status of active, approved, and settled purchase orders throughout the year.
      - This helps the admin track the progress and efficiency of the procurement process.

   E. **Monthly Expenses Panel:**
      - Views a vertical bar graph providing a detailed monthly breakdown of expenses. This enables the admin to identify patterns, forecast future expenses, and ensure budget compliance.

   D. **Notifications and Activities:**
      - The top right panel provides notifications and activities.
      - The admin can view alerts, updates, and recent activities related to the procurement process.

## Alternative Flow:

- If the admin encounters issues logging in:
  - The system prompts the admin to re-enter their password.
  - If login issues persist, the admin contacts the IT support team for assistance.
