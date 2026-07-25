# Workflow Overview

1. GitHub Trigger detects Pull Request events.
2. PR metadata is extracted.
3. GitHub API fetches changed files.
4. Source files are filtered.
5. Gemini reviews the code diff.
6. Review is posted as a GitHub comment.
