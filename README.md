Core Objective
An AI platform that serves two primary functions: flagging hidden contract risks for everyday professionals and summarizing lengthy court judgments for legal researchers.

Key Requirements
Functional: Secure document uploads (PDF/DOCX), dual AI workflows (contract risk analysis vs. judgment summarization), an interactive split-screen viewer to map insights to original text, and user dashboards.

Non-Functional: Strict privacy (end-to-end encryption, auto-deletion of processed files), fast performance (30-60 seconds for 50 pages), and mandatory disclaimers that the output is not formal legal advice.

Technical Architecture
Frontend: React.js (Vite) and Tailwind CSS.

Backend & Database: Node.js, Express.js, and MongoDB.

AI Layer: External LLM APIs (OpenAI or Anthropic) or a custom Python NLP microservice.

MVP (Minimum Viable Product) Strategy
Launch quickly by restricting the scope:

Support PDFs only.

Focus on one persona initially (judgment summarization is recommended as it's easier to build than subjective risk evaluation).

Use basic email/password auth.

Rely on a third-party LLM API rather than building a custom model.

Future/Advanced Features (Post-MVP)
Document Tools: Keyword search, version comparison (diffing updated contracts), and multi-format exports.

UX & AI Enhancements: Hoverable jargon tooltips, regional language translation, and human-in-the-loop feedback to improve AI accuracy.

Workflow Operations: Role-based access control (RBAC), secure sharing links, background asynchronous processing with alerts, and user API quota tracking. write in .md
