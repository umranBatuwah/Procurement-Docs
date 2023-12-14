<!-- ### Add Request API

**Method:** POST  
**Endpoint:** /request  

**Workflow:**
1. Parse event body as JSON.
2. Connect to the database.
3. Execute SQL to insert the request.
4. Return success or error response.

---

### Search Requests API

**Method:** GET  
**Endpoint:** /request  

**Workflow:**
1. Connect to the database.
2. Execute SQL to retrieve requests.
3. Return the list of requests.

---

### Delete Request API

**Method:** DELETE  
**Endpoint:** /request/{id}  

**Workflow:**
1. Extract request ID.
2. Connect to the database.
3. Execute SQL to delete the request.
4. Return success or error response.

---

### Update Request API

**Method:** PUT  
**Endpoint:** /request/{id}  

**Workflow:**
1. Extract request ID and updated data.
2. Connect to the database.
3. Execute SQL to update the request.
4. Return success or error response.

---

### Deactivate Request API

**Method:** POST  
**Endpoint:** /request/deactivate/{id}  

**Workflow:**
1. Extract request ID.
2. Connect to the database.
3. Execute SQL to deactivate the request.
4. Return success or error response.

---

### Approve Request API

**Method:** POST  
**Endpoint:** /request/approve/{id}  

**Workflow:**
1. Extract request ID and approval details.
2. Connect to the database.
3. Check authorization.
4. Execute SQL to update the request status.
5. Return success or error response.

---

### Add Approvers API

**Method:** POST  
**Endpoint:** /approvers  

**Workflow:**
1. Extract approver data.
2. Connect to the database.
3. Execute SQL to insert the approver.
4. Return success or error response.

---

### Search Approvers API

**Method:** GET  
**Endpoint:** /approvers  

**Workflow:**
1. Connect to the database.
2. Execute SQL to retrieve approvers.
3. Return the list of approvers.

---

### Delete Approvers API

**Method:** DELETE  
**Endpoint:** /approvers/{id}  

**Workflow:**
1. Extract approver ID.
2. Connect to the database.
3. Execute SQL to delete the approver.
4. Return success or error response.

---

### Update Approvers API

**Method:** PUT  
**Endpoint:** /approvers/{id}  

**Workflow:**
1. Extract approver ID and updated data.
2. Connect to the database.
3. Execute SQL to update the approver.
4. Return success or error response.

### Add Purchase Order API

**Method:** POST  
**Endpoint:** /purchase_order  

**Workflow:**
1. Parse event body as JSON.
2. Connect to the database.
3. Execute SQL to insert the purchase order.
4. Return success or error response.

---

### Search Purchase Orders API

**Method:** GET  
**Endpoint:** /purchase_order  

**Workflow:**
1. Connect to the database.
2. Execute SQL to retrieve purchase orders.
3. Return the list of purchase orders.

---

### Delete Purchase Order API

**Method:** DELETE  
**Endpoint:** /purchase_order/{id}  

**Workflow:**
1. Extract purchase order ID.
2. Connect to the database.
3. Execute SQL to delete the purchase order.
4. Return success or error response.

---

### Update Purchase Order API

**Method:** PUT  
**Endpoint:** /purchase_order/{id}  

**Workflow:**
1. Extract purchase order ID and updated data.
2. Connect to the database.
3. Execute SQL to update the purchase order.
4. Return success or error response.

---

### Deactivate Purchase Order API

**Method:** POST  
**Endpoint:** /purchase_order/deactivate/{id}  

**Workflow:**
1. Extract purchase order ID.
2. Connect to the database.
3. Execute SQL to deactivate the purchase order.
4. Return success or error response. -->



# Common Workflow Function
Function CommonWorkflow(action, endpoint, id = null, data = null):
    1. If action is "POST":
        - Parse event body as JSON.
        - Connect to the database.
        - Execute SQL to insert data.
        - Return success or error response.
    2. If action is "GET":
        - Connect to the database.
        - Execute SQL to retrieve data.
        - Return the list of data.
    3. If action is "DELETE":
        - Extract ID.
        - Connect to the database.
        - Execute SQL to delete data.
        - Return success or error response.
    4. If action is "PUT":
        - Extract ID and updated data.
        - Connect to the database.
        - Execute SQL to update data.
        - Return success or error response.

# Add Request API
CommonWorkflow("POST", "/request")

# Search Requests API
CommonWorkflow("GET", "/request")

# Delete Request API
CommonWorkflow("DELETE", "/request/{id}")

# Update Request API
CommonWorkflow("PUT", "/request/{id}")

# Deactivate Request API
CommonWorkflow("POST", "/request/deactivate/{id}")

# Approve Request API
Function ApproveRequest(id, approvalDetails):
    1. Extract request ID and approval details.
    2. Connect to the database.
    3. Check authorization.
    4. Execute SQL to update the request status.
    5. Return success or error response.
ApproveRequest("/request/approve/{id}")

# Add Approvers API
CommonWorkflow("POST", "/approvers")

# Search Approvers API
CommonWorkflow("GET", "/approvers")

# Delete Approvers API
CommonWorkflow("DELETE", "/approvers/{id}")

# Update Approvers API
CommonWorkflow("PUT", "/approvers/{id}")

# Add Purchase Order API
CommonWorkflow("POST", "/purchase_order")

# Search Purchase Orders API
CommonWorkflow("GET", "/purchase_order")

# Delete Purchase Order API
CommonWorkflow("DELETE", "/purchase_order/{id}")

# Update Purchase Order API
CommonWorkflow("PUT", "/purchase_order/{id}")

# Deactivate Purchase Order API
CommonWorkflow("POST", "/purchase_order/deactivate/{id}")
