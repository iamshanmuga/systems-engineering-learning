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

## Git workflow (always follow)

Every time work in this repo touches git, follow this loop:

1. **Branch off `main`.** Never commit directly to `main`. Use a descriptive branch name: `claude/<short-description>` for Claude-driven work, `content/<topic>` for content edits, `fix/<thing>` for fixes.
2. **Commit on the branch.** Logical, scoped commits with clear messages. Show diffs / summarise before committing if the change is large or destructive.
3. **Push the branch and open a PR.** Use `gh pr create` with a description that summarises the change, the reasoning, and any follow-ups. The PR is Shanmuga's review surface.
4. **Wait for Shanmuga to merge the PR.** Do not merge or push to `main` directly.
5. **After the PR is merged, clean up.** Verify the branch is fully merged into `main` (locally and on `origin`), then delete it both places: `git branch -d <branch>` and `git push origin --delete <branch>`. No stale branches sitting around.

This applies to every git-touching task in this repo, regardless of size.

## Content placement convention (CSEP folder)

Within `01_CSEP-Certification/`, content is split by *purpose*:

- **Chapter folders own durable knowledge.** `CH0X_<Chapter>/` (and the subprocess sub-folders under CH03–CH08) hold topic summaries, flashcards, mind maps, illustration diagrams, audio overview scripts, references — anything that's tied to a specific INCOSE SE Handbook chapter or ISO 15288 process. Files in chapter folders use plain names (`Topic_Summaries.md`, `Flashcards.md`, `References.md`, `Diagrams/<name>.svg`), no `Week_XX_` prefix.
- **Week folders own study cadence.** `Study-Plan/CSEP_Study_Plan/Week_XX/` holds *only* the week-shaped artifacts: `Week_XX_Study_Plan.md` (daily schedule + learning objectives), `Week_XX_Practice_Questions.md`, `Week_XX_Assessment_Answers.md`, `Week_XX_NotebookLM_Steps.md`, and an optional `Week_XX_Index.md` linking out to that week's chapter content.
- **`Study-Plan/CSEP-Study-Plan.md` (top-level)** is the master schedule + week→chapter mapping. Source of truth for which chapter a given week covers.
- **`Practice-Exams-and-Quizzes/`** at the CSEP root is reserved for mixed-chapter mock exams. Per-week practice questions stay in their week folder.
- When generating new content, route by topic: a Week 4 topic summary on Architecture Definition lands in `CH03_Technical-Processes/Architecture-Definition/Topic_Summaries.md`, not in `Week_04/`.

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
