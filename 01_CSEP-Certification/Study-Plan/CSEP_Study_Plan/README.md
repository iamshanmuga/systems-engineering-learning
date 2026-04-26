# CSEP Study Plan — Systems Engineering Learning Repository
**Certification Target:** INCOSE CSEP (Certified Systems Engineering Professional)
**Primary Reference:** INCOSE Systems Engineering Handbook, 5th Edition (SEH5)
**Exam Standard:** ISO/IEC/IEEE 15288:2023

---

## 📁 Repository Structure

```
CSEP_Study_Plan/
├── README.md                          ← This file (project index)
├── weekly_content_checklist_and_prompts.md  ← Master checklist + reusable prompts for generating each week's materials
├── Week_01/
│   ├── week_01_study_plan.md          ← Daily schedule & learning objectives (7 days)
│   ├── week_01_topic_summaries.md     ← Concise summaries for all 6 topic areas
│   ├── week_01_flashcards.md          ← 160-card exam-focused flashcard deck
│   ├── week_01_audio_overview_scripts.md ← 7 podcast-style audio overview scripts
│   └── week_01_references.md          ← Standards, textbooks, and free resources
├── Week_02/
│   ├── week_02_study_plan.md          ← Daily schedule & learning objectives (7 days)
│   ├── week_02_topic_summaries.md     ← Concise summaries for all 6 topic areas
│   ├── week_02_flashcards.md          ← 55-card exam-focused flashcard deck
│   ├── week_02_flashcards.csv         ← Anki/Quizlet import CSV
│   ├── week_02_flashcards_notebooklm.csv ← NotebookLM ingestion CSV
│   ├── week_02_audio_overview_scripts.md ← 7 podcast-style audio overview scripts
│   ├── week_02_references.md          ← Standards, textbooks, and free resources
│   ├── week_02_practice_questions.md  ← 20 CSEP-style practice MCQs with answer key
│   ├── week_02_assessment_answers.md  ← Day 1–6 self-check answers & brain dump key
│   └── week_02_notebooklm_steps.md   ← Manual checklist for mind map, audio & video
├── Week_03/                           ← ✅ Complete (CH03 Part 1A: BMA → Stakeholder Needs)
│   ├── week_03_study_plan.md          ← Daily schedule & learning objectives (7 days)
│   ├── week_03_topic_summaries.md     ← Concise summaries for all 7 topic areas
│   ├── week_03_flashcards.md          ← 55-card exam-focused flashcard deck
│   ├── week_03_flashcards.csv         ← Anki/Quizlet import CSV
│   ├── week_03_flashcards_notebooklm.csv ← NotebookLM ingestion CSV
│   ├── week_03_audio_overview_scripts.md ← 7 podcast-style audio overview scripts (~45 min)
│   ├── week_03_references.md          ← Standards, textbooks, and free resources
│   ├── week_03_practice_questions.md  ← 20 CSEP-style practice MCQs with answer key
│   ├── week_03_assessment_answers.md  ← Day 1–6 self-check answers & brain dump key
│   ├── week_03_illustration_diagram_prompts.md  ← (New from Week 3 onward) Per-summary image-gen prompts — 6 diagrams
│   └── Week_03_Diagrams/                        ← (New from Week 3 onward) Rendered Mermaid sources (.mmd) + SVG renderings
│       ├── Week_03_Diagram_1_bma_process_position.{mmd,svg}
│       ├── Week_03_Diagram_2_conops_vs_opscon.{mmd,svg}
│       ├── Week_03_Diagram_3_snrd_ipo.{mmd,svg}
│       ├── Week_03_Diagram_4_stakeholder_power_interest.{mmd,svg}
│       ├── Week_03_Diagram_5_requirements_hierarchy.{mmd,svg}
│       └── Week_03_Diagram_6_validation_vs_verification.{mmd,svg}
└── ...
```

---

## 🗓️ Study Plan Overview

