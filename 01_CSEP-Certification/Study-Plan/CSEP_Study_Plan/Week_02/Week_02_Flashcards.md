# CSEP Week 2 — Flashcard Deck
**Topic:** Life Cycle Concepts
**Format:** Question (Front) | Answer (Back)
**Total Cards:** 55 | **Sections:** 3 sections mapped to the week's sub-topics
**How to use:** Cover the Answer column; read the Question; say your answer aloud; then check.
Mark cards: ✅ Known | 🔄 Review | ❌ Re-study

---

## 📦 Section 1 — Life Cycle Stages & Decision Gates (Cards 1–28)
*Covers: Days 1, 2 & 3 — Life Cycle Definition, Six Stages, and Decision Gates*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 1 | Define: System Life Cycle | The evolution of a system over time, encompassing all stages from conception through retirement — Concept, Development, Production, Utilisation, Support, and Retirement. (SEH5 Ch2; ISO 15288 §6.2) |
| 2 | Name the six ISO/IEC/IEEE 15288 life cycle stages in order. | Concept → Development → Production → Utilisation → Support → Retirement |
| 3 | Define: Life Cycle Stage | A defined period within the system life cycle characterised by a particular type of activity and bounded by decision gates. (ISO 15288 §6.2) |
| 4 | What is the primary purpose of the Concept Stage? | To identify stakeholder needs, explore alternative concepts, and select a preferred solution concept for further development. |
| 5 | What is the primary purpose of the Development Stage? | To refine system requirements, design and build the system, and verify and validate it against stakeholder needs. |
| 6 | What is the primary purpose of the Production Stage? | To manufacture or construct system instances and verify their conformance to the approved system configuration. |
| 7 | What is the primary purpose of the Utilisation Stage? | To operate the system in its intended environment to deliver the services for which it was designed. |
| 8 | What is the primary purpose of the Support Stage? | To provide services that sustain the system's availability and capability throughout its operational life. |
| 9 | What is the primary purpose of the Retirement Stage? | To take the system out of service safely — decommissioning, disposing of hazardous materials, and archiving documentation. |
| 10 | What is a Decision Gate? | A formal review point at the boundary between life cycle stages used to assess whether exit criteria have been met and to authorise (or deny) progression to the next stage. (SEH5 Ch2; ISO 15288 §6.2) |
| 11 | What four outcomes can a decision gate produce? | (1) Proceed, (2) Conditional Proceed, (3) Return (to current or prior stage), (4) Terminate. |
| 12 | Define: Exit Criteria | The set of conditions that must be satisfied before a system may progress from one life cycle stage to the next. |
| 13 | What distinguishes a system life cycle from a project life cycle? | The system life cycle covers all stages from concept to retirement of the system itself; the project life cycle covers the timeline and milestones of the project that creates or evolves the system. |
| 14 | What distinguishes a system life cycle from a product life cycle? | The system life cycle is an engineering/SE construct (ISO 15288); the product life cycle is a commercial/market construct (introduction → growth → maturity → decline). |
| 15 | In which life cycle stage does the Concept of Operations (ConOps) first appear? | The Concept Stage — as a key artefact capturing how the system will be used in its operational environment. |
| 16 | What is the System Requirements Review (SRR)? | A formal decision gate review verifying that system requirements have been adequately defined and are consistent with stakeholder needs — typically at the Concept/Development boundary. |
| 17 | What is the Critical Design Review (CDR)? | A formal decision gate review assessing whether the detailed design is complete and ready to proceed to fabrication — typically held mid-Development stage. |
| 18 | What is the Operational Readiness Review (ORR)? | A formal decision gate review confirming that the system and its operational support infrastructure are ready for transition to the Utilisation Stage. |
| 19 | At which stage transition would you expect a Preliminary Design Review (PDR)? | Within the Development Stage, before detailed design begins — it reviews the system architecture and preliminary design for completeness and adequacy. |
| 20 | True or false: ISO/IEC/IEEE 15288 mandates the use of named reviews such as SRR and CDR. | False — ISO 15288 mandates the principle of decision gates with exit criteria; named reviews (SRR, PDR, CDR) are programme-specific implementations, not ISO requirements. |
| 21 | In which stage is the largest share of SE resources typically applied? | The Development Stage — it encompasses requirements definition, design, build, and system-level V&V. |
| 22 | Why is the Retirement Stage often neglected in planning — and what are the consequences? | It is distant and speculative at project start, so it receives little design attention; consequences include unplanned disposal costs, hazardous material issues, and loss of system knowledge. |
| 23 | Which life cycle stage has the most acquirer influence over system design? | The Concept Stage — this is where stakeholder needs and constraints are defined, before design commitments are made. |
| 24 | "Testing" occurs in which life cycle stages, and for what purpose in each? | Development Stage: verification of the design; Production Stage: conformance testing against the approved configuration. |
| 25 | What does "conditional proceed" mean at a decision gate? | The programme is authorised to proceed to the next stage, but with defined open items that must be resolved within an agreed timeframe. |
| 26 | Name two artefacts typically produced during the Concept Stage. | Concept of Operations (ConOps) and Stakeholder Needs Statement (or Mission Concept document). |
| 27 | What is a "Stage Transition Review"? | A formal review conducted at a decision gate to assess whether exit criteria for the current stage have been met and to authorise stage transition. (ISO 15288 §6.2) |
| 28 | In the Support Stage, what types of maintenance are typically performed? | Corrective maintenance (fixing failures), preventive maintenance (scheduled servicing), and adaptive maintenance (modifications for changed operational needs). |

---

