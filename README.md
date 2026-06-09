# Status Codes You Will Use Most Often as a Backend Developer
```txt
200 OK
201 Created
204 No Content

400 Bad Request
401 Unauthorized
403 Forbidden
404 Not Found
409 Conflict
422 Unprocessable Entity
429 Too Many Requests

500 Internal Server Error
503 Service Unavailable
```
These 11 status codes cover roughly **90–95% of typical CRUD API development** in the software industry.

## 1xx — Informational (Rarely Used in API Development)

| Code | Message             | Purpose                                         |
| ---- | ------------------- | ----------------------------------------------- |
| 100  | Continue            | Client can continue sending request             |
| 101  | Switching Protocols | Used when switching protocols (e.g., WebSocket) |

---

## 2xx — Success Responses

| Code | Message    | When Used                       |
| ---- | ---------- | ------------------------------- |
| 200  | OK         | Request successful              |
| 201  | Created    | New resource created            |
| 202  | Accepted   | Request accepted for processing |
| 204  | No Content | Success but nothing to return   |

---

## 3xx — Redirection (Less Common in APIs)

| Code | Message           | When Used                    |
| ---- | ----------------- | ---------------------------- |
| 301  | Moved Permanently | Resource permanently moved   |
| 302  | Found             | Temporary redirect           |
| 304  | Not Modified      | Browser cache is still valid |

---

## 4xx — Client Errors

These are among the most commonly used status codes.

| Code | Message              | When Used                               |
| ---- | -------------------- | --------------------------------------- |
| 400  | Bad Request          | Invalid request data                    |
| 401  | Unauthorized         | Login/authentication required           |
| 403  | Forbidden            | User authenticated but lacks permission |
| 404  | Not Found            | Resource does not exist                 |
| 405  | Method Not Allowed   | Wrong HTTP method used                  |
| 409  | Conflict             | Duplicate data/conflicting state        |
| 422  | Unprocessable Entity | Validation failed                       |
| 429  | Too Many Requests    | Rate limit exceeded                     |

---

## 5xx — Server Errors

These indicate a problem on the server side.

| Code | Message               | When Used                            |
| ---- | --------------------- | ------------------------------------ |
| 500  | Internal Server Error | Unexpected server error              |
| 501  | Not Implemented       | Feature not implemented              |
| 502  | Bad Gateway           | Invalid response from another server |
| 503  | Service Unavailable   | Server temporarily unavailable       |
| 504  | Gateway Timeout       | Upstream server timeout              |

---



