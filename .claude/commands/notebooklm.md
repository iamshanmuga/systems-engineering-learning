# NotebookLM Skill — Load Study Plan Reference Materials

Generate a `week_xx_notebooklm_steps.md` checklist for loading the specified week's reference materials into NotebookLM (notebooklm.google.com).

## Usage

```
/notebooklm [week number or description]
```

Examples:
- `/notebooklm Week 03`
- `/notebooklm` (defaults to the current week based on context)

## Where source files now live (post-restructure)

This repo splits study content by purpose:

- **Chapter folders** under `01_CSEP-Certification/CHxx_<Chapter>/` (and CH03–CH08 subprocess sub-folders) own the durable content: `topic_summaries.md`, `flashcards.md`, `references.md`, `audio_overview_script.md`, mind maps, diagrams.
- **Week folders** under `01_CSEP-Certification/Study-Plan/CSEP_Study_Plan/Week_XX/` own only cadence files: `week_xx_study_plan.md`, `week_xx_practice_questions.md`, `week_xx_assessment_answers.md`, `week_xx_notebooklm_steps.md`, `week_xx_index.md`.

To find a week's NotebookLM source files, open the week's `week_xx_index.md`. It names the chapter folder(s) the week covers.

## Week → Chapter mapping (source of truth: top-level `Study-Plan/csep-study-plan.md`)

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

If the mapping above and the top-level `Study-Plan/csep-study-plan.md` table disagree, the top-level file wins. Update this command to match.

## What this command does

1. **Resolves** the week to its chapter folder(s) using the mapping above.
2. **Identifies** the source files in those chapter folder(s):
   - `topic_summaries.md`
   - `flashcards.md`
   - `references.md`
   - `audio_overview_script.md` (if present)
   - Any chapter-specific PDF in `05_Resources/Books-and-References/` (e.g., SEH5 Chapter PDF) — note as optional upload
   - The week's own `week_xx_study_plan.md` (still in the week folder; gives NotebookLM the daily structure and learning objectives)
3. **Creates** `week_xx_notebooklm_steps.md` in `Study-Plan/CSEP_Study_Plan/Week_XX/` with:
   - A pre-requisite section listing every source file to upload, with the actual repo paths
   - Notebook naming convention: `CSEP Week XX — <Week Topic>`
   - Mind Map customisation prompt tailored to the week's topics
   - Audio Overview customisation prompt tailored to the week's topics
   - Video Overview customisation prompt tailored to the week's topics
   - A completion checklist

## Output

The command produces **only** the `week_xx_notebooklm_steps.md` file. It does not generate or modify Topic Summaries, Flashcards, References, or any chapter content. Use the standard weekly content generation flow (see `Study-Plan/CSEP_Study_Plan/weekly_content_checklist_and_prompts.md`) to produce those.

## Where the NotebookLM-generated outputs go

After running NotebookLM and downloading the artifacts, file them in the chapter folder, not the week folder:

- Mind Map PNG → `CHxx_<Chapter>/mind_map.png`
- Audio Overview m4a → `CHxx_<Chapter>/audio_overview.m4a`
- Video Overview mp4 → `CHxx_<Chapter>/video_overview.mp4`

For weeks that span multiple subprocess folders (e.g. Week 3 covers BMA + SN&RD), file the artifacts in the primary subprocess folder named in the week's `week_xx_index.md`.
