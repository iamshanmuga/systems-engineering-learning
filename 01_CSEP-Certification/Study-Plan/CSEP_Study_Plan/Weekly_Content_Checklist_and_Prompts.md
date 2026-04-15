# CSEP Weekly Content Checklist & Prompt Library

**Purpose:** Master checklist of deliverables that must be produced for **each** week of the CSEP study programme, plus the exact, reusable prompts used to generate each deliverable (via Claude, NotebookLM, or other tools). This document is the single source of truth for scheduled tasks that auto-generate weekly content.

**How to use:**
1. Pick the target week and its topic scope from the **12-Week Topic Map** (below).
2. For each deliverable listed in the **Per-Week Checklist**, copy the corresponding prompt from the **Prompt Library** and substitute the `{{placeholders}}` with the week's values.
3. Save the outputs into `Week_XX/` following the **File Naming Convention**.
4. Tick off each deliverable in the checklist as it is produced.

---

## 12-Week Topic Map

| Week | Topic | SEH5 Chapter | ISO 15288 Anchor | Est. Hours |
|------|-------|--------------|------------------|-----------|
| 1 | SE Overview & Fundamentals | CH01 | §4 (Concepts & Terms) | 4.5 |
| 2 | Life Cycle Concepts | CH02 | §6 (Life Cycle) | 4 |
| 3 | Technical Processes — Part 1A (Business/Mission Analysis → Stakeholder Needs) | CH03 | §6.4.1–6.4.2 | 3 |
| 4 | Technical Processes — Part 1B (System Requirements → Architecture) | CH03 | §6.4.3–6.4.4 | 3 |
| 5 | Technical Processes — Part 2A (Design → Implementation → Integration) | CH03 | §6.4.5–6.4.7 | 3 |
| 6 | Technical Processes — Part 2B (Verification → Validation → Transition → Operation → Maintenance → Disposal) | CH03 | §6.4.8–6.4.13 | 3 |
| 7 | Technical Management Processes (8 processes) | CH04 | §6.3 | 5 |
| 8 | Agreement & Organizational Project-Enabling Processes | CH05 + CH06 | §6.1, §6.2 | 4 |
| 9 | Specialty Engineering (RAM, Safety, Security, HF, etc.) | CH07 | — | 4 |
| 10 | Crosscutting Methods (MBSE, SoS, Agile SE, Digital Engineering) | CH08 | — | 3 |
| 11 | Full Review + Practice Exam #1 | All | All | 6 |
| 12 | Gap Analysis + Practice Exam #2 + Final Brain Dump | All | All | 6 |

---

## File Naming Convention

All deliverables for a given week go under:
`01_CSEP-Certification/Study-Plan/CSEP_Study_Plan/Week_XX/`

| Deliverable | Filename |
|-------------|----------|
| Day-by-day study plan | `Week_XX_Study_Plan.md` |
| Exam-focused topic summaries | `Week_XX_Topic_Summaries.md` |
| Q&A flashcard deck (Markdown) | `Week_XX_Flashcards.md` |
| Flashcards exported as CSV | `Week_XX_Flashcards.csv` |
| Flashcards formatted for NotebookLM | `Week_XX_Flashcards_NotebookLM.csv` |
| Audio overview podcast scripts | `Week_XX_Audio_Overview_Scripts.md` |
| Tiered references / further reading | `Week_XX_References.md` |
| Mind map (generated via NotebookLM / draw.io) | `Week_XX_Mind_Map.png` |
| Narrated audio overview (NotebookLM) | `Week_XX_Audio_Overview.m4a` |
| Video overview (NotebookLM) | `Week_XX_Video_Overview.mp4` |
| Practice questions (exam-style MCQ) | `Week_XX_Practice_Questions.md` |
| Week assessment / brain dump answer key | `Week_XX_Assessment_Answers.md` |
| Illustration diagram prompts (one per topic summary) | `Week_XX_Illustration_Diagram_Prompts.md` |
| Generated illustration diagrams (Mermaid/SVG/PNG) | `Week_XX_Diagrams/` (folder, one file per summary: `Week_XX_Diagram_<n>_<slug>.{mmd,svg,png}`) |

---

## Per-Week Deliverables Checklist

Tick each item once produced and saved to `Week_XX/`.

