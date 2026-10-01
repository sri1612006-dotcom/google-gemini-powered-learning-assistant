# 13. Algorithms and Pseudocode

## Algorithm: Generate Learning Answer

```text
START
  Read user prompt
  IF prompt is empty
      Display validation message
      STOP
  END IF

  Validate input length
  Create educational prompt
  Send request to backend
  Backend calls Gemini API

  IF API returns an error
      Display error message
  ELSE
      Receive generated answer
      Display answer to user
  END IF
END
```

## Quiz Generation Algorithm
1. Read topic.
2. Validate topic.
3. Create quiz-specific prompt.
4. Request structured questions.
5. Validate returned content.
6. Display questions and answers.
