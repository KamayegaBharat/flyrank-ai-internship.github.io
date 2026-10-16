# FlyRank AI — Frontend Internship (FE-01)

**Assignment:** Environment & Repository Setup

This repository contains the setup documentation and configuration for the **FlyRank AI Frontend Internship — FE-01 assignment**.

The goal of this assignment is to establish a clean development workspace, document repository conventions, prepare AI coding assistant instructions, and demonstrate a basic Git workflow.

> **Scope:** This stage focuses on environment and repository setup. It does not require building a website or application.

## Repository Structure

```text
.
├── .gitignore    # Files and directories Git should ignore
├── LICENSE       # MIT License
├── README.md     # Project overview and setup instructions
└── CLAUDE.md     # AI coding assistant guidelines
```

## Prerequisites

Before working with this repository, ensure you have:

- **Git** installed for version control.
- A **GitHub account** to access and manage the repository.
- **Claude Code or Cursor** for the AI-assisted development task and screenshot deliverable.
- A terminal or development environment where you can run Git commands.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/KamayegaBharat/flyrank-ai-internship.github.io.git
cd flyrank-ai-internship.github.io
```

### 2. Verify the repository

Check the current working-tree status and configured remote:

```bash
git status
git remote -v
```

Review the existing commit history:

```bash
git log --oneline
```

## Git and Commit Conventions

This repository follows the [Conventional Commits specification](https://www.conventionalcommits.org/).

Use this format for commit messages:

```text
<type>: <short description>
```

Common types include:

| Type | Purpose |
|---|---|
| `chore` | Repository maintenance and configuration |
| `docs` | Documentation changes |
| `feat` | New functionality |
| `fix` | Bug fixes |
| `style` | Formatting changes that do not affect functionality |
| `refactor` | Code restructuring without changing intended behavior |
| `test` | Adding or updating tests |

Examples:

```text
chore: initialize repository configuration
docs: add project README
docs: add Claude Code project instructions
```

Each commit should represent a real, meaningful change. Review changes before committing, and preserve existing repository history.

## AI Coding Assistant Guidelines

The `CLAUDE.md` file defines instructions for AI coding assistants working in this repository.

These guidelines emphasize:

- Inspecting files before making changes.
- Staying within the assignment scope.
- Reviewing diffs before committing.
- Following Conventional Commits.
- Protecting API keys, credentials, and other secrets.
- Reporting actions and verification results accurately.

## FE-01 Deliverables

Use this checklist to track assignment progress.

- [x] GitHub repository created.
- [x] MIT `LICENSE` file present.
- [x] `.gitignore` file present.
- [x] `README.md` created.
- [x] `CLAUDE.md` created.
- [x] At least three meaningful Conventional Commits verified in the Git history.
- [x] Genuine screenshot showing Claude Code or Cursor completing a task.

The final two items should only be marked complete after the commit history and screenshot have been verified.

## License

This repository includes an MIT License. See the [`LICENSE`](LICENSE) file for the full license text.
