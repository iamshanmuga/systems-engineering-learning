# CSEP Week 2 — Assessment Answer Key: Life Cycle Concepts
**Purpose:** Reference answers for Day 1–6 self-check questions and Day 7 brain dump
**Use:** Review after attempting your own answers; target 20–30 minutes for full review

---

## Day 1 Self-Check Answers — What is a System Life Cycle?

**Q1. Define "system life cycle" in your own words, then compare with the INCOSE/ISO definition.**
Model answer: A system life cycle is the complete span of a system's existence — from the earliest ideas about what the system should do through to the point where it is taken out of service and disposed of. Formally, INCOSE SEH5 (Ch2) and ISO/IEC/IEEE 15288 define it as the evolution of a system over time, encompassing the stages of Concept, Development, Production, Utilisation, Support, and Retirement. The key point is that the life cycle is not just the acquisition period — it includes operation, maintenance, and disposal, all of which must be designed for from the outset.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q2. What is the difference between a system life cycle and a project life cycle?**
Model answer: The system life cycle spans the entire existence of the system — from concept through retirement — regardless of how many projects are involved in creating, modifying, or decommissioning it. The project life cycle is narrower: it describes the planning and execution timeline of a specific project. A project typically covers only some of the system life cycle stages (e.g., Concept and Development); when the project ends, the system continues through Utilisation and Support. Multiple projects may exist within a single system life cycle (e.g., a mid-life capability upgrade project within a 30-year system life cycle).
*Cite: SEH5 Ch2*

**Q3. Why is it insufficient to manage a system's development without a life cycle framework?**
Model answer: Without a life cycle framework, there is no shared language for when activities begin and end, no agreed decision points for stage progression, and no systematic consideration of post-acquisition costs and constraints (such as supportability, disposal, and operational performance). Programmes without a life cycle framework tend to over-focus on the Development Stage and fail to design for operation, support, and retirement — resulting in high total life cycle costs and operational failures that were predictable and preventable.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q4. Name the six ISO/IEC/IEEE 15288 life cycle stages in order.**
Model answer: Concept → Development → Production → Utilisation → Support → Retirement.
*Cite: ISO 15288 §6.2*

---

## Day 2 Self-Check Answers — Life Cycle Stages

**Q1. What is the primary purpose of the Concept Stage? What key artefact does it produce?**
Model answer: The primary purpose of the Concept Stage is to identify stakeholder needs, explore alternative solution concepts, and select a preferred concept for further development. It is the stage where the problem is defined before solutions are committed to. The key artefact is the **Concept of Operations (ConOps)** — a document describing how the system will be used in its operational environment, by whom, and under what conditions.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q2. How does the Support Stage differ from the Utilisation Stage?**
Model answer: The Utilisation Stage is concerned with operating the system to deliver its intended services to users. The Support Stage is concerned with sustaining the system's availability and capability so that it can continue to be operated. These stages often run concurrently — the system is being operated while simultaneously being maintained and supported. They are distinct because the activities (operation vs maintenance) involve different stakeholders, different processes, and different cost drivers.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q3. At which stage is V&V (verification and validation) first formally applied?**
Model answer: V&V is first formally applied in the **Development Stage**, where the system design is verified (confirmed to meet specified requirements) and the system is validated (confirmed to meet stakeholder needs). However, V&V activities are not limited to Development — the Verification process (ISO 15288 Technical Process) is also applied in the Production Stage (verifying manufactured conformance) and in the Support Stage (verifying post-maintenance system state).
*Cite: ISO 15288 §6.4.9 and §6.4.10; SEH5 Ch2 and Ch3*

**Q4. Why is the Retirement Stage often overlooked in planning — and what are the consequences?**
Model answer: The Retirement Stage is distant at project start, creating planning bias toward near-term concerns. Consequences include: unplanned and potentially enormous disposal costs (e.g., nuclear decommissioning, hazardous material handling); loss of system knowledge when staff retire or move on before documentation is completed; stranded assets that cannot be safely disposed of; and legal or regulatory liability if disposal plans were not embedded in the original design.
*Cite: SEH5 Ch2*

