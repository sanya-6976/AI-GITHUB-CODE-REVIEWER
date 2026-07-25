<img width="1855" height="665" alt="Screenshot 2026-07-25 135143" src="https://github.com/user-attachments/assets/11f048a7-3edc-480c-81ad-7022f379fc0c" /># 🤖 CodeGuardian AI

> An AI-powered GitHub Pull Request Reviewer built with **n8n**, **GitHub API**, and **Google Gemini**.

Automatically reviews pull requests, analyzes changed code, detects security and performance issues, and posts structured AI-powered feedback directly on GitHub.

---

## ✨ Features

- 🔄 Automatic GitHub Pull Request Trigger
- 🤖 AI-powered code review using Google Gemini
- 📂 Reviews only modified source code files
- 🔒 Security analysis
- ⚡ Performance optimization suggestions
- 🧹 Clean Code & SOLID principle checks
- 🧪 Testing recommendations
- 📚 Documentation suggestions
- ⭐ Engineering scorecard
- 💬 Automatically posts review comments on GitHub

---

## 🏗 Architecture

```text
GitHub Pull Request
        │
        ▼
GitHub Trigger
        │
        ▼
Extract PR Metadata
        │
        ▼
Fetch Changed Files
        │
        ▼
Filter Source Files
        │
        ▼
Google Gemini
        │
        ▼
AI Review Generation
        │
        ▼
GitHub Comment API
        │
        ▼
Pull Request Review
```

---

## 🛠 Tech Stack

- n8n
- GitHub REST API
- Google Gemini
- OAuth2 Authentication
- HTTP Request Node
- AI Prompt Engineering

---

## 🚀 Workflow

1. Detect Pull Request event
2. Fetch changed files
3. Ignore non-code files
4. Send Git diff to Gemini
5. Generate structured review
6. Post review to GitHub

---

## 📋 AI Review Includes

- Executive Summary
- Critical Issues
- Security Review
- Performance Review
- Code Quality Analysis
- Architecture Suggestions
- Testing Recommendations
- Documentation Review
- Engineering Scorecard
- Pull Request Decision

---

## 📸 Screenshot:-
<img src=images/workflow>


---

## 🔮 Future Improvements

- Inline code review comments
- Multi-model AI support
- Slack & Discord integration
- Review analytics dashboard
- Automatic unit test generation
- AI-generated release notes

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

---

## 📜 License

MIT License
