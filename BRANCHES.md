
# Rootstock Ecosystem Directory - Branches and Contribution Guide

This document explains how contributors should use the different update branches in this repository to submit changes, improvements, and reports safely and efficiently.

---

## 1. Overview of Update Branches

| Branch Name                 | Purpose                                      | Files to Edit / Add                              |
|-----------------------------|----------------------------------------------|-------------------------------------------------|
| `updates/verified-tokens`   | Add or update verified tokens                | `verified-tokens.json`                           |
| `updates/trusted-dapps`     | Add or update trusted decentralized apps (DApps) | `trusted-dapps.md`                               |
| `updates/scam-alerts`       | Report scams or suspicious projects          | `scam-alerts.md`                                 |
| `updates/verification-guide`| Improve or update token verification instructions | `verification-guide.md`                         |
| `updates/contributing`      | Suggest improvements to contribution guidelines or docs | `CONTRIBUTING.md`, other documentation `.md` files |

---

## 2. General Contribution Rules

- Fork the repository before making any changes.
- Clone your fork locally.
- Checkout or create the appropriate update branch for your change.
- Follow file formatting guidelines for the branch you contribute to.
- Keep commit messages clear and descriptive.
- Open Pull Requests targeting the same update branch on the main repository.
- Wait for maintainers to review and merge your contribution.
- Keep changes focused and avoid mixing multiple topics in a single PR.

---

## 3. Branch-Specific Guidelines and Formats

### A. `updates/verified-tokens`

**Purpose:**  
Add new or update existing tokens in the verified tokens list.

**File:**  
`verified-tokens.json`

**Format:**  
The file contains a JSON array of token objects. Each token should follow this structure:

```json
{
  "name": "Token Name",
  "symbol": "SYM",
  "contractAddress": "0x123456789abcdef...",
  "website": "https://example.com",
  "audit": "https://auditlink.com",
  "status": "Verified"
}
````

**Tips:**

* Validate your JSON using a tool like [JSONLint](https://jsonlint.com) before submitting.
* Provide official websites and audit URLs when available.
* Only add tokens that have been properly verified.

---

### B. `updates/trusted-dapps`

**Purpose:**
Add or update the list of trusted, reputable decentralized applications (DApps).

**File:**
`trusted-dapps.md`

**Format:**
Use a Markdown table format with the following columns:

| DApp Name  | Description                        | Website                                        |
| ---------- | ---------------------------------- | ---------------------------------------------- |
| ExampleApp | Brief description of the DApp here | [https://exampleapp.io](https://exampleapp.io) |

**Tips:**

* Descriptions should be factual and concise.
* Verify that the DApp is active and trusted.
* Use official URLs only.

---

### C. `updates/scam-alerts`

**Purpose:**
Report scams or suspicious projects to warn the community.

**File:**
`scam-alerts.md`

**Format:**
Use Markdown headings and structured entries:

```markdown
### Project Name

- **Contract Address:** 0x123456789abcdef...
- **Description:** Explain why this project is suspicious or a scam.
- **Reported by:** @username
- **Date:** YYYY-MM-DD
- **Evidence / Links:** https://community-warning-link.com
```

**Tips:**

* Provide clear, verifiable evidence.
* Avoid speculation; only report confirmed or strongly suspected scams.
* Maintain a neutral, factual tone.

---

### D. `updates/verification-guide`

**Purpose:**
Enhance or clarify the walkthrough for verifying tokens.

**File:**
`verification-guide.md`

**Format:**
Markdown document with clear step-by-step instructions, optionally including screenshots or links.

**Tips:**

* Use simple, easy-to-follow language.
* Keep the guide updated with the latest tools and explorer changes.
* Include relevant URLs and images.

---

### E. `updates/contributing`

**Purpose:**
Improve contribution guidelines and documentation.

**Files:**
`CONTRIBUTING.md` and other `.md` documentation files.

**Tips:**

* Follow Markdown best practices.
* Keep changes concise and practical.
* Reference existing guidelines where appropriate.

---

## 4. Example Contributor Workflow

1. **Fork** this repository on GitHub.
2. **Clone** your fork locally:

```bash
git clone https://github.com/YOUR_USERNAME/Rootstock-Ecosystem-Directory.git
cd Rootstock-Ecosystem-Directory
```

3. **Checkout** the update branch matching your change, for example:

```bash
git checkout updates/verified-tokens
```

4. **Make your edits** to the relevant file(s).
5. **Validate** your changes, especially JSON files.
6. **Commit** your changes with a descriptive message:

```bash
git add verified-tokens.json
git commit -m "Add ExampleToken to verified tokens list"
```

7. **Push** your changes:

```bash
git push origin updates/verified-tokens
```

8. **Open a Pull Request** from your fork’s update branch to the main repository’s corresponding branch.
9. **Wait for review** and respond to any feedback.

---

## 5. Additional Notes

* Submit separate Pull Requests for different update branches if contributing multiple types of changes.
* Engage with maintainers via issues or community channels if unsure where to contribute.
* Keep all contributions respectful, fact-based, and in line with repository goals.

---

Thank you for helping maintain a trustworthy and up-to-date Rootstock Ecosystem Directory
