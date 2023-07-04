# Account Service

This microservice handles the lifecycle of Accounts.

## Health Endpoint

### GET /health

Returns the health status of the service.

## Create a New Account

### POST /accounts

Creates a new Account.

#### Request

- Method: POST
- URL: `/accounts`
- Content-Type: `application/json`

Example Request Body:
```json
{
  "name": "John Doe",
  "email": "johndoe@example.com",
  "address": "123 Main St",
  "phone_number": "555-1234"
}
