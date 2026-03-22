# Contributing to PII-Safe

Thank you for your interest in contributing to PII-Safe!
This guide will help you get started quickly.

## Prerequisites

- Python 3.9 or higher
- Git
- Docker (for running the full service locally)

## Getting Started

### 1. Fork the Repository
Click the Fork button at the top right of the page.

### 2. Clone Your Fork
git clone https://github.com/YOUR-USERNAME/PII-Safe.git
cd PII-Safe

### 3. Create a Branch
git checkout -b feature/your-feature-name

Branch prefixes:
- feature/ for new features
- fix/ for bug fixes  
- docs/ for documentation changes

### 4. Make Your Changes
Write clean, readable code. Add tests for new features.

### 5. Commit Your Changes
git commit -m "feat: short description of change"

### 6. Push and Open a Pull Request
git push origin feature/your-feature-name

Open a PR against the main branch. Always link to an
existing issue using Closes #ISSUE-NUMBER in your
PR description.

## PR Guidelines

- One feature or fix per PR
- Describe what your PR does and why
- Respond to review comments within 48 hours
- Do not open a PR without a linked issue

## Reporting Bugs

Open an issue at https://github.com/c2siorg/PII-Safe/issues

Include steps to reproduce, expected vs actual behavior,
and your Python version.

## Questions

Reach out via GitHub issues or the C2SI community Slack.
```

---

### Step 3 — Scroll Down to Commit
- Select **"Create a new branch"**
- Name it: `docs/add-contributing-guide`
- Click **"Propose new file"**

---

### Step 4 — PR Title and Description
**Title:**
```
docs: add CONTRIBUTING.md to guide new contributors
```

**Description:**
```
Closes #13

## Summary
Adds CONTRIBUTING.md to help GSoC 2026 applicants 
and new contributors onboard quickly.

## Changes
- Added prerequisites and setup instructions
- Added branch naming conventions
- Added PR guidelines and commit message format
- Added bug reporting guide

## Checklist
- [x] Documentation only change
- [x] Improves contributor onboarding experience
