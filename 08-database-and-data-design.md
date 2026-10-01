# 8. Database and Data Design

The basic version of EduGenie can operate without permanent user data storage. This reduces complexity and privacy risk for a student prototype.

If persistence is required, the following logical entities can be introduced:

### User
- user_id
- name
- email
- created_at

### LearningRequest
- request_id
- user_id
- topic
- request_type
- prompt
- created_at

### LearningResponse
- response_id
- request_id
- response_text
- model_name
- created_at

Sensitive API credentials must never be stored in frontend code or committed to GitHub.
