# AI_CODE_DEBUG_HELPER
AI Debug Helper is a full-stack developer tool that validates Python, C, C++, and Java code in-browser with real compiler/runtime checks, editor error highlighting, and an AI debugging assistant. It gives instant syntax and compile feedback, suggestions, and chat-based help to speed up debugging.
Collecting project details from package manifests and README files to summarize it accurately.

Read [](file:///d%3A/ai-debug-helper/package.json)

Read [](file:///d%3A/ai-debug-helper/frontend/src/App.js#1-1), lines 1 to 200

Read [](file:///d%3A/ai-debug-helper/backend/README.md)

Read [](file:///d%3A/ai-debug-helper/frontend/README.md)

Read [](file:///d%3A/ai-debug-helper/backend/index.js)

Reviewing analyzer and chatbot files for a stronger project summary.

Read [](file:///d%3A/ai-debug-helper/frontend/src/components/Chatbot.jsx)

Read [](file:///d%3A/ai-debug-helper/backend/analyzer.js#1-1), lines 1 to 250

## GitHub Description / README Intro

**AI Debug Helper** is a full-stack debugging assistant built to help developers write, validate, and fix code faster.

- Frontend: React + CodeMirror 6 editor
- Backend: Node.js + Express
- Languages supported: Python, C, C++, Java
- Features:
  - syntax/compile checks for submitted code
  - runtime error detection
  - editor line highlighting for error locations
  - AI chatbot support with Groq
  - chat history persistence with SQLite

### What it does
- Accepts code and language from the browser
- Runs language-specific checks on the backend
  - Python syntax and execution via `python -m py_compile`
  - C/C++ compile via `gcc` / `g++`
  - Java compile/run via `javac` / `java`
- Returns structured analysis results:
  - errors
  - explanation
  - suggestions
  - line numbers
- Stores submissions and chat history in SQLite

### Why it’s cool
- Combines real compiler/runtime feedback with AI-assisted debugging
- Provides an interactive learning/debugging UI
- Useful for learning, prototyping, and catching syntax issues quickly

---

## Suggested GitHub README Summary

**AI Debug Helper** is a developer tool for interactive code debugging and learning. It combines a React-based code editor with a backend analysis service that runs actual language tooling and returns actionable feedback.

Built with:
- React 19
- CodeMirror 6 editor
- Express.js backend
- SQLite for persistence
- Groq AI integration for chatbot responses

Run locally:
1. `cd backend && npm install && npm start`
2. `cd frontend && npm install && npm start`
3. Open frontend and start debugging Python, C, C++, or Java code

