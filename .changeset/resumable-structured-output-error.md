---
"@ai-hero/sandcastle": patch
---

`StructuredOutputError` now carries `sessionId` and `sessionFilePath` from the run that produced the failed output, so callers can resume that session with feedback to re-emit corrected output instead of repeating the work.
