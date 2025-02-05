# tasko

# HNG12 Backend Stage 0 - Public API

Welcome to the Stage 0 task for HNG12! This project implements a **public API** that returns basic information, including:
- Your registered email address.
- The current datetime in ISO 8601 format.
- The GitHub URL of your project’s codebase.

## API Endpoint

### `GET /`

This API endpoint responds to `GET` requests at the root URL and returns the following JSON data:

**Response Example:**
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
