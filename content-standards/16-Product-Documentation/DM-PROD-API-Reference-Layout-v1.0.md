---
title: "API Reference Specification"
category: "Product Documentation"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Engineering Team"
---

# API Reference Specification

This document defines the layout schema for technical API endpoint documentation. AI models can parse these sections to generate client SDKs or automated API mock servers.

---

## 📇 Endpoint Parameters (Input Schema)

```yaml
endpoint:
  path: "/api/v1/{{RESOURCE}}"
  method: "POST / GET / PUT / DELETE"
  auth_required: true
  scope: "Vendor / School / Admin"
  description: "Detailed description of the API action."
```

---

## 🏗️ Structure Blocks

Document each API route using this modular layout:

### Endpoint: {{METHOD}} {{PATH}}
- **Authentication**: Bearer Token required. Authorized Role: `{{SCOPE}}`.

#### Request Headers
```http
Authorization: Bearer <token>
Content-Type: application/json
```

#### Request Body parameters
Provide details in this schema table:

| Field Name | Data Type | Required | Description |
| :--- | :--- | :--- | :--- |
| `rfp_id` | UUID String | Yes | Unique target RFP ID |
| `items` | Array | Yes | List of bid items |
| `items.unit_price` | Decimal | Yes | Unit price bid in INR |

#### Response: `201 Created`
```json
{
  "status": "success",
  "data": {
    "bid_id": "8f2b3e4a-9c8d-7e6f-5a4b-3c2d1e0f9a8b",
    "created_at": "2026-07-16T20:00:00Z",
    "status": "submitted"
  }
}
```

#### Response: `400 Bad Request`
Returned when validation limits are violated.
```json
{
  "status": "error",
  "message": "Bid price cannot be lower than the floor bidding limit set by the school."
}
```