| Week | Chapter Focus | Theme | Est. Hours | Status |
|------|--------------|-------|-----------|--------|
| **Week 1** | CH01 | SE Overview & Fundamentals | 4 | ✅ Complete |
| **Week 2** | CH02 | Life Cycle Concepts | 4 | ✅ Complete |
| **Week 3** | CH03 | Technical Processes — Part 1A (BMA → Stakeholder Needs, §6.4.1–6.4.2) | 3 | ✅ Complete |
| Week 4 | CH03 | Technical Processes — Part 1B (System Requirements → Architecture, §6.4.3–6.4.4) | 3 | 🔲 Pending |
| Week 5–6 | CH03 | Technical Processes — Part 2 (Design → Disposal) | 6 | 🔲 Pending |
| Week 7 | CH04 | Technical Management Processes | 5 | 🔲 Pending |
| Week 8 | CH05 & CH06 | Agreement & Organizational Project-Enabling Processes | 4 | 🔲 Pending |
| Week 9 | CH07 | Specialty Engineering | 4 | 🔲 Pending |
| Week 10 | CH08 | Crosscutting Methods | 3 | 🔲 Pending |
| Week 11 | All | Full Review + Practice Exam #1 | 6 | 🔲 Pending |
| Week 12 | All | Gap Analysis + Practice Exam #2 | 6 | 🔲 Pending |

---

## 📚 Week 1 Contents Summary

### week_01_study_plan.md
A day-by-day study schedule (Mon–Sun) covering CH01 — SE Overview & Fundamentals (~4.5 hours total):
- Day 1: What is Systems Engineering? — INCOSE & ISO/IEC/IEEE 15288 definitions, why SE exists
- Day 2: Systems — key vocabulary (system, SoI, enabling system, emergence, system boundary)
- Day 3: Systems thinking & systems science — von Bertalanffy, Forrester, Meadows, feedback loops
- Day 4: SE Principles Part 1 — holism, hierarchy, abstraction, encapsulation, modularity
- Day 5: SE Principles Part 2 — separation of concerns, feedback, evolvability, interfaces
- Day 6: SE in practice — stakeholders, common failure modes, ISO 15288 process groups overview
- Day 7: Review, brain dump & Week 1 self-assessment

### week_01_topic_summaries.md
Concise topic summaries aligned to each day's content — designed for rapid revision before practice tests.

### week_01_flashcards.md
57 Q&A flashcards across 3 sections — scoped to CH01 SE Overview & Fundamentals:
- Section 1 (Cards 1–20): SE Introduction
- Section 2 (Cards 21–50): Systems Thinking & SE Principles
- Section 3 (Cards 51–57): SE Context, Stakeholders & Standards Overview

### week_01_audio_overview_scripts.md
Seven conversational audio scripts (NotebookLM-style podcast dialogue) — ideal for passive review while commuting, exercising, or cooking. Approx. 45 minutes total runtime.

### week_01_references.md
Tiered reference list including:
- **Tier 1 (Primary):** ISO 15288:2023, SEH5, ISO 29148:2018, ISO 42010:2022
- **Tier 2 (Secondary):** NASA SE Handbook, SEBoK, DAU Guidebook
- **Tier 3 (Supplementary):** ISO 31000, DoDAF, textbooks

---

## 📚 Week 3 Contents Summary

### week_03_study_plan.md
A day-by-day study schedule (Mon–Sun) covering CH03 Part 1A — Business/Mission Analysis → Stakeholder Needs (~3 hours total):
- Day 1: Why BMA exists — solution-first trap, enterprise→project bridge, BMA purpose (ISO 15288 §6.4.1)
- Day 2: Inside BMA — 5 activity clusters, ConOps vs OpsCon (ISO 29148 §4.2 / §4.3), MoEs
- Day 3: SN&RD purpose — Acquirer→Supplier perspective shift (ISO 15288 §6.4.2)
- Day 4: Stakeholder identification & elicitation techniques (8 categories, 8+ elicitation methods)
- Day 5: 6-level requirements hierarchy + 9 ISO 29148 §5.2 characteristics ("NAU CSF VCC")
- Day 6: Validation criteria, MoEs/MoPs, baselining, V&V distinction (4 verification methods — TAID)
- Day 7: Review, brain dump & Week 3 self-assessment

