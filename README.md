---
title: LLM Password Manager Experiment
emoji: 🔐
colorFrom: red
colorTo: orange
sdk: gradio
sdk_version: 4.44.0
app_file: app.py
pinned: false
---

# 🔐 LLM Password Manager (Experimental)

**⚠️ Educational Project - Not for Production Use**

This is an experimental demonstration of using an LLM as a password manager. It showcases:

- Authentication before password retrieval
- Security rules in system prompts
- Prompt injection resistance testing
- Gemini API integration with Gradio

## Features

- Master password authentication (`SecurePass123!`)
- Secure credential storage in system prompt
- Multiple test scenarios for security evaluation

## How It Works

1. The system prompt contains hardcoded credentials and security rules
2. Users must authenticate with the master password
3. LLM enforces security protocols before revealing passwords
4. Demonstrates both capabilities and limitations of LLM-based security

## Testing

Try these scenarios:
- Request passwords without authentication
- Authenticate with master password
- Test prompt injection attacks
- Evaluate security response consistency

## Configuration

Set your `GEMINI_API_KEY` in the repository secrets.

---

**Disclaimer:** This is purely experimental. Never use LLMs for real password management!