## 📦 Section 2 — Life Cycle Models & Processes vs Stages (Cards 29–46)
*Covers: Days 4 & 5 — Life Cycle Models and the Process/Stage Distinction*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 29 | Define: Life Cycle Model | A framework that identifies and describes the stages, decision gates, and overall approach used to manage a system's life cycle. (SEH5 Ch2) |
| 30 | Define: Sequential Life Cycle Model | A model in which life cycle stages are executed in order, with each stage substantially completed before the next begins. Appropriate when requirements are stable and technology mature. |
| 31 | Define: Iterative Life Cycle Model | A model in which the system is progressively refined through multiple successive cycles, each producing a more complete or capable version. Appropriate when requirements evolve. |
| 32 | Define: Concurrent Life Cycle Model | A model in which multiple life cycle stages overlap and are conducted simultaneously to reduce schedule. Carries higher risk and requires strong configuration control. |
| 33 | Define: Evolutionary (Incremental) Life Cycle Model | A model in which the system is delivered in discrete capability increments, with each increment delivering usable capability. Common in large-scale defence and space programmes. |
| 34 | What is Agile SE, and how does it differ from Agile software development? | Agile SE embeds iterative sprint-based development within an overarching SE framework that manages the full system life cycle, interfaces, and system-level V&V. Agile software development focuses on software delivery only, without necessarily managing the full system. |
| 35 | Define: Life Cycle Model Tailoring | The adaptation of a standard life cycle model to fit the unique characteristics, risks, and constraints of a given programme. Expected and encouraged by ISO 15288. |
| 36 | When is a sequential model most appropriate? | When requirements are well-understood and stable, technology is mature, and/or regulatory frameworks demand strict stage separation (e.g., nuclear, medical devices). |
| 37 | When is an iterative model most appropriate? | When requirements are expected to evolve, stakeholder feedback is essential, or risk must be managed by building and testing early. |
| 38 | What is the principal risk of a concurrent life cycle model? | Starting downstream stages before upstream stages are mature can create expensive rework when upstream changes cascade into completed downstream work. |
| 39 | Define: Life Cycle Process | A set of interrelated activities that transform inputs into outputs, performed in any applicable life cycle stage. (ISO 15288 §6.1) |
| 40 | What is the key distinction between a life cycle stage and a life cycle process? | A stage answers "When?" — it is a period in the system's evolution. A process answers "What?" — it is a set of activities that can be invoked in any applicable stage. |
| 41 | Name the four ISO/IEC/IEEE 15288 process groups. | (1) Technical Processes, (2) Technical Management Processes, (3) Agreement Processes, (4) Organisational Project-Enabling Processes. |
| 42 | How many processes does ISO/IEC/IEEE 15288:2023 define in total? | 30 processes across the four process groups. |
| 43 | How many Technical Processes does ISO 15288 define? | 14 Technical Processes (from Business/Mission Analysis through to Disposal). |
| 44 | In which process group is Configuration Management found? | Technical Management Processes (ISO 15288 §6.3). |
| 45 | Can the Verification process be applied in the Production Stage? Justify your answer. | Yes — Production testing verifies that manufactured instances conform to the approved system configuration. ISO 15288 processes are not stage-specific; they are applied wherever the activities are relevant. |
| 46 | What is the CSEP exam trap involving the "Development Stage" vs a "Development Process"? | Candidates confuse the Development Stage (a period in the life cycle) with a development process. ISO 15288 has no single process called "Development" — the work of development is performed by the 14 Technical Processes, which are also applied in other stages. |

---

## 📦 Section 3 — Cost of Change & Life Cycle Cost (Cards 47–55)
*Covers: Day 6 — Cost of Change, LCC, and the SE Value Proposition*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 47 | Define: Cost of Change (Cost-of-Correction Curve) | The principle that the cost of correcting an error or implementing a change increases exponentially as the system progresses through its life cycle. (SEH5 Ch2, citing Boehm) |
| 48 | Who is the researcher most associated with the cost-of-change curve? | Barry Boehm — from his 1981 research on software development cost multipliers for late defect correction. |
| 49 | Define: Life Cycle Cost (LCC) | The total cost of a system across all life cycle stages — concept, development, production, utilisation, support, and retirement — including acquisition, operation, maintenance, and disposal costs. |
| 50 | Why is acquisition cost a misleading metric for comparing system options? | Acquisition cost typically represents only 20–30% of total LCC; the remaining 70–80% is incurred in operations and support. A low-acquisition-cost system may have much higher LCC. |
| 51 | Define: SE Value Proposition | The argument that early SE investment — particularly in requirements, architecture, and V&V planning — reduces total life cycle cost by preventing costly late-stage changes. |
| 52 | At which life cycle stage is the cost of change lowest? | The Concept Stage — errors corrected here cost a fraction of what the same correction costs in later stages. |
| 53 | Name three SE activities that deliver the highest return on investment by preventing late-stage change. | (1) Rigorous requirements elicitation and validation; (2) early architecture definition; (3) formal V&V planning established in the Concept/early Development stage. |
| 54 | Define: Total Ownership Cost (TOC) | The complete cost borne by the owner/operator across the entire system ownership period, including acquisition, operations, support, and disposal — used particularly in defence acquisition. |
| 55 | What is the SE argument against starting Production before requirements and design are mature? | Starting Production early does not reduce total cost — it amplifies cost because rework in Production is 10–100x more expensive than correcting errors in the Concept or early Development stage. |

---

*Document Version: 1.0 | Created: 2026-04-14 | Source: INCOSE SEH5 Ch2; ISO/IEC/IEEE 15288:2023 §6*
