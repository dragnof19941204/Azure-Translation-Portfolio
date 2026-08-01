# Translation Workflow

## Overview

This document describes the workflow used to produce Japanese technical translations in this repository.

The goal of the workflow is to ensure technical accuracy, terminology consistency, and natural Japanese readability while using AI as a productivity tool rather than a replacement for human review.

---

## Workflow

### Step 1 — Review the Source Material

Read the Microsoft Learn documentation to understand:

- Technical concepts
- Learning objectives
- Azure service behavior
- Relationships between Azure resources

At this stage, the focus is on understanding the technical content rather than translating it.

---

### Step 2 — Create an AI-assisted Draft

Generate an initial Japanese translation using AI.

The AI draft is treated as a starting point only.

---

### Step 3 — Verify Microsoft Terminology

Review technical terms against Microsoft's official terminology.

Examples include:

- Log Analytics workspace
- Recovery Services vault
- Azure Monitor
- Resource Group
- Action Group

Official terminology is preserved whenever possible.

---

### Step 4 — Verify Azure Portal UI

Confirm that Azure Portal menu names and UI labels match the Japanese Azure Portal.

Examples include:

- Monitoring
- Alerts
- Access Control (IAM)
- Review + Create
- Resource Health

---

### Step 5 — Technical Review

Review the translation for:

- Technical correctness
- Logical consistency
- Missing information
- Incorrect interpretation

Azure operational knowledge is used during this review.

---

### Step 6 — Improve Japanese Readability

Edit the translation to improve:

- Sentence flow
- Grammar
- Consistency
- Readability

The objective is to produce documentation that is natural for Japanese engineers.

---

### Step 7 — Quality Assurance

Perform a final review covering:

- Formatting
- Terminology
- Markdown
- Tables
- Headings
- Spelling

---

### Step 8 — Publish

Store the reviewed translation in GitHub using a consistent repository structure.

Each project contains:

- README
- Translation documents
- Glossary
- Lessons Learned
- Quality Checklist

---

## Principles

This repository emphasizes:

- Technical accuracy
- Consistent terminology
- Transparent review process
- Continuous improvement
