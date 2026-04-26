# NotebookLM Skill — Load Study Plan Reference Materials

Generate a `Week_XX_NotebookLM_Steps.md` checklist for loading the specified week's reference materials into NotebookLM (notebooklm.google.com), following the same structure as `Week_02_NotebookLM_Steps.md`.

## Usage

```
/notebooklm [week number or description]
```

Examples:
- `/notebooklm Week 03`
- `/notebooklm` (defaults to the current week based on context)

## What This Skill Does

1. **Identifies** all reference material files for the specified week under `01_CSEP-Certification/Study-Plan/CSEP_Study_Plan/Week_XX/`
2. **Creates** `Week_XX_NotebookLM_Steps.md` in that week's folder with:
   - A pre-requisite section listing every source file to upload to NotebookLM
   - Notebook naming convention: `CSEP Week XX — <Week Topic>`
   - Mind Map customisation prompt tailored to the week's topics
   - Audio Overview customisation prompt tailored to the week's topics
   - Video Overview customisation prompt tailored to the week's topics
   - A completion checklist

## Reference Files to Include (per week)

Always include these files as NotebookLM sources:
- `Week_XX_Study_Plan.md`
- `Week_XX_Topic_Summaries.md`
- `Week_XX_Flashcards.md`
- `Week_XX_References.md`
- Any relevant PDF chapters if available (e.g., SEH5 Chapter PDF)

## Output

The skill produces **only** the `Week_XX_NotebookLM_Steps.md` file — it does not generate any other content (flashcards, summaries, etc.) unless separately requested.
