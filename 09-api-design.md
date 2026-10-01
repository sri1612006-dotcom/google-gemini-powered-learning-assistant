# 9. API Design

## Endpoint

`POST /api/ask`

### Request
```json
{
  "prompt": "Explain photosynthesis in simple words."
}
```

### Response
```json
{
  "success": true,
  "answer": "Photosynthesis is the process by which green plants..."
}
```

## Additional Possible Endpoints
- `GET /api/health` – server health check
- `POST /api/summarize` – generate a summary
- `POST /api/quiz` – generate quiz questions

The backend should validate requests and return appropriate HTTP status codes for invalid input, authentication/API failures and server errors.