### Core study materials
- [ ] **Study Plan** — day-by-day 7-day schedule with objectives, activities, key-term tables, self-check questions, and competency checklist. [Use Prompt 1]
- [ ] **Topic Summaries** — concise exam-focused written summaries (one per subject area). [Use Prompt 2]
- [ ] **Illustration Diagram Prompts** — one image-generation prompt per topic summary (where a diagram usefully reinforces the concept), plus rendered diagrams. [Use Prompt 12]
- [ ] **Flashcards (Markdown)** — 40–60 Q&A flashcards organised by sub-topic, with legend for ✅/🔄/❌. [Use Prompt 3]
- [ ] **Flashcards (CSV)** — CSV export suitable for Anki/Quizlet import. [Use Prompt 4a]
- [ ] **Flashcards (NotebookLM CSV)** — CSV formatted for NotebookLM ingestion. [Use Prompt 4b]
- [ ] **Audio Overview Scripts** — podcast-style host/guest dialogues for each day's topic. [Use Prompt 5]
- [ ] **References** — tiered (Tier 1/2/3) reference list including standards, books, and free online resources. [Use Prompt 6]
- [ ] **Practice Questions** — 15–25 exam-style multiple-choice questions with answer key and rationale. [Use Prompt 7]

### Multimedia / NotebookLM deliverables
- [ ] **Mind Map (PNG)** — visual map of the week's concepts. [Use Prompt 8]
- [ ] **Audio Overview (m4a)** — NotebookLM-generated narrated overview. [Use Prompt 9]
- [ ] **Video Overview (mp4)** — NotebookLM-generated narrated video overview with slides. [Use Prompt 11]

### Closure
- [ ] **Week Assessment Answer Key** — reference answers for the Day 7 self-check / brain-dump. [Use Prompt 10]
- [ ] **Update top-level progress tracker** — mark the chapter row in `01_CSEP-Certification/README.md` as 🔄 or ✅. [Manual]
- [ ] **Create PR** — per repo workflow, changes go on a feature branch `content/week-XX` with a PR; never commit directly to `main`.

---

## Prompt Library

> **Substitution variables** (fill in before running each prompt):
> - `{{WEEK_NUMBER}}` — e.g. `02`
> - `{{WEEK_TOPIC}}` — e.g. `Life Cycle Concepts`
> - `{{SEH5_CHAPTER}}` — e.g. `CH02 — Life Cycle Concepts`
> - `{{ISO_CLAUSES}}` — e.g. `ISO/IEC/IEEE 15288:2023 §6 (Life Cycle)`
> - `{{LEARNING_OBJECTIVES}}` — bulleted list of 8–12 learning objectives for the week
> - `{{KEY_SUBTOPICS}}` — 4–7 sub-topics for the week (the day-by-day breakdown)
> - `{{TARGET_HOURS}}` — total study hours (e.g. `4`)
> - `{{PRIOR_WEEK_TOPIC}}` — preceding week's topic (for continuity)
> - `{{NEXT_WEEK_TOPIC}}` — following week's topic (for preview section)
>
> **Canonical inputs (always attach / cite):**
> - INCOSE Systems Engineering Handbook, 5th Edition (SEH5) — relevant chapter
> - ISO/IEC/IEEE 15288:2023 — relevant clauses
> - SEBoK v2.10 — corresponding knowledge area
> - Any cross-reference books from `05_Resources/Books-and-References/`

---

### Prompt 1 — Study Plan (`Week_XX_Study_Plan.md`)

```
You are an INCOSE-certified CSEP tutor building a 7-day study plan for Week {{WEEK_NUMBER}}
of a 12-week CSEP preparation programme.

Week topic: {{WEEK_TOPIC}}
Primary reference: INCOSE SE Handbook 5th Edition, {{SEH5_CHAPTER}}
Secondary reference: {{ISO_CLAUSES}}
Target total study time: {{TARGET_HOURS}} hours, spread across 7 days.

Learning objectives to cover (student must be able to):
{{LEARNING_OBJECTIVES}}

Sub-topics to schedule across Days 1–6 (Day 7 is review):
{{KEY_SUBTOPICS}}

Produce a single Markdown document with the following exact sections:

1. Title block (Week number, topic, primary reference, ISO clauses, weekly theme, target hours).
2. "Week {{WEEK_NUMBER}} Learning Objectives" — numbered list mirroring the objectives above.
3. "Day-by-Day Schedule" — one section per day (Monday–Sunday), each containing:
   - Estimated time
   - SEH5 coverage
   - Topics to cover (bulleted)
   - Study activities (checkbox list)
   - Key definitions to memorise (Markdown table: Term | Definition)
   - Self-check questions (numbered, 3–5 per day)
4. A "Week {{WEEK_NUMBER}} Study Hours Summary" Markdown table.
5. "Upcoming Preview — Week {{NEXT_WEEK_NUMBER}} Topics" bulleted list pointing to {{NEXT_WEEK_TOPIC}}.
6. Footer with document version, date, and source citation.

Constraints:
- Use INCOSE / ISO 15288 terminology exactly.
- Every definition table must cite the standard (e.g. "INCOSE SEH5", "ISO 15288 §6.4.3").
- Use only Markdown — no HTML. Tables must render in GitHub-flavoured Markdown.
- Match the formatting style of Week_01_Study_Plan.md in this repo.
```

