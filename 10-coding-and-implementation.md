# 10. Coding and Implementation

A recommended repository structure is:

```text
EduGenie/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── package.json
├── server/
│   ├── routes/
│   ├── services/
│   ├── middleware/
│   ├── server.js
│   └── package.json
├── .env.example
├── .gitignore
└── README.md
```

Implementation should keep frontend and backend responsibilities separate. The frontend handles presentation, while the backend validates requests and communicates with Gemini.

### Example backend flow
```text
Receive request
      ↓
Validate input
      ↓
Build educational prompt
      ↓
Call Gemini API
      ↓
Validate response
      ↓
Return JSON to frontend
```
