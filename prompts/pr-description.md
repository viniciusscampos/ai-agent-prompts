---
title: Pull Request Description Generator
compatibleWith: [copilot]
tags: [documentation, automation]
---

# Generate Pull Request Title and Description

Based on the changes in the current Git branch (`git diff`), generate:

1. A clear and concise **title** for the pull request (max 60 characters)
2. A **summary** of the key changes, including:
   - The **motivation** behind the work
   - What was added, changed, or removed
   - Any key files or components affected

🎯 The goal is to assist in quickly writing PR titles and descriptions that are informative for code reviewers.

📄 **Output format**:

```
## Title
<insert generated title here>

## Description
<insert generated summary here>
```

Use a technical and professional tone. Be specific and avoid vague terms like “minor fix” or “small update”.