---

### Prompt 2 — Topic Summaries (`Week_XX_Topic_Summaries.md`)

```
You are writing concise, exam-focused topic summaries for Week {{WEEK_NUMBER}} of the CSEP
programme. These summaries are the student's primary revision material before attempting
practice questions.

Week topic: {{WEEK_TOPIC}}
Chapter: {{SEH5_CHAPTER}}
ISO anchor: {{ISO_CLAUSES}}

Produce one Markdown document containing ONE summary per sub-topic (3–6 summaries total):
{{KEY_SUBTOPICS}}

For each summary include:
- A clear heading: "## Summary N: <sub-topic title>"
- 2–4 paragraphs of prose written at the level of INCOSE SEH5
- Key terminology in **bold** on first use
- One Markdown definition or comparison table if appropriate
- A final "CSEP Exam Tip:" sentence highlighting what examiners emphasise
- A "Suggested Illustration:" block (1–2 sentences) describing the diagram type that would best
  reinforce this summary (e.g. process flow, context diagram, V-model, block diagram, state
  machine, concept map) and the 3–6 key elements/labels it must contain. If a diagram would add
  no pedagogical value for this particular summary, write "Suggested Illustration: N/A — text only"
  and briefly explain why. These blocks are the direct inputs to Prompt 12.

Rules:
- Cite SEH5 chapter/section numbers inline (e.g. "SEH5 §6.4.3").
- Use INCOSE / ISO definitions verbatim where they exist — do not paraphrase the formal
  definitions of "Systems Engineering", "system", "verification", "validation", "architecture",
  etc.
- Write in UK English.
- End the document with a version footer.
- Match the structure and tone of Week_01_Topic_Summaries.md.
```

---

### Prompt 3 — Flashcards (`Week_XX_Flashcards.md`)

```
Build a spaced-repetition flashcard deck for Week {{WEEK_NUMBER}} — {{WEEK_TOPIC}}.
Target: 50 ±10 cards, organised into 2–4 logical sections mapped to the week's sub-topics.

Input material: the Week_{{WEEK_NUMBER}}_Study_Plan.md and Week_{{WEEK_NUMBER}}_Topic_Summaries.md
I have just produced.

Output format: a single Markdown file with:
- Title block: "Topic:", "Format:", "Total Cards:", "Sections:", "How to use:" instructions,
  and legend ✅ Known | 🔄 Review | ❌ Re-study.
- One Markdown table per section with columns: # | 🃏 QUESTION (Front) | ✅ ANSWER (Back)
- Cards should cover:
   - All formal INCOSE / ISO definitions verbatim
   - Every key term from the day-by-day definition tables
   - All self-check questions from the Study Plan
   - Common CSEP exam gotchas (e.g. verification vs validation, stage vs process)
   - Process inputs, outputs, and purpose where relevant

Rules:
- Each card must be standalone — no "see card 12" references.
- Answers should be 1–3 sentences maximum. Longer facts go as their own card.
- Use exam-style phrasing: "Define X", "Name three Y", "What distinguishes A from B?".
- Match the structure of Week_01_Flashcards.md.
```

---

### Prompt 4a — Flashcards CSV (`Week_XX_Flashcards.csv`)

```
Convert Week_{{WEEK_NUMBER}}_Flashcards.md into a CSV suitable for Anki/Quizlet import.

CSV format:
- Header row: Front,Back,Tags
- One card per row.
- Escape commas and quotes per RFC 4180 (wrap field in double quotes; double any internal
  double quotes).
- Tags column: space-separated, e.g. "CSEP Week{{WEEK_NUMBER}} {{WEEK_TOPIC_SLUG}}".
- Preserve the card order from the Markdown file.
- UTF-8, LF line endings, no BOM.
```

