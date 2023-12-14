# Use Case for Purchase Requisition Tracking

## Actor:
- Approver
- Requester: Initiates and tracks the purchase requisition.

## Trigger Point:
The requester wants to track the status and details of a purchase requisition.

## Preconditions:
- The requester has valid credentials to access the purchase requisition tracking system.
- A purchase requisition has been previously initiated.

## Postconditions:
The requester gains insights into the status and details of the purchase requisition.

## Normal Flow:

### Login and Overview:
- The requester logs into the purchase requisition tracking system.
- The top panel displays the Request Overview Panel with details such as creation date, required delivery date, request type, department, priority, and location.

### Request Timeline Panel:
- The requester navigates to the Request Timeline Panel.
- The timeline updates include:
  - Initiate the request.
  - Request approved.
  - Purchase order confirmed.
  - Waiting for delivery.
  - Order confirmation.
  - Request closed.

### Order Line Panel:
- The requester checks the Order Line Panel.
- Details displayed include:
  - Line number
  - Item name
  - Quantity
  - Unit
  - Price
  - Total cost.

### Tracking Updates:
- The requester monitors the timeline for updates, providing a chronological view of the request's progress.
- Checks the status and any recent updates to understand where the request is in the procurement process.

## Alternative Flow:
- If the requester encounters an issue logging in:
  - The system prompts the requester to re-enter credentials.
  - If issues persist, the requester contacts the IT support team.
- If the requester needs to modify the purchase requisition:
  - The system allows the requester to edit certain details (if permitted) and notifies relevant parties of the changes.
  - The timeline is updated to reflect modifications.

## Exceptional Flow:
- If there is a delay in the procurement process:
  - The system generates an alert, notifying the requester of the delay and providing relevant details.
  - The requester can contact the procurement department or relevant authorities for further information.
- If there are discrepancies in the order line details:
  - The system highlights the discrepancies, and the requester can communicate with the procurement officer to address the issues.

**Note:** The use case describes a simplified procurement tracking process, and in a real-world scenario, the steps and details may vary based on the specific procurement system and organization's processes.
