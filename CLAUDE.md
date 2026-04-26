# Systems Engineering Learning Repository

## What this is

A structured knowledge base for Systems Engineering study, INCOSE CSEP certification preparation, reusable SE templates, and Systems Engineering project work. Tracked in git, pushed to https://github.com/iamshanmuga/systems-engineering-learning.

Currently active workstream: CSEP exam prep (`01_CSEP-Certification/`). No exam date scheduled.

## How Claude should work in this project

This repo has its own internal structure (the `01_-05_` numbered folders below). It pre-dates the workspace project template and was not built from it. Don't reorganize it into the template's `docs/src/tests/` shape — the structure is intentional and tied to the INCOSE SE Handbook v5 chapter layout.

Other rules specific to this project:

- The repo is git-tracked with a GitHub remote. Adding new files is fine. Modifying existing tracked files: flag what's changing and confirm before editing. Never push without explicit go-ahead (workspace `CLAUDE.md` rule already says this; restating because this is the only currently-pushable repo in the workspace).
- `memory/` is gitignored. Project session notes go there freely without polluting the repo.
- `CLAUDE.md` (this file) and `README.md` are the two Claude-readable orientation files. Keep them in sync with each other when structural changes happen.
- The `03_Templates/` folder contains SE document templates (Markdown, DOCX, XLSX, Draw.io). When Shanmuga asks for a new SE artifact, check there first before generating from scratch.

## Where things live

- `01_CSEP-Certification/` — CSEP exam prep aligned to INCOSE SE Handbook v5. Contains chapter notes (`CH01_-CH08_`), `Study-Plan/`, `Flashcards/`, `Practice-Exams-and-Quizzes/`, `References-and-Standards/`.
- `02_SE-Domains/` — deep-dive notes on SE disciplines: Requirements Engineering, MBSE, Risk-and-Safety, Program-and-Project-Management.
- `03_Templates/` — reusable SE document templates in `Markdown/`, `Word-DOCX/`, `Excel-XLSX/`, `Diagrams/` (Draw.io).
- `04_Projects/` — actual SE project work. Sub-folders: `Real-World-Projects/`, `Study-Projects/`, `_project-template/` (this repo's own internal project template, separate from the workspace template).
- `05_Resources/` — external standards, books, tools, cheat sheets, course notes.
- `README.md` — human-facing repo overview.
- `memory/log.md` — append-only dated session log for this project.
- `memory/decisions.md` — significant decisions with rationale.
- `memory/glossary.md` — project-specific shorthand and terms.

## Current focus

CSEP exam prep. Status tracked in workspace `About Me/memory.md`.