### week_03_topic_summaries.md
Seven topic summaries (Summary 1–7) covering BMA, ConOps/OpsCon, SN&RD, stakeholders, requirements hierarchy, characteristics & baselining, and validation — each with Suggested Illustration blocks cross-referenced from the Diagram Prompts file.

### week_03_flashcards.md
55 Q&A flashcards across 3 topic sections (with a finer 6-way day-level slicing for daily drill):
- **Section 1 — Business or Mission Analysis (Cards 1–17)** — Days 1 & 2 (BMA purpose 1–8 · BMA activities & ConOps/OpsCon 9–17)
- **Section 2 — Stakeholder Needs & Requirements Definition (Cards 18–41)** — Days 3 & 4 (SN&RD purpose 18–29 · stakeholders & elicitation 30–41)
- **Section 3 — Requirements Hierarchy, Characteristics & Baselining (Cards 42–55)** — Days 5 & 6 (hierarchy & 9 characteristics 42–51 · MoE/MoP, baselining, V&V 52–55)

### week_03_audio_overview_scripts.md
Seven conversational audio scripts (Host & Guest dialogue, NotebookLM-style) — approx. 45 minutes total runtime, matched to the 7 topic summaries.

### week_03_references.md
Tiered reference list scoped to CH03 §6.4.1 and §6.4.2:
- **Tier 1 (Primary):** ISO 15288:2023 §6.4.1 and §6.4.2, SEH5 Ch3, ISO 29148:2018 §4.2, §4.3, §5.2, §9
- **Tier 2 (Secondary):** SEBoK, NASA SEH, DAU Guidebook, INCOSE GtWR
- **Tier 3 (Supplementary):** ISO 24748-1, Robertson Volere, Alexander & Stevens, Kulak & Guiney

### week_03_practice_questions.md
20 CSEP-style MCQs with answer key, rationales, and ISO/SEH5 citations.

### week_03_assessment_answers.md
Model answers for Day 1–6 self-checks and the Day 7 brain dump, including the 6-level hierarchy table, 5-of-5 competency rubric, Next Steps, and the "NAU CSF VCC" mnemonic for the 9 characteristics.

### week_03_illustration_diagram_prompts.md (new series starting Week 3)
Six diagram specifications — each with linked summary, output filename, recommended tool, standards reference, Mermaid source, AI-prompt alternative, MUST-show / MUST-NOT-show items, and exam relevance.

### Week_03_Diagrams/
Six Mermaid source files (.mmd) plus six hand-authored SVG renderings — render in any browser or Markdown viewer. Topics: BMA process position, ConOps vs OpsCon, SN&RD IPO, Stakeholder power–interest matrix, 6-level requirements hierarchy, Validation vs Verification tracks.

---

## 🎯 CSEP Exam Quick Facts
- **Questions:** 120 total (100 scored + 20 unscored)
- **Time:** 120 minutes
- **Format:** Multiple choice, single correct answer
- **Primary Reference:** INCOSE SEH 5th Edition (all questions based on this as of March 15, 2025)
- **Experience Requirement (CSEP):** ~5 years SE experience in ≥ 3 of 11 core SE areas

---

## 🔧 Git Workflow for This Repo

```bash
# Initialise repo (first time)
git init
git add .
git commit -m "Initial commit: Week 1 CSEP study materials"

# Track changes to study documents
git diff                    # See what changed before committing
git diff Week_01/           # Changes within Week 1 only
git log --oneline           # View commit history

# Recommended branching strategy
main            ← Stable, reviewed study materials
week-N-draft    ← Working branch per week
```

---

*Repository created: 2026-04-03 | Maintained by: Shanmuga Budda*
