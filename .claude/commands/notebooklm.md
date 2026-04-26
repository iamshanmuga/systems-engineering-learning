# NotebookLM Skill — Load Study Plan Reference Materials

Generate a `Week_XX_NotebookLM_Steps.md` checklist for loading the specified week's reference materials into NotebookLM (notebooklm.google.com).

## Usage

```
/notebooklm [week number or description]
```

Examples:
- `/notebooklm Week 03`
- `/notebooklm` (defaults to the current week based on context)

## Where source files now live (post-restructure)

This repo splits study content by purpose:

- **Chapter folders** under `01_CSEP-Certification/CHxx_<Chapter>/` (and CH03–CH08 subprocess sub-folders) own the durable content: `Topic_Summaries.md`, `Flashcards.md`, `References.md`, `Audio_Overview_Script.md`, mind maps, diagrams.
- **Week folders** under `01_CSEP-Certification/Study-Plan/CSEP_Study_Plan/Week_XX/` own only cadence files: `Week_XX_Study_Plan.md`, `Week_XX_Practice_Questions.md`, `Week_XX_Assessment_Answers.md`, `Week_XX_NotebookLM_Steps.md`, `Week_XX_Index.md`.

To find a week's NotebookLM source files, open the week's `Week_XX_Index.md`. It names the chapter folder(s) the week covers.

## Week → Chapter mapping (source of truth: top-level `Study-Plan/CSEP-Study-Plan.md`)

| Week | Chapter source folder(s) |
|------|--------------------------|
| 1 | `CH01_SE-Overview-and-Fundamentals/` |
| 2 | `CH02_Life-Cycle-Concepts/` |
| 3 | `CH03_Technical-Processes/Business-Mission-Analysis/` and `CH03_Technical-Processes/Stakeholder-Needs-and-Requirements/` |
| 4 | `CH03_Technical-Processes/System-Requirements-Definition/` and `CH03_Technical-Processes/Architecture-Definition/` |
| 5 | `CH03_Technical-Processes/Design-Definition/`, `Implementation/`, `Integration/` |
| 6 | `CH03_Technical-Processes/Verification/`, `Validation/`, `Transition/`, `Operation-Maintenance-Disposal/`, `System-Analysis/` |
| 7 | `CH04_Technical-Management-Processes/` (all subprocess folders) |
| 8 | `CH05_Agreement-Processes/` and `CH06_Organizational-Enabling-Processes/` (all subprocess folders) |
| 9 | `CH07_Specialty-Engineering/` (all subprocess folders) |
| 10 | `CH08_Crosscutting-Methods/` (all subprocess folders) |
| 11–12 | All chapters — full review |

If the mapping above and the top-level `Study-Plan/CSEP-Study-Plan.md` table disagree, the top-level file wins. Update this command to match.

## What this command does

1. **Resolves** the week to its chapter folder(s) using the mapping above.
2. **Identifies** the source files in those chapter folder(s):
   - `Topic_Summaries.md`
   - `Flashcards.md`
   - `References.md`
   - `Audio_Overview_Script.md` (if present)
   - Any chapter-specific PDF in `05_Resources/Books-and-References/` (e.g., SEH5 Chapter PDF) — note as optional upload
   - The week's own `Week_XX_Study_Plan.md` (still in the week folder; gives NotebookLM the daily structure and learning objectives)
3. **Creates** `Week_XX_NotebookLM_Steps.md` in `Study-Plan/CSEP_Study_Plan/Week_XX/` with:
   - A pre-requisite section listing every source file to upload, with the actual repo paths
   - Notebook naming convention: `CSEP Week XX — <Week Topic>`
   - Mind Map customisation prompt tailored to the week's topics
   - Audio Overview customisation prompt tailored to the week's topics
   - Video Overview customisation prompt tailored to the week's topics
   - A completion checklist

## Output

The command produces **only** the `Week_XX_NotebookLM_Steps.md` file. It does not generate or modify Topic Summaries, Flashcards, References, or any chapter content. Use the standard weekly content generation flow (see `Study-Plan/CSEP_Study_Plan/Weekly_Content_Checklist_and_Prompts.md`) to produce those.

## Where the NotebookLM-generated outputs go

After running NotebookLM and downloading the artifacts, file them in the chapter folder, not the week folder:

- Mind Map PNG → `CHxx_<Chapter>/Mind_Map.png`
- Audio Overview m4a → `CHxx_<Chapter>/Audio_Overview.m4a`
- Video Overview mp4 → `CHxx_<Chapter>/Video_Overview.mp4`

For weeks that span multiple subprocess folders (e.g. Week 3 covers BMA + SN&RD), file the artifacts in the primary subprocess folder named in the week's `Week_XX_Index.md`.
