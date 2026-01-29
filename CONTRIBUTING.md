# Contributing to My Skills Collection

Thank you for your interest in contributing! This repository aims to build a high-quality, process-oriented collection of skills for modern AI IDEs.

## How to Add a New Skill

### 1. Identify the Correct Path
We use a **Process-Based** directory structure with specific subcategories. Please find the most appropriate location for your skill:

*   **tomf-skills-repo/planning/**
    *   `requirements/` (PRDs, User Stories)
    *   `research/` (User Research, Market Analysis)
    *   `strategy/` (Business Plans, Roadmaps)
*   **tomf-skills-repo/design/**
    *   `ui-ux/` (Design Systems, Component Specs)
    *   `visual-assets/` (Icons, Color Palettes)
    *   `prototyping/` (Wireframes, Interaction Flows)
*   **tomf-skills-repo/development/**
    *   `frontend/` (React, Vue, CSS)
    *   `backend/` (Node, Python, API Logic)
    *   `architecture/` (System Design, Patterns)
    *   `database/` (SQL, Schema Design)
*   **tomf-skills-repo/quality/**
    *   `code-review/` (Linters, Best Practices)
    *   `testing/` (Unit, E2E Tests)
    *   `security/` (Audits, Vulnerability Checks)
*   **tomf-skills-repo/operations/**
    *   `data-analysis/` (SQL, Excel, Visualization)
    *   `marketing-seo/` (Content, SEO)
    *   `deployment/` (Docker, CI/CD)
*   **tomf-skills-repo/office-tools/**
    *   `document-processing/` (Converters, OCR)
    *   `communication/` (Emails, Meeting Notes)
    *   `productivity/` (Time Management, Automation)

### 2. Create the Skill Directory
Create a new folder for your skill inside the chosen subcategory. Use **kebab-case** for the folder name.

**Example Path:**
`tomf-skills-repo/design/ui-ux/modern-glassmorphism/`

### 3. Add Required Files
Your skill directory **MUST** contain a `SKILL.md` file.

**File Structure:**
```text
tomf-skills-repo/category/subcategory/your-skill-name/
├── SKILL.md          (REQUIRED: The prompt definition)
├── README.md         (RECOMMENDED: Documentation for humans)
└── scripts/          (OPTIONAL: Helper scripts if needed)
```

### 4. Format Your SKILL.md
The `SKILL.md` file defines how the AI behaves. It must start with YAML frontmatter.

```markdown
---
name: "your-skill-name"
description: "A short, clear description of what this skill does. (Max 200 chars)"
---

# Skill Name

[Detailed instructions, prompt templates, and context for the AI agent go here...]
```

### 5. Submit Your Contribution
1.  **Fork** the repository.
2.  **Create a branch** (`git checkout -b add-new-skill`).
3.  **Commit** your changes.
4.  **Push** to your fork and submit a **Pull Request**.

## Testing Guidelines
Before submitting, please test your skill in your preferred IDE (Trae, Cursor, VS Code, etc.):
1.  Place your skill folder in your IDE's local skills directory (e.g., `.trae/skills/`).
2.  Trigger the skill using natural language or the specific skill name.
3.  Verify that the output is accurate and helpful.

---
**Happy Hacking!**
