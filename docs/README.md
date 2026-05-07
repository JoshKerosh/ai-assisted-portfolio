# Documentation Guide

This directory contains all project-related documentation for the AI-Assisted Portfolio project.

The documentation follows a docs-as-code approach and is version-controlled together with the source code to ensure traceability, maintainability, and transparency throughout the development lifecycle.

---

# Documentation Principles

The project documentation is designed to:

- document architectural and technical decisions,
- track Scrum planning and sprint progress,
- record AI-assisted engineering workflows,
- maintain OpenSpec-driven development practices,
- support onboarding and future scalability,
- and preserve the full build process as part of the portfolio case study itself.

---

# Documentation Structure

## `/ai`

AI-assisted engineering documentation.

Contains:
- AI usage policy,
- prompt logs,
- review process,
- and reusable AI workflows/skills.

This project treats AI as an engineering assistant rather than an autonomous system.

---

## `/architecture`

Technical architecture and engineering structure.

Contains:
- system overview,
- repository organization,
- frontend architecture,
- content strategy,
- and infrastructure decisions.

---

## `/decisions`

Architecture Decision Records (ADRs).

Used to document important technical and product decisions.

Examples:
- static content strategy,
- GitHub Projects usage,
- stack selection,
- deployment strategy.

---

## `/deployment`

Deployment and CI/CD documentation.

Contains:
- GitHub Actions configuration,
- Vercel deployment notes,
- environment setup,
- and release workflows.

---

## `/design`

Design and branding exploration.

Contains:
- design direction,
- moodboards,
- visual references,
- branding notes,
- and UX/UI experimentation.

---

## `/process`

Engineering workflow documentation.

Contains:
- Definition of Done,
- Git workflow,
- branch strategy,
- commit conventions,
- deployment process,
- and operational standards.

---

## `/product`

Product-related documentation.

Contains:
- product vision,
- roadmap,
- personas,
- scope definition,
- and strategic planning.

---

## `/scrum`

Scrum and project management documentation.

Contains:
- backlog,
- sprint planning,
- sprint outcomes,
- and workflow templates.

---

## `/testing`

Testing strategy documentation.

Contains:
- testing standards,
- integration testing strategy,
- E2E testing approach,
- and quality assurance practices.

---

# Documentation Standards

## General Rules

- Documentation should be concise and professional.
- Major decisions must be recorded through ADRs.
- AI-assisted work should be documented when relevant.
- Sprint outcomes should be summarized after completion.
- Documentation should evolve together with the implementation.

---

# Traceability

The project aims to maintain traceability between:

```txt
OpenSpec Change
→ GitHub Issue
→ Branch
→ Pull Request
→ Commit
→ Documentation Update