---

### Prompt 4b — NotebookLM Flashcards CSV (`Week_XX_Flashcards_NotebookLM.csv`)

```
Produce a CSV formatted for NotebookLM source ingestion from Week_{{WEEK_NUMBER}}_Flashcards.md.

CSV format:
- Header row: Question,Answer,Topic,Difficulty
- Topic = the section heading the card belongs to.
- Difficulty = Easy | Medium | Hard, inferred from card type (pure recall = Easy, application
  = Medium, multi-step reasoning / scenario = Hard).
- Escape per RFC 4180. UTF-8, LF line endings.
- Keep card order stable.
```

---

### Prompt 5 — Audio Overview Scripts (`Week_XX_Audio_Overview_Scripts.md`)

```
Write a set of podcast-style audio overview scripts for Week {{WEEK_NUMBER}} — {{WEEK_TOPIC}}.
Format: conversation between Host (H) and Expert Guest (G), NotebookLM Audio Overview style.
Total target runtime: ~45 minutes across 6–7 tracks (one per sub-topic + a closing
recap track).

For each track include:
- A heading: "## 🎙️ Track N — <topic question>"
- "(Est. runtime: ~X minutes)" subheader
- A natural opening hook (Host welcomes listener, frames the question)
- Technically accurate dialogue — Expert Guest explains concepts using exact INCOSE / ISO
  terminology where it matters, but in conversational tone
- At least one moment per track where the Guest flags "what the exam tests on this"
- Closing beat (Host recaps, teases next track)

Rules:
- Each line starts "**H:**" or "**G:**" for TTS-friendly parsing.
- Do not invent organisations, people, or standards. Only cite what appears in SEH5,
  ISO 15288, SEBoK, NASA SE Handbook, or other references listed in Week_XX_References.md.
- Keep sentences tight — aim for <25 words each — to be TTS-legible.
- Match the tone and structure of Week_01_Audio_Overview_Scripts.md.
```

---

### Prompt 6 — References (`Week_XX_References.md`)

```
Compile a tiered reference list for Week {{WEEK_NUMBER}} — {{WEEK_TOPIC}}.

Structure with these headings:
- 🏆 Tier 1 — PRIMARY (Must-Know Standards)
- 🥈 Tier 2 — SECONDARY (Highly Recommended)
- 🥉 Tier 3 — SUPPLEMENTARY (Deeper Dives)
- 📚 Textbooks & Books
- 🌐 Free Online Resources (Markdown table)
- 📋 Standards Acquisition Priority List (Markdown table)

For each reference include:
- Full title
- Author(s) / publisher / edition / year
- Relevance rating ⭐ out of ⭐⭐⭐⭐⭐
- "What it covers:" bullet list
- "Week {{WEEK_NUMBER}} Topics Covered:" line tying it back to sub-topics
- "How to Access:" (URL, ISO/IEEE store, free PDF, institutional access)
- "Study Tip:" one-line actionable tip

Rules:
- Only include references that genuinely cover this week's material.
- Flag any reference that is superseded/withdrawn (e.g. IEEE 1220) clearly.
- Match the style of Week_01_References.md.
```

---

### Prompt 7 — Practice Questions (`Week_XX_Practice_Questions.md`)

```
Generate 20 CSEP-style multiple-choice practice questions for Week {{WEEK_NUMBER}} —
{{WEEK_TOPIC}}.

For each question:
- Question stem written in the style of the INCOSE CSEP exam (precise, scenario or
  definition based, single best answer).
- Four answer options labelled A–D.
- Exactly one correct answer.
- Answer key and 2–3 sentence rationale AT THE END of the document (not inline), citing
  the SEH5 section or ISO 15288 clause that supports the answer.

Coverage mix:
- 30% pure recall (definitions, process names, standards numbering)
- 50% conceptual application (pick the best principle / process / method for a scenario)
- 20% distinguishing commonly-confused concepts (e.g. verification vs validation,
  stage vs process, architecture vs design, functional vs allocated baseline)

Rules:
- No "all of the above" / "none of the above" options.
- Distractors must be plausible — drawn from adjacent concepts, not absurdities.
- Keep question stems ≤ 60 words.
```

---

### Prompt 8 — Mind Map (`Week_XX_Mind_Map.png`)

