## Copilot Spaces — Setup & Guide

This guide helps you use GitHub Copilot Spaces to collect, maintain, and scale institutional knowledge inside a repo.

Goals
- Provide a trustworthy single source of truth for project processes, onboarding, and playbooks
- Make it easy for contributors to add or update knowledge
- Use Spaces to organize content, discussions, and AI-assisted contributions

Quick start
1. Create a new Space in your organization or repository for "Institutional Knowledge".
2. Organize content by categories (Onboarding, How-tos, Playbooks, Runbooks, Meeting notes).
3. Add a CONTRIBUTING.md and templates so people know how to submit updates.

Templates
- Use short, scoped templates for common content: "How-to", "Runbook", "Onboarding step".
- Keep entries focused (250-800 words) and link to related docs and issues.

Maintaining quality
- Assign maintainers or owners for each category.
- Add a review checklist: accuracy, links, steps reproducible, security/privacy check.

Examples
- Onboarding: checklist for new hires with links to accounts, tooling, and first-week tasks.
- Runbook: steps to troubleshoot and remediate a common incident with exact commands.

Revision process
1. Open an issue to propose major changes.
2. Small edits can be done via PR with the `docs/` path and a short changelog entry.

Automation
- Use GitHub Actions to check for broken links and run spellcheck on `docs/` files.

Further reading
- GitHub Docs: Copilot for Business and Spaces (link your internal docs)