**Q5. In which stage would you find the System Verification Review (SVR)?**
Model answer: The SVR is typically positioned at the end of the Development Stage — it is the decision gate review that confirms the system has been fully verified against its requirements and is ready for operational validation or transition to the Utilisation Stage. Some programmes position SVR between the Development and Utilisation stage boundaries.
*Cite: SEH5 Ch2*

---

## Day 3 Self-Check Answers — Decision Gates

**Q1. What four outcomes can a decision gate review produce?**
Model answer: (1) **Proceed** — all exit criteria satisfied; stage transition authorised. (2) **Conditional Proceed** — exit criteria largely met; defined open items tracked to owners and close-out dates; programme proceeds. (3) **Return** — exit criteria not met; programme returns to current or a previous stage for corrective action. (4) **Terminate** — fundamental programme viability failure or strategic change; programme is cancelled or restructured.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q2. Where in the life cycle would you expect a Preliminary Design Review (PDR)?**
Model answer: The PDR is typically held within the Development Stage, before detailed design begins. It reviews the system architecture and preliminary design for completeness, adequacy, and risk — confirming that the architecture is sound before committing to detailed design effort. It sits between the System Requirements Review (Concept/Development boundary) and the Critical Design Review (mid-Development).
*Cite: SEH5 Ch2*

**Q3. What is the difference between entry criteria and exit criteria for a stage?**
Model answer: **Entry criteria** are the conditions that must be satisfied before a programme is authorised to *enter* a stage. **Exit criteria** are the conditions that must be satisfied before a programme may *leave* a stage and progress to the next. Entry criteria for a stage are often equivalent to — or closely derived from — the exit criteria of the preceding stage. Both are defined by the programme as part of its life cycle model planning.
*Cite: SEH5 Ch2; ISO 15288 §6.2*

**Q4. Who has authority to approve stage transitions — the acquirer, supplier, or both?**
Model answer: Typically, the **acquirer** has authority to approve stage transitions — particularly major transitions (e.g., Development to Production). On complex programmes, both acquirer and supplier representatives participate in the review, but the acquirer holds the governance authority to authorise or deny progression. The Agreement Processes in ISO 15288 §6.1 govern the contractual framing of these decisions.
*Cite: ISO 15288 §6.1 and §6.2; SEH5 Ch2*

---

## Day 4 Self-Check Answers — Life Cycle Models

**Q1. Under what conditions would you select a sequential model over an iterative model?**
Model answer: A sequential model is appropriate when: requirements are well-understood and stable (low probability of significant change); technology is mature (no novel development risk); the regulatory or certification framework demands formal phase completion before progression (e.g., nuclear, aviation, medical devices); or when the programme has high accountability requirements that benefit from clearly bounded, documented stages.
*Cite: SEH5 Ch2*

**Q2. What is the principal risk of a concurrent life cycle model?**
Model answer: The principal risk is **change cascade**: if upstream stages (e.g., requirements or design) change after downstream stages (e.g., production preparation) have already commenced, the downstream work must be reworked. Concurrency is a schedule risk traded against cost risk — the programme compresses time but accepts higher rework cost if upstream decisions are not stable when downstream work begins.
*Cite: SEH5 Ch2*

**Q3. How does an Agile-SE approach differ from a pure Agile software development approach?**
Model answer: In Agile SE, iterative software development sprints are embedded within an overarching SE framework that continues to manage the full system life cycle, system-level requirements, architecture, interfaces, and system-level V&V. The SE layer operates above the sprint layer. In pure Agile software development, there is typically no formal SE layer — the focus is on delivering software functionality in sprint increments without necessarily managing system-level concerns, hardware interfaces, or whole-life V&V.
*Cite: SEH5 Ch2*

**Q4. What does "life cycle model tailoring" mean, and who performs it?**
Model answer: Life cycle model tailoring is the adaptation of a standard life cycle model (sequential, iterative, concurrent, evolutionary) to fit the specific characteristics, risks, regulations, and constraints of a programme. It is performed by the programme's SE and management team — typically the chief systems engineer and programme manager — in conjunction with acquirer requirements. ISO 15288 expects tailoring; applying any model without adaptation to programme context is poor practice.
*Cite: ISO 15288 §6.2; SEH5 Ch2*

---