**Tool:** NotebookLM "Mind Map" feature, or Whimsical / draw.io fallback.

**NotebookLM prompt (paste into NotebookLM chat after uploading Week_XX_Study_Plan.md and Week_XX_Topic_Summaries.md as sources):**

```
Create a mind map for Week {{WEEK_NUMBER}} of my CSEP study — topic: {{WEEK_TOPIC}}.

Root node: "{{WEEK_TOPIC}}"
First-level branches: each of the day-by-day sub-topics from the Study Plan:
{{KEY_SUBTOPICS}}
Second-level branches: the key definitions and principles from the Topic Summaries,
grouped under the correct sub-topic.
Third-level branches: concrete examples, common exam gotchas, and cross-references
to other CSEP chapters where relevant.

Style: clear, exam-revision oriented, minimum visual clutter, exportable as PNG at
1920×1080 or higher.
```

Export as PNG and save as `Week_XX_Mind_Map.png` in the week's folder.

---

### Prompt 9 — Audio Overview (`Week_XX_Audio_Overview.m4a`)

**Tool:** NotebookLM "Audio Overview" feature.

**Setup:**
1. In NotebookLM, create a notebook named `CSEP Week {{WEEK_NUMBER}} — {{WEEK_TOPIC}}`.
2. Upload these sources:
   - `Week_XX_Study_Plan.md`
   - `Week_XX_Topic_Summaries.md`
   - `Week_XX_Flashcards.md`
   - `Week_XX_References.md`
   - Relevant SEH5 chapter PDF (if available)
3. Click "Audio Overview" → "Customize".

**Customisation prompt to paste:**

```
Produce a deep-dive podcast-style conversation (two hosts) for a CSEP candidate studying
Week {{WEEK_NUMBER}} on {{WEEK_TOPIC}}.

Target audience: an experienced engineer preparing for the INCOSE CSEP exam. Assume they
already know basic engineering but are newly learning the formal INCOSE / ISO 15288
terminology.

Cover, in order:
1. Why this topic matters for the exam and in real projects.
2. The formal INCOSE and ISO definitions verbatim (pronounce acronyms in full the first
   time).
3. Each of the following sub-topics in ~3–5 minutes each: {{KEY_SUBTOPICS}}.
4. The 3–5 most commonly confused distinctions in this chapter.
5. Three high-yield exam tips specific to this topic.
6. A one-minute recap.

Tone: engaging, technically precise, UK English. Target length: 18–25 minutes.
Do not invent references. Cite SEH5, ISO 15288, or SEBoK where specific claims are made.
```

Download the generated audio as `.m4a` and save to the week's folder.

---

### Prompt 11 — Video Overview (`Week_XX_Video_Overview.mp4`)

**Tool:** NotebookLM "Video Overview" feature (Studio panel → Video Overview).

**Setup:**
1. Open the NotebookLM notebook already created for this week
   (`CSEP Week {{WEEK_NUMBER}} — {{WEEK_TOPIC}}`) with the sources uploaded for the
   audio overview (Study Plan, Topic Summaries, Flashcards, References, SEH5 chapter).
2. In the Studio panel, click **Video Overview → Customize**.
3. Select style: **Explainer** (slides + narration). Select length: **Longer** if the
   topic has 5+ sub-topics, otherwise **Default**.

**Customisation prompt to paste into NotebookLM Video Overview "Customize":**

```
Produce a narrated explainer video for a CSEP candidate studying Week {{WEEK_NUMBER}}
on {{WEEK_TOPIC}}.

Audience: experienced engineer (5+ years) preparing for the INCOSE CSEP exam. They
already understand basic engineering but are learning formal INCOSE / ISO 15288
terminology.

Structure the video as follows (one slide per beat, use visuals — diagrams, tables,
process flows — wherever the concept benefits from them):

1. Cold open (15–20 sec): state the week's topic and why the exam tests it heavily.
2. Learning objectives slide (mirrors the objectives in Week_{{WEEK_NUMBER}}_Study_Plan.md).
3. For each of the following sub-topics, produce 1–3 slides (definition slide + example
   slide + "exam watch-out" slide if needed): {{KEY_SUBTOPICS}}.
4. A comparison / distinctions slide for the 3–5 most commonly confused concepts in
   this chapter (e.g. for CH03: verification vs validation, architecture vs design).
5. A process / life-cycle diagram slide where applicable (use the standard SEH5 or
   ISO 15288 diagram style — boxes + arrows, not artistic illustration).
6. Exam-tip montage: 3 high-yield exam tips for this week, one per slide.
7. Recap slide with the 5 must-remember takeaways.
8. "Next up" slide teasing Week {{NEXT_WEEK_NUMBER}} — {{NEXT_WEEK_TOPIC}}.

Style:
- UK English narration, clear and measured pace (avoid podcast-style banter — this is
  an explainer, not a conversation).
- Cite SEH5 section or ISO 15288 clause numbers on every slide that states a formal
  definition or process, shown as small footnote text on the slide.
- Use INCOSE / ISO 15288 terminology verbatim for formal definitions.
- Target runtime: 12–20 minutes.
- Do not invent references, people, or standards — only cite sources already in the
  notebook.
- On-screen text should be minimal per slide (≤ 40 words) — the narration carries the
  detail.
```

