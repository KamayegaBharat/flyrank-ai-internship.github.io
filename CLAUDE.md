# Claude Code & AI Coding Assistant Instructions

This file defines the operating rules, guardrails, and conventions for Claude Code, Cursor, and any other AI coding assistant operating within this repository.

---

## 1. Repository Purpose & Scope

- This repository is strictly for the **FlyRank AI Frontend Internship FE-01 Setup** assignment.
- The current scope is **repository configuration and developer environment setup only**.
- **CRITICAL RULE:** Do not generate application code, web pages, components, mock data, or UI frameworks (e.g., React, Vite, Next.js, or HTML/CSS apps) unless explicitly commanded by the user in writing.

---

## 2. Inspect Before Editing

- Always inspect existing workspace files and directories before proposing or making changes.
- Never assume the presence or absence of a file, branch, or commit without verifying first.
- Clearly distinguish between local workspace state and remote GitHub state.
- Before cleanup or removal, verify that directories are empty or files are obsolete, and obtain explicit user approval for destructive changes.

---

## 3. Documentation & Configuration Conventions

- Keep documentation accurate, minimal, and directly aligned with the assignment criteria.
- Do not invent hypothetical features, tech stacks, or deployment pipelines.
- Preserve existing repository configurations, licenses, and author information.

---

## 4. Git & Commit Safety Rules

- **Review diffs first:** Show and review the exact `git diff` with the user before committing or staging changes.
- **Conventional Commits:** All commit messages must follow the [Conventional Commits specification](https://www.conventionalcommits.org/).
  - Format: `type(optional-scope): description`
  - Permitted types: `chore`, `docs`, `feat`, `fix`, `style`, `refactor`, and `test`.
  - **Real history only:** Every commit must represent a real, tangible change. Never create empty or duplicate commits solely to increase the commit count.
- **Never force-push:** Do not overwrite, rewrite, rebase, or force-push over public or shared history.
- **Safe remote integration:** Inspect remote branches and repository status before committing to avoid diverging from or replacing existing remote work.

---

## 5. Security & Secret Protection

- **Zero secret exposure:** Never commit, log, or embed API keys, OAuth tokens, personal access tokens (PATs), passwords, credentials, or private keys.
- Ensure sensitive artifacts, local caches, and credential files are appropriately covered by `.gitignore`.

---

## 6. Truthful Reporting & Verification

- Report test results, execution outputs, and tool operations accurately and honestly.
- Never fabricate command outputs, test passes, Git histories, or deployment statuses.
- Do not claim external tools (e.g., Claude Code or Cursor CLI) are configured or installed unless their presence has been verified in the environment.