## Day 5 Self-Check Answers — Processes vs Stages

**Q1. Name the four ISO/IEC/IEEE 15288 process groups.**
Model answer: (1) Technical Processes (14 processes). (2) Technical Management Processes (8 processes). (3) Agreement Processes (2 processes). (4) Organisational Project-Enabling Processes (6 processes). Total: 30 processes.
*Cite: ISO 15288 §6*

**Q2. Can the Verification process be applied in the Support Stage? Justify your answer.**
Model answer: Yes. The Verification process (ISO 15288 §6.4.9) is a Technical Process applicable in any stage where it is relevant. In the Support Stage, verification activities confirm that the system remains in conformance with its requirements after maintenance actions (corrective or adaptive). ISO 15288 processes are not locked to specific stages — they are applied wherever their activities are relevant to the programme's needs.
*Cite: ISO 15288 §6.4.9; SEH5 Ch3*

**Q3. What is the key distinction between a "stage" and a "process" in ISO/IEC/IEEE 15288?**
Model answer: A **stage** is a temporal construct — it defines *when* in the system's evolution a particular type of activity occurs. Stages are bounded by decision gates and occur in sequence (even if iterated). A **process** is a functional construct — it defines *what activities* are performed, with specific inputs, outputs, and outcomes. Processes are not stage-specific; the same process can be invoked in multiple stages. Stages tell you *when*; processes tell you *what*.
*Cite: ISO 15288 §6; SEH5 Ch2*

**Q4. In which process group would Configuration Management be found?**
Model answer: Configuration Management is found in the **Technical Management Processes** group (ISO 15288 §6.3). Other Technical Management Processes include Project Planning, Project Assessment and Control, Decision Management, Risk Management, Information Management, Measurement, and Quality Assurance.
*Cite: ISO 15288 §6.3*

---

## Day 6 Self-Check Answers — Cost of Change & Life Cycle Thinking

