Sure! Here's your full CONTRIBUTING.md content in proper .md format:


---

# Contributing to the Rootstock Ecosystem Directory

Welcome! This guide explains how you can contribute to the project, whether you're reporting scams, adding verified tokens, or improving documentation.

---

## Getting Started

1. Fork this repository to your GitHub account.
2. Clone your fork to your local machine:

git clone https://github.com/yourusername/Rootstock-Ecosystem-Directory.git cd Rootstock-Ecosystem-Directory

3. Create a new branch for your contribution:

git checkout -b your-branch-name

---

## What You Can Contribute

### 1. Add a Verified Token

- Edit `verified-tokens.json`.
- Use this format:
```json
{
 "name": "TokenName",
 "symbol": "TKN",
 "contractAddress": "0x1234567890abcdef...",
 "website": "https://example.com",
 "audit": "https://auditlink.com",
 "status": "Verified"
}

Save the file.


2. Report a Scam or Suspicious Project

Open scam-alerts.md.

Add the token/project name, contract address, evidence links, and short description.


3. Improve Documentation

Help improve README.md, verification-guide.md, or other markdown files.


4. Translate Content

Create a file like README.es.md for Spanish, etc.

Translate existing guides.



---

Submitting a Pull Request

1. Stage and commit your changes:

git add .
git commit -m "Describe your update"


2. Push to your fork:

git push origin your-branch-name


3. On GitHub, open a Pull Request from your branch to the main branch.




---

Guidelines

Use valid JSON syntax.

Write clear, factual descriptions.

Follow the existing format for all files.

Only submit verified or well-supported information.



---

Useful Resources

RSK Explorer

JSON Validator

Rootstock Discord

Rootstock Telegram



---

Thank you for helping make Rootstock safer and more transparent for everyone.
