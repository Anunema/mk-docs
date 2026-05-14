# API Reference

## Endpoints

### GET /api/status
Returns the service status.

**Response:**
```json
{
  "status": "healthy",
  "uptime": 12345
}
```

### POST /api/data
Submits data to the service.

**Request:**
```json
{
  "data": "example"
}
```
