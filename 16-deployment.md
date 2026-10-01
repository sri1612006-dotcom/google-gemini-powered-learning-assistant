# 16. Deployment

## Deployment Steps

1. Push the source code to GitHub.
2. Create a production environment on the selected hosting platform.
3. Configure environment variables.
4. Install dependencies.
5. Build the frontend.
6. Start the backend.
7. Test the public URL.

## Required Environment Variables

```env
GEMINI_API_KEY=your_api_key_here
PORT=5000
```

Never place a real API key in README files, screenshots or source code.

## Post-Deployment Checks
- Open the live URL.
- Test the home page.
- Submit a sample question.
- Verify the AI response.
- Check browser console and server logs for errors.
