# My Skills Collection

**A curated collection of developer skills and tools organized by business workflow. From planning and design to development and operations, this repository provides a comprehensive toolkit to accelerate every stage of your digital product lifecycle. Compatible with modern AI-powered IDEs (Trae, Cursor, VS Code, etc.).**

## Repository Structure

This repository follows a **Process-Based Classification** system to help you find the right tool for your current workflow stage.

```text
├── tomf-skills-repo/
│   ├── planning/           # 1. Planning & Definition (0 -> 1)
│   │   ├── requirements/       # Requirements gathering (PRD, User Stories)
│   │   ├── research/           # Market & User Research
│   │   └── strategy/           # Product Strategy & Roadmaps
│   │
│   ├── design/             # 2. Design & Prototyping (Visual)
│   │   ├── ui-ux/              # UI/UX Design Systems
│   │   ├── visual-assets/      # Icons, Illustrations, Graphics
│   │   └── prototyping/        # Wireframing & Interaction
│   │
│   ├── development/        # 3. Development & Implementation (Build)
│   │   ├── frontend/           # Web/Mobile Frontend
│   │   ├── backend/            # Server-side Logic & APIs
│   │   ├── architecture/       # System Design & Patterns
│   │   └── database/           # Schema Design & SQL
│   │
│   ├── quality/            # 4. Quality & Testing (Assurance)
│   │   ├── code-review/        # Code Analysis & Best Practices
│   │   ├── testing/            # Unit/Integration/E2E Testing
│   │   └── security/           # Vulnerability Scanning & Audits
│   │
│   ├── operations/         # 5. Operations & Data (Growth)
│   │   ├── data-analysis/      # Data Cleaning & Visualization
│   │   ├── marketing-seo/      # Growth Hacking & SEO
│   │   └── deployment/         # CI/CD & DevOps
│   │
│   └── office-tools/       # 6. Productivity & Admin (Support)
│       ├── document-processing/# Format Conversion (PDF/Word/MD)
│       ├── communication/      # Meeting Notes & Emails
│       └── productivity/       # Time Management & Automation
```

## Skills Index

### 1. Planning
> Tools for product managers, founders, and creators to define ideas.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **Requirements** | PRD Writer, User Story Gen | `tomf-skills-repo/planning/requirements/` |
| **Strategy** | Business Plan, Roadmap Gen | `tomf-skills-repo/planning/strategy/` |
| **Research** | User Persona, Competitor Analysis | `tomf-skills-repo/planning/research/` |

### 2. Design
> Tools for UI/UX designers and creative directors.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **UI/UX** | **UI/UX Pro Max** (Tailwind/React) | `tomf-skills-repo/design/ui-ux/ui-ux-pro-max` |
| **Prototyping** | Wireframe Description | `tomf-skills-repo/design/prototyping/` |
| **Visual Assets** | Icon Generator, Color Palette | `tomf-skills-repo/design/visual-assets/` |

### 3. Development
> Tools for frontend, backend, and full-stack engineers.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **Frontend** | React/Vue Component Gen | `tomf-skills-repo/development/frontend/` |
| **Backend** | API Logic, Auth Flows | `tomf-skills-repo/development/backend/` |
| **Architecture** | API Designer, System Design | `tomf-skills-repo/development/architecture/` |

### 4. Quality
> Tools for QA engineers and code reviewers.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **Code Review** | Clean Code Checker | `tomf-skills-repo/quality/code-review/` |
| **Testing** | Jest/PyTest Generator | `tomf-skills-repo/quality/testing/` |
| **Security** | Dependency Audit | `tomf-skills-repo/quality/security/` |

### 5. Operations
> Tools for data analysts, marketers, and growth hackers.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **Data Analysis** | Excel/SQL Wizard | `tomf-skills-repo/operations/data-analysis/` |
| **Marketing/SEO** | SEO Optimizer, Content Writer | `tomf-skills-repo/operations/marketing-seo/` |
| **Deployment** | Docker/K8s Config | `tomf-skills-repo/operations/deployment/` |

### 6. Office Tools
> Productivity boosters for everyone.

| Subcategory | Skill Examples | Path |
|-------------|----------------|------|
| **Docs** | PDF to Markdown, OCR | `tomf-skills-repo/office-tools/document-processing/` |
| **Comm** | Meeting Minutes, Email Helper | `tomf-skills-repo/office-tools/communication/` |

---

## How to Use

### Option 1: Clone Full Repository (Recommended)
Clone this repository into your IDE's global skills directory. This makes all skills available across all your projects.

**For Trae:**
```bash
mkdir -p .trae/skills
git clone https://github.com/your-username/my-skills.git .trae/skills/my-collection
```

**For Other IDEs:**
Check your IDE's documentation for the skills directory location (e.g., `.cursor/skills`, `.vscode/skills`).

### Option 2: Selective Install
If you only need a specific skill (e.g., just the UI design tool), you can copy that specific folder to your project's local skills directory.

## Contributing

Contributions are welcome! Please follow these steps to add new skills:

1.  **Fork** the repository.
2.  **Create** a new branch for your feature.
3.  **Place** your skill folder in the appropriate category path:
    *   `tomf-skills-repo/<category>/<subcategory>/<your-skill-name>/`
4.  **Ensure** your skill folder contains a valid `SKILL.md`.
5.  **Submit** a Pull Request.

---
License: MIT
