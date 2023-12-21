# Procurement Service API Documentation

This API documentation provides details on the endpoints and operations of the Procurement Service. Below are the available API endpoints with their corresponding methods, parameters, and responses.

## Authentication

### `/login` - User Login

- **Method:** `POST`
- **Summary:** User Login
- **Operation ID:** userLogin
- **Tags:** Authentication
- **Request Body:**
  - `email` (String, required): User email
  - `password` (String, required): User password
- **Responses:**
  - `200`: Successful login
  - `401`: Invalid credentials


**Example:**
```bash
curl -X POST -H "Content-Type: application/json" -d '{"email": "user@example.com", "password": "password"}' {baseUrl}/dev/login"
```

## Requests

### `/request` - Add Request

- **Method:** `POST`
- **Summary:** Add Request
- **Operation ID:** addRequest
- **Tags:** Request
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X POST -H "Content-Type: application/json" {baseUrl}/dev/request

```

### `/request` - Search Requests

- **Method:** `GET`
- **Summary:** Search Requests
- **Operation ID:** searchRequests
- **Tags:** Request
- **Responses:**
  - `200`: Successful operation



**Example:**
```bash
curl -X GET {baseUrl}/dev/request

```

### `/request/{id}` - Delete Request

- **Method:** `DELETE`
- **Summary:** Delete Request
- **Operation ID:** deleteRequest
- **Tags:** Request
- **Parameters:**
  - `id` (String, path, required): Request ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X DELETE {baseUrl}/dev/request/{id}

```

### `/request/{id}` - Update Request

- **Method:** `PUT`
- **Summary:** Update Request
- **Operation ID:** updateRequest
- **Tags:** Request
- **Parameters:**
  - `id` (String, path, required): Request ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X PUT -H "Content-Type: application/json" -d '{"email": "user@example.com", "password": "password"}' {baseUrl}/dev/request/{id}

```

### `/request/deactivate/{id}` - Deactivate Request

- **Method:** `POST`
- **Summary:** Deactivate Request
- **Operation ID:** deactivateRequest
- **Tags:** Request
- **Parameters:**
  - `id` (String, path, required): Request ID
- **Responses:**
  - `200`: Successful operation

**Example:**
```bash
curl -X POST {baseUrl}/dev/request/deactivate/{id}

```



### `/request/approve/{id}` - Approve Request

- **Method:** `POST`
- **Summary:** Approve Request
- **Operation ID:** approveRequest
- **Tags:** Request
- **Parameters:**
  - `id` (String, path, required): Request ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X POST {baseUrl}/dev/request/approve/{id}

```

## Purchase Orders

### `/purchase_order` - Add Purchase Order

- **Method:** `POST`
- **Summary:** Add Purchase Order
- **Operation ID:** addPurchaseOrder
- **Tags:** Purchase Order
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X POST -H "Content-Type: application/json" {baseUrl}/dev/purchase_order

```

### `/purchase_order` - Search Purchase Orders

- **Method:** `GET`
- **Summary:** Search Purchase Orders
- **Operation ID:** searchPurchaseOrders
- **Tags:** Purchase Order
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X GET {baseUrl}/dev/purchase_order

```

### `/purchase_order/{id}` - Delete Purchase Order

- **Method:** `DELETE`
- **Summary:** Delete Purchase Order
- **Operation ID:** deletePurchaseOrder
- **Tags:** Purchase Order
- **Parameters:**
  - `id` (String, path, required): Purchase Order ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X DELETE {baseUrl}/dev/purchase_order/{id}

```

### `/purchase_order/{id}` - Update Purchase Order

- **Method:** `PUT`
- **Summary:** Update Purchase Order
- **Operation ID:** updatePurchaseOrder
- **Tags:** Purchase Order
- **Parameters:**
  - `id` (String, path, required): Purchase Order ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X PUT -H "Content-Type: application/json" -d '{"email": "user@example.com", "password": "password"}' {baseUrl}/dev/purchase_order/{id}

```

### `/purchase_order/deactivate/{id}` - Deactivate Purchase Order

- **Method:** `POST`
- **Summary:** Deactivate Purchase Order
- **Operation ID:** deactivatePurchaseOrder
- **Tags:** Purchase Order
- **Parameters:**
  - `id` (String, path, required): Purchase Order ID
- **Responses:**
  - `200`: Successful operation


**Example:**
```bash
curl -X POST {baseUrl}/dev/purchase_order/deactivate/{id}
```