**Export & save:**
- Once the video finishes generating, use NotebookLM's download option (or record the
  output if direct download is unavailable) and save as
  `Week_XX_Video_Overview.mp4` in the week's folder.
- If NotebookLM only produces a shareable link (not a file), add the link to
  `Week_XX_References.md` under a new "Generated Multimedia" section and leave the
  `.mp4` checkbox unticked with a note.

---

### Prompt 10 — Week Assessment Answer Key (`Week_XX_Assessment_Answers.md`)

```
Produce a reference answer key for the Day 7 review activities in
Week_{{WEEK_NUMBER}}_Study_Plan.md.

Include:
- Model answers for every Day 1–6 self-check question (1 short paragraph each, citing
  SEH5 / ISO 15288 sections).
- A worked-through Brain Dump solution covering each of the bulleted brain-dump items.
- A rubric for the Week {{WEEK_NUMBER}} Competency Checklist: for each competency, a
  brief description of what "3/5" vs "5/5" mastery looks like.

Rules:
- Match the exact numbering and wording of the questions in the Study Plan.
- Keep answers crisp — aim for a student to review in 20–30 minutes.
- End with a "Next steps if you scored below 70%:" bullet list pointing to specific
  SEH5 sections, flashcards, and references to re-study.
```

---

### Prompt 12 — Illustration Diagram Prompts (`Week_XX_Illustration_Diagram_Prompts.md`)

**Purpose:** For every topic summary produced by Prompt 2 that is marked with a non-N/A
"Suggested Illustration:" block, generate a self-contained image-generation prompt that can
be pasted into an image/diagram tool (Mermaid Live Editor, draw.io, PlantUML, Whimsical, or
an AI image generator such as the ones in ChatGPT / Claude / Gemini) to render the diagram.

```
You are producing a set of diagram-generation prompts for Week {{WEEK_NUMBER}} —
{{WEEK_TOPIC}} of the CSEP study programme.

Input: Week_{{WEEK_NUMBER}}_Topic_Summaries.md (already produced). Read each summary's
"Suggested Illustration:" block.

For EACH summary whose "Suggested Illustration" is NOT marked "N/A — text only", produce
one entry in a single Markdown file with this exact structure:

## Diagram {{N}} — <summary title>

**Linked summary:** Summary N in Week_{{WEEK_NUMBER}}_Topic_Summaries.md
**Output filename:** `Week_{{WEEK_NUMBER}}_Diagrams/Week_{{WEEK_NUMBER}}_Diagram_{{N}}_<slug>.mmd`
(for Mermaid) or `.svg`/`.png` (for raster tools)
**Recommended tool:** Mermaid (preferred for process/flow/state), PlantUML (UML), draw.io
(context/block diagrams), or an AI image generator (conceptual illustrations only — not
for formal SE diagrams).
**Standards reference:** SEH5 §… / ISO 15288 §… that the diagram must be consistent with.

### Mermaid source (if applicable)
```mermaid
<a complete, copy-pastable Mermaid diagram that renders the concept>
```

### Alternative: natural-language prompt for an AI image generator
> <self-contained paragraph, 80–150 words, describing the exact diagram to render:
> layout, labelled nodes, arrows/relationships, colour hints (neutral/technical palette),
> style ("clean, textbook-style, flat vector, high-contrast labels, UK English spelling"),
> aspect ratio, and any terminology that must appear verbatim from INCOSE / ISO 15288.>

### What the diagram MUST show
- <bullet list of 3–6 mandatory elements/labels>
- <include INCOSE / ISO definitions verbatim where the label is a formal term>

### What the diagram MUST NOT show
- <things that would introduce non-standard or out-of-scope concepts, e.g. vendor logos,
  artistic embellishment, fabricated process steps>

### Exam relevance
One sentence linking the diagram to the CSEP exam objective it supports.

---

Repeat the block above for every eligible summary, numbered 1..N in the same order as the
summaries appear in Week_{{WEEK_NUMBER}}_Topic_Summaries.md. If the student chooses to
generate a diagram, the rendered file goes into `Week_{{WEEK_NUMBER}}_Diagrams/` using the
filename specified in that entry.

Rules:
- Prefer Mermaid first — it versions cleanly in git and renders on GitHub natively. Only
  fall back to AI image generation for conceptual illustrations that cannot be expressed
  as boxes-and-arrows (e.g. a metaphorical "iceberg" systems-thinking diagram).
- Do NOT invent process steps, standards, or terminology. If the Topic Summary cites SEH5
  §6.4.3, the diagram must use exactly the process names from that section.
- Use UK English on every label.
- Every diagram prompt must be standalone — no "see Diagram 2" cross-references.
- Match the style of the most recent Week_XX_Illustration_Diagram_Prompts.md that exists
  in the repo (if none exist yet, establish the template with Week {{WEEK_NUMBER}}).
```

