# CSEP Study Plan — Systems Engineering Learning Repository
**Certification Target:** INCOSE CSEP (Certified Systems Engineering Professional)
**Primary Reference:** INCOSE Systems Engineering Handbook, 5th Edition (SEH5)
**Exam Standard:** ISO/IEC/IEEE 15288:2023

---

## 📁 Repository Structure

```
CSEP_Study_Plan/
├── README.md                          ← This file (project index)
├── Weekly_Content_Checklist_and_Prompts.md  ← Master checklist + reusable prompts for generating each week's materials
├── Week_01/
│   ├── Week_01_Study_Plan.md          ← Daily schedule & learning objectives (7 days)
│   ├── Week_01_Topic_Summaries.md     ← Concise summaries for all 6 topic areas
│   ├── Week_01_Flashcards.md          ← 160-card exam-focused flashcard deck
│   ├── Week_01_Audio_Overview_Scripts.md ← 7 podcast-style audio overview scripts
│   └── Week_01_References.md          ← Standards, textbooks, and free resources
├── Week_02/
│   ├── Week_02_Study_Plan.md          ← Daily schedule & learning objectives (7 days)
│   ├── Week_02_Topic_Summaries.md     ← Concise summaries for all 6 topic areas
│   ├── Week_02_Flashcards.md          ← 55-card exam-focused flashcard deck
│   ├── Week_02_Flashcards.csv         ← Anki/Quizlet import CSV
│   ├── Week_02_Flashcards_NotebookLM.csv ← NotebookLM ingestion CSV
│   ├── Week_02_Audio_Overview_Scripts.md ← 7 podcast-style audio overview scripts
│   ├── Week_02_References.md          ← Standards, textbooks, and free resources
│   ├── Week_02_Practice_Questions.md  ← 20 CSEP-style practice MCQs with answer key
│   ├── Week_02_Assessment_Answers.md  ← Day 1–6 self-check answers & brain dump key
│   └── Week_02_NotebookLM_Steps.md   ← Manual checklist for mind map, audio & video
├── Week_03/                           ← (Scheduled — Monday 2026-04-20)
│   ├── Week_03_Illustration_Diagram_Prompts.md  ← (New from Week 3 onward) Per-summary image-gen prompts
│   └── Week_03_Diagrams/                        ← (New from Week 3 onward) Rendered Mermaid / SVG / PNG diagrams
└── ...
```

---

## 🗓️ Study Plan Overview

| Week | Chapter Focus | Theme | Est. Hours | Status |
|------|--------------|-------|-----------|--------|
| **Week 1** | CH01 | SE Overview & Fundamentals | 4 | ✅ Complete |
| Week 2 | CH02 | Life Cycle Concepts | 4 | 🔄 In Progress |
| Week 3–4 | CH03 | Technical Processes — Part 1 (Stakeholder Needs → Architecture) | 6 | 🔲 Pending |
| Week 5–6 | CH03 | Technical Processes — Part 2 (Design → Disposal) | 6 | 🔲 Pending |
| Week 7 | CH04 | Technical Management Processes | 5 | 🔲 Pending |
| Week 8 | CH05 & CH06 | Agreement & Organizational Project-Enabling Processes | 4 | 🔲 Pending |
| Week 9 | CH07 | Specialty Engineering | 4 | 🔲 Pending |
| Week 10 | CH08 | Crosscutting Methods | 3 | 🔲 Pending |
| Week 11 | All | Full Review + Practice Exam #1 | 6 | 🔲 Pending |
| Week 12 | All | Gap Analysis + Practice Exam #2 | 6 | 🔲 Pending |

---

## 📚 Week 1 Contents Summary

### Week_01_Study_Plan.md
A day-by-day study schedule (Mon–Sun) covering CH01 — SE Overview & Fundamentals (~4.5 hours total):
- Day 1: What is Systems Engineering? — INCOSE & ISO/IEC/IEEE 15288 definitions, why SE exists
- Day 2: Systems — key vocabulary (system, SoI, enabling system, emergence, system boundary)
- Day 3: Systems thinking & systems science — von Bertalanffy, Forrester, Meadows, feedback loops
- Day 4: SE Principles Part 1 — holism, hierarchy, abstraction, encapsulation, modularity
- Day 5: SE Principles Part 2 — separation of concerns, feedback, evolvability, interfaces
- Day 6: SE in practice — stakeholders, common failure modes, ISO 15288 process groups overview
- Day 7: Review, brain dump & Week 1 self-assessment

### Week_01_Topic_Summaries.md
Concise topic summaries aligned to each day's content — designed for rapid revision before practice tests.

### Week_01_Flashcards.md
57 Q&A flashcards across 3 sections — scoped to CH01 SE Overview & Fundamentals:
- Section 1 (Cards 1–20): SE Introduction
- Section 2 (Cards 21–50): Systems Thinking & SE Principles
- Section 3 (Cards 51–57): SE Context, Stakeholders & Standards Overview

### Week_01_Audio_Overview_Scripts.md
Seven conversational audio scripts (NotebookLM-style podcast dialogue) — ideal for passive review while commuting, exercising, or cooking. Approx. 45 minutes total runtime.

### Week_01_References.md
Tiered reference list including:
- **Tier 1 (Primary):** ISO 15288:2023, SEH5, ISO 29148:2018, ISO 42010:2022
- **Tier 2 (Secondary):** NASA SE Handbook, SEBoK, DAU Guidebook
- **Tier 3 (Supplementary):** ISO 31000, DoDAF, textbooks

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
