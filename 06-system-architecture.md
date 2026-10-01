# 6. System Architecture

EduGenie follows a client-server architecture.

```text
+---------------------+
|       Student       |
+----------+----------+
           |
           v
+---------------------+
|   React Frontend    |
| UI / Forms / Chat   |
+----------+----------+
           |
           | HTTPS / REST API
           v
+---------------------+
| Node.js Backend     |
| Validation / Prompt |
| API Security        |
+----------+----------+
           |
           | Gemini API
           v
+---------------------+
| Google Gemini Model |
+----------+----------+
           |
           v
+---------------------+
| Generated Response  |
+---------------------+
```

The backend keeps the API key away from the browser and controls communication with the AI service.