**Rendering step (manual, after the prompt file is produced):**
1. Create the folder `Week_{{WEEK_NUMBER}}_Diagrams/`.
2. For each Mermaid entry, save the fenced block as a `.mmd` file using the specified
   filename, then render to `.svg` via `mmdc -i <file>.mmd -o <file>.svg` (mermaid-cli)
   or paste into <https://mermaid.live> and export SVG/PNG.
3. For AI-image entries, paste the natural-language prompt into the chosen image generator,
   download the result, and save with the specified filename.
4. Commit both the `.mmd` source and the rendered `.svg`/`.png` — the source is the source
   of truth; the raster is for embedding in slides.

---

## Scheduled-Task Execution Plan

When scheduling a weekly content-generation task, follow this sequence (dependencies in
order — each step feeds the next):

1. **Run Prompt 1** → produces `Week_XX_Study_Plan.md`
2. **Run Prompt 2** → produces `Week_XX_Topic_Summaries.md` (each summary includes a
   "Suggested Illustration:" block — the input to Prompt 12)
3. **Run Prompt 3** → produces `Week_XX_Flashcards.md` *(depends on 1 & 2)*
4. **Run Prompts 4a & 4b** (in parallel) → produce both CSVs *(depend on 3)*
5. **Run Prompt 5** → produces `Week_XX_Audio_Overview_Scripts.md` *(depends on 1 & 2)*
6. **Run Prompt 6** → produces `Week_XX_References.md`
7. **Run Prompt 7** → produces `Week_XX_Practice_Questions.md` *(depends on 1, 2, 3)*
8. **Run Prompt 10** → produces `Week_XX_Assessment_Answers.md` *(depends on 1)*
9. **Run Prompt 12** → produces `Week_XX_Illustration_Diagram_Prompts.md` *(depends on 2)*
10. **Manual — Render diagrams:** for each entry in the Illustration Diagram Prompts file,
    render to `Week_XX_Diagrams/` (Mermaid via `mmdc` or mermaid.live; AI images via chosen
    generator). Commit both source (`.mmd`) and rendered (`.svg`/`.png`).
11. **Manual — NotebookLM:** upload outputs from steps 1–7 (and the rendered diagrams from
    step 10 for richer visual context), then run Prompts 8, 9 & 11 to produce the mind map
    PNG, audio overview m4a, and video overview mp4.
12. **Manual:** update `01_CSEP-Certification/README.md` progress tracker.
13. **Manual — Git:** create feature branch `content/week-XX`, commit all files, open PR
    targeting `main`. (Per repo rule: never commit directly to `main`.)

---

## Maintenance

- When the Week 1 materials evolve, update the relevant prompt in this file to keep the
  templates aligned with the latest house style.
- If a new deliverable type is added (e.g. video scripts, exam simulator configs), add it
  to the Per-Week Checklist and append a new prompt to the Prompt Library.
- Record any prompt tweaks that materially improved output quality in a "Lessons Learned"
  section below.

### Lessons Learned
*(empty — populate as weeks are produced)*

---

*Document Version: 1.0 | Created: 2026-04-14 | Owner: CSEP Study Programme*
