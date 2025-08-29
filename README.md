# Naptha-AI-Agent
<img width="1428" height="853" alt="Screen Shot 2025-08-28 at 5 24 19 PM" src="https://github.com/user-attachments/assets/b38d5b70-0558-45e6-8f72-affbf61e2b88" />



Try it for yourself here: https://pritiks23.github.io/Naptha-AI-Agent/
**WILL NOT WORK IF YOU DON"T USE A GEMINI API KEY**


# Naptha AI Agent Demo

## Overview
This repository hosts a **web-based AI agent demo** tailored for Naptha AI use cases. The agent assists developers by explaining code, suggesting improvements, generating test cases, and summarizing pull requests. 
This Naptha AI Agent helps developers collaborate smarter — it can explain code, suggest improvements, generate tests, and summarize pull requests, all powered by Gemini.
 Users can interact with the agent directly through a **coding terminal-like interface** without running anything locally.

## Features
- **Agent Persona Customization:** Choose between *Code Mentor*, *Senior Dev Reviewer*, and *Junior QA Bot*. Responses adapt to the selected persona.
- **Terminal-Style Interface:** Dark theme with monospace font and structured input/output to emulate a real developer console.
- **API Key Input:** Users provide their own Gemini API key at runtime; keys are never stored.
- **Instant Responses:** The agent responds immediately, presenting clean, formatted text explanations.
- **Technical Flexibility:** Fully client-side implementation compatible with GitHub Pages.

## Example Queries
- Explain a function: `function add(a, b) { return a + b; }`
- Suggest unit tests for a code snippet.
- Refactor code to improve readability or efficiency.
- Summarize a pull request or code block.

## Deployment
- Fully client-side: no backend required.
- Compatible with GitHub Pages.
- Ensure API key is valid and has access to Gemini API endpoints.

## Technical Details
- Built with **HTML, CSS, and vanilla JavaScript**.
- Uses the **Gemini API** for generative code analysis.
- Clean and structured prompts ensure stable and readable AI responses.
- Monospace, terminal-like output enhances readability for technical users.