**Q1. Describe the cost-of-change curve and what it implies for SE effort allocation.**
Model answer: The cost-of-change curve (based on Boehm's 1981 research, cited in SEH5 Ch2) shows that the cost of correcting an error or implementing a change increases exponentially as the system progresses through its life cycle. A correction costing one unit in the Concept Stage may cost 10 units in Development, 100 units in Production, and 1,000+ units in Utilisation. The implication for SE effort allocation is clear: SE effort should be **front-loaded** into the Concept and early Development stages, where the cost of finding and fixing errors is minimised.
*Cite: SEH5 Ch2 (citing Boehm, 1981)*

**Q2. Why is acquisition cost a misleading metric for comparing system options?**
Model answer: Acquisition cost captures only the cost to build (or buy) the system — typically 20–30% of total life cycle cost. The remaining 70–80% is incurred operating and supporting the system over its operational life. A system option with low acquisition cost may have high maintenance requirements, energy consumption, or spare parts costs that make it significantly more expensive over its life cycle. Total Life Cycle Cost (LCC) is the correct metric for whole-life comparison.
*Cite: SEH5 Ch2*

**Q3. Give two examples where poor requirements definition in the Concept Stage caused large costs in later stages.**
Model answer (examples): (1) A military vehicle programme where survivability requirements were inadequately defined in the Concept Stage led to a significant structural redesign in mid-Development, requiring retesting of the full vehicle — a cost many times greater than a thorough requirements analysis would have cost. (2) A software-intensive avionics system where performance requirements were ambiguous in the Concept Stage required multiple architecture revisions in Development when actual performance metrics were later clarified by the operator, delaying delivery and increasing integration test costs substantially.
*Cite: SEH5 Ch2 (general principle; specific examples illustrative)*

**Q4. What is the SE argument for investing heavily in the Concept Stage even under schedule pressure?**
Model answer: Under schedule pressure, the instinct is to shorten Concept Stage work and begin Design or Development earlier. The SE argument against this is the cost-of-change curve: every decision deferred or requirement left ambiguous in the Concept Stage will cost exponentially more to resolve in Development or Production. The programme will spend less total time and money by investing properly in the Concept Stage — it is a false economy to abbreviate it. This is the SE value proposition: spend more early, spend far less overall, and deliver a system that actually meets stakeholder needs.
*Cite: SEH5 Ch1 and Ch2*

---

## Day 7 Brain Dump — Model Answers

**1. List the six ISO/IEC/IEEE 15288 life cycle stages with one-line purpose each.**

| Stage | One-Line Purpose |
|-------|----------------|
| Concept | Identify stakeholder needs, explore concepts, select preferred solution |
| Development | Refine requirements, design, build, verify, and validate the system |
| Production | Manufacture system instances; verify conformance to approved configuration |
| Utilisation | Operate the system in its intended environment |
| Support | Sustain system availability through maintenance and support services |
| Retirement | Decommission and safely dispose of the system; archive knowledge |

**2. Describe the four decision gate outcomes.**
Proceed — all exit criteria met, stage transition authorised. Conditional Proceed — open items tracked, programme advances. Return — criteria not met, return to current or prior stage. Terminate — programme cancelled or fundamentally restructured.

**3. Explain the process/stage distinction in three sentences.**
A life cycle stage defines *when* in the system's evolution activities occur — it is a bounded period characterised by a particular type of work. A life cycle process defines *what activities* are performed — with specific inputs, outputs, and outcomes — and can be applied in any stage where relevant. The same process (e.g., Verification) may run in the Development, Production, and Support stages; stages and processes are orthogonal constructs, not synonyms.

**4. Sketch the cost-of-change curve — label each stage region.**
Curve shape: exponential rise from left (Concept) to right (Retirement).
- Concept: minimum cost, ~×1
- Development: low-to-medium cost, ~×10
- Production: high cost, ~×100
- Utilisation: very high cost, ~×100–×1,000
(Key point: the curve rises steeply after Development commitment — design and production are difficult to reverse.)

**5. Name four life cycle models and an appropriate use case for each.**
- Sequential: nuclear power plant certification (stable requirements, regulatory stage gates)
- Iterative: new military unmanned system (evolving operational requirements, high risk)
- Concurrent: commercial satellite (schedule-critical, long-lead production overlap with late-design development)
- Evolutionary: national air defence system Block upgrade (incremental capability deliveries)

---

## Competency Rubric — Week 2

| Competency | 3/5 Mastery | 5/5 Mastery |
|-----------|-------------|-------------|
| Define all six life cycle stages verbatim | Can name all six stages and give a rough purpose | Can state each stage's purpose precisely using ISO 15288 terminology without notes |
| Distinguish process vs stage | Can explain the difference with prompting | Can spontaneously illustrate with three examples of the same process applied across multiple stages |
| Describe three life cycle models with use cases | Can name three models and broadly describe them | Can state appropriate use cases, key risks, and benefits for each model, choosing correctly in exam scenarios |
| Sketch cost-of-change curve from memory | Draws approximate curve shape | Draws exponential curve, correctly labels each stage region, and states the Boehm origin |
| Name the four ISO 15288 process groups | Can name all four with the count of processes | Can name all four plus examples of individual processes in each group |
| Explain LCC vs acquisition cost | Can state that LCC includes more than acquisition | Can state the 20–30% / 70–80% split and explain which design decisions drive operations and support costs |
| Describe decision gates and four outcomes | Can name the four outcomes | Can describe exit criteria, the role of the acquirer, and the distinction between ISO 15288 principles and named reviews |

---

## Next Steps if You Scored Below 70%

- **Stages unclear?** Re-read SEH5 Ch2 stage descriptions; use Day 2 Flashcards (Cards 9–20).
- **Decision gates uncertain?** Re-read SEH5 Ch2 decision gate section; use Day 3 Flashcards (Cards 21–28) and map named reviews to stage transitions.
- **Process/stage distinction not solid?** Re-read Topic Summary 5 and Day 5 Flashcards (Cards 39–46); practice saying the distinction aloud.
- **Cost-of-change curve not memorised?** Draw it three times from scratch; annotate with stage names and rough cost multipliers.
- **Life cycle models vague?** Re-read Topic Summary 4 and Day 4 Flashcards (Cards 29–38); build a comparison table.

---

*Document Version: 1.0 | Created: 2026-04-14 | Source: INCOSE SEH5 Ch2; ISO/IEC/IEEE 15288:2023 §6*
