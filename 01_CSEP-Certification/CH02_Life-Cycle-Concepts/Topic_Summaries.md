# CSEP Week 2 — Topic Summaries: Life Cycle Concepts
**Chapter:** INCOSE SEH5 Chapter 2 — Life Cycle Concepts
**ISO Anchor:** ISO/IEC/IEEE 15288:2023 §6 — System Life Cycle Processes
**Purpose:** Concise, exam-focused summaries for rapid revision before attempting practice questions

---

## Summary 1: System Life Cycle — Definition and Purpose

A **system life cycle** is the evolution of a system from its conception through its retirement. ISO/IEC/IEEE 15288:2023 defines it as the series of stages — Concept, Development, Production, Utilisation, Support, and Retirement — that a system passes through during its existence. INCOSE SEH5 Chapter 2 frames the life cycle as the primary organising principle for all SE activity: without a defined life cycle, projects lack a shared understanding of when activities begin and end, making planning, resourcing, and decision-making unreliable.

The life cycle concept is important because it forces stakeholders to think beyond the acquisition phase. Most systems spend a small fraction of their total existence in development; the majority of cost and risk occurs in the Utilisation and Support stages. A lifecycle-aware SE approach therefore treats operational effectiveness, supportability, and retirement as design drivers from the outset, not as afterthoughts.

It is important to distinguish three related but separate constructs: the **system life cycle** (the stages through which the system evolves), the **project life cycle** (the timeline and milestones of the project that creates or evolves the system), and the **product life cycle** (a commercial or market-oriented construct describing the product's journey from introduction to decline). The CSEP exam tests the system life cycle definition rigorously; candidates must not confuse it with the product life cycle.

**CSEP Exam Tip:** ISO 15288 governs the system life cycle through its six stages. The exam will ask you to name and sequence these stages correctly. Do not add or omit stages — there are exactly six in the standard.

---

## Summary 2: The Six Life Cycle Stages (ISO/IEC/IEEE 15288 §6.2)

ISO/IEC/IEEE 15288:2023 defines six life cycle stages. Each stage is characterised by a distinct type of activity, bounded at entry and exit by **decision gates** (also called stage transition reviews).

**1. Concept Stage** — The purpose of the Concept Stage is to identify stakeholder needs, explore alternative concepts, and select a preferred solution concept for further development. Key artefacts produced include the Concept of Operations (ConOps), preliminary stakeholder needs statements, and system concept documentation. The acquirer has the most influence at this stage, and SE effort at this point is least expensive — yet the decisions made here have the greatest impact on total life cycle cost.

**2. Development Stage** — The Development Stage refines system requirements, produces the system design, builds the system, and verifies and validates it. It encompasses the full technical process cycle from requirements definition through to system qualification. It is the most SE-intensive stage and the one where the largest share of SE resources is applied.

**3. Production Stage** — The Production Stage involves the manufacture or construction of system instances (one or many). Activities include manufacturing, assembly, inspection, and production testing against the approved system configuration. SE activities during this stage are primarily configuration management and production verification.

**4. Utilisation Stage** — In the Utilisation Stage, the system is operated by its intended users in its operational environment to deliver the services for which it was designed. SE activities focus on monitoring operational performance, capturing anomalies, and supporting operational decisions.

**5. Support Stage** — The Support Stage provides the services needed to sustain the system's availability and capability. It includes maintenance (corrective, preventive, adaptive), supply chain management, and life extension activities. In many defence programmes, the Support Stage is the longest and most costly.

**6. Retirement Stage** — The Retirement Stage takes the system out of service. Activities include decommissioning, safe disposal of hazardous materials, archiving documentation, and — where applicable — knowledge transfer to replacement systems. Failure to plan for retirement in the Concept Stage can result in significant unplanned cost (e.g., nuclear plant decommissioning).

![alt text](The_6_Life_Cycle_Stages.png)

**CSEP Exam Tip:** The exam frequently asks in which stage a named activity occurs. Memorise the primary purpose of each stage precisely. A common trap: "testing" occurs in both the Development and Production stages but for different reasons — Development testing is for **verification/validation** of the design; Production testing is for **conformance** to the approved configuration.

---

## Summary 3: Decision Gates — Stage Transition Reviews

A **decision gate** is a formal review point at the boundary between life cycle stages. Its purpose is to assess whether the exit criteria for the current stage have been met and to authorise (or deny) progression to the next stage. ISO/IEC/IEEE 15288:2023 uses the term "decision gate" and specifies that each stage should have defined entry and exit criteria.

A decision gate review can produce four outcomes:
1. **Proceed** — exit criteria satisfied; authorise entry to next stage
2. **Conditional Proceed** — proceed with defined open items to be resolved within agreed timeframe
3. **Return** — exit criteria not met; return to current or previous stage for corrective action
4. **Terminate** — the programme is cancelled or restructured; a valid and sometimes appropriate outcome

Well-known decision gate reviews (often used on defence and space programmes) map approximately to stage boundaries:
| Review | Common Stage Boundary |
|--------|-----------------------|
| System Requirements Review (SRR) | Concept → Development |
| Preliminary Design Review (PDR) | Early Development (before detailed design) |
| Critical Design Review (CDR) | Mid-Development (before fabrication) |
| System Verification Review (SVR) | Late Development (after system testing) |
| Operational Readiness Review (ORR) | Development → Utilisation |
| Disposal Readiness Review | Support → Retirement |

It is important to note that named reviews such as SRR and CDR are **programme-specific conventions**, not mandated by ISO 15288 itself. ISO 15288 mandates the principle of decision gates and exit criteria; individual programmes select which named reviews to hold and when.

**CSEP Exam Tip:** The exam distinguishes between the ISO 15288 principle of decision gates (which is normative) and named reviews such as SRR/PDR/CDR (which are programme-specific implementations). Know both but understand the hierarchy.

---

## Summary 4: Life Cycle Models

A **life cycle model** is a framework that describes the stages, decision gates, and overall approach used to manage a system's life cycle. ISO/IEC/IEEE 15288 does not prescribe a single life cycle model — it intentionally separates the definition of processes from the selection of a life cycle model. Programmes are expected to select and tailor a model appropriate to their context.

**Sequential model** — Stages are executed largely in order, with each stage substantially completed before the next begins. Clear gates and deliverables characterise this model. It is appropriate when requirements are well-understood and stable, when the technology is mature, or when regulatory frameworks demand strict stage separation (e.g., nuclear, medical devices).

**Iterative model** — The system is progressively refined through multiple successive cycles, each producing a more complete or capable version. Each iteration revisits requirements, design, and verification at increasing levels of fidelity. It is appropriate when requirements are expected to evolve, when stakeholder feedback is essential, or when risk must be managed by building and testing early.

**Concurrent model** — Multiple life cycle stages are conducted simultaneously to compress schedule. For example, Production planning may begin before Development is complete. This model accepts higher risk in exchange for shorter time to delivery, and requires strong configuration control and rigorous change management.

**Evolutionary/Incremental model** — The system is delivered in discrete capability increments. Each increment delivers a usable capability, and the full system emerges across multiple increments. This is common in complex defence and space programmes.

**Agile SE** — Iterative, sprint-based development cycles are embedded within an overarching SE framework. ISO/IEC/IEEE 15288 processes are applied within and across sprints. Agile SE is not the same as Agile software development: the SE layer continues to manage the full system life cycle, interfaces, and system-level V&V even when software components are developed in sprints.

**Life cycle model tailoring** is the adaptation of a standard model to fit the unique characteristics of a programme. Tailoring is expected and encouraged by ISO 15288; blind application of a standard model without tailoring is poor SE practice.

**CSEP Exam Tip:** The exam presents scenarios and asks which life cycle model is most appropriate. Match the scenario's key characteristics (requirements stability, risk tolerance, schedule pressure, regulatory environment) to the model that best fits. The sequential model is not inherently inferior — it is correct for its context.

---

## Summary 5: Processes vs Stages — The Critical Distinction

One of the most heavily tested concepts in the CSEP exam is the distinction between **life cycle stages** and **life cycle processes**. These are fundamentally different constructs.

A **life cycle stage** answers the question "When?" — it is a period in the system's evolution characterised by a particular type of activity. Stages are sequential (even if iterated), bounded by decision gates, and specific to a given system's life cycle.

A **life cycle process** answers the question "What?" — it is a set of interrelated activities with defined inputs, outputs, and outcomes. Processes can be invoked in any applicable stage. The same process (e.g., Verification) may be performed in the Development stage (verifying the design), the Production stage (verifying manufactured instances), and the Support stage (verifying post-maintenance system state).

ISO/IEC/IEEE 15288 defines 30 processes, grouped into four groups:
| Process Group | Count | Examples |
|--------------|-------|---------|
| Technical Processes | 14 | Business/Mission Analysis, Stakeholder Needs Definition, System Requirements Definition, Architecture Definition, Design Definition, System Analysis, Implementation, Integration, Verification, Validation, Transition, Operation, Maintenance, Disposal |
| Technical Management Processes | 8 | Project Planning, Project Assessment & Control, Decision Management, Risk Management, Configuration Management, Information Management, Measurement, Quality Assurance |
| Agreement Processes | 2 | Acquisition, Supply |
| Organisational Project-Enabling Processes | 6 | Life Cycle Model Management, Infrastructure Management, Portfolio Management, Human Resource Management, Quality Management, Knowledge Management |

A frequent CSEP exam trap: candidates confuse the "Development stage" with the act of "developing a system" or a "Development process." ISO 15288 has no single process called "Development" — the work of development is carried out by the Technical Processes (requirements, architecture, design, implementation, integration, verification, validation) invoked within the Development stage and, as applicable, in other stages.

**CSEP Exam Tip:** If a question asks about "what process governs X," look for a named ISO 15288 process. If it asks "at which stage does X occur," match to one of the six stages. These are different questions requiring different answers — never conflate them.

---

## Summary 6: Cost of Change and Life Cycle Thinking

The **cost-of-change curve** (also called the cost-of-correction curve) is one of the central justifications for investing in SE, particularly early-stage SE effort. Research by Barry Boehm (and cited in SEH5) demonstrates that the cost of correcting an error or implementing a change increases exponentially as the life cycle progresses. An error in stakeholder requirements that costs one unit to fix in the Concept Stage may cost 10–100 units to fix in the Development Stage and 100–1,000 units (or more) to fix during Utilisation.

The implication is that SE activities that are most effective in preventing late-stage change — rigorous requirements elicitation and validation, early architecture definition, formal V&V planning — deliver the highest return on investment despite being front-loaded in the earliest stages. This is the **SE value proposition**: by spending more early, you spend far less overall.

**Life Cycle Cost (LCC)** is the total cost of a system across all stages — concept, development, production, utilisation, support, and retirement. LCC includes acquisition cost, operating cost, maintenance cost, and disposal cost. In many systems, acquisition cost represents only 20–30% of total LCC; the remaining 70–80% is incurred in operations and support. This means that design decisions made during Development — which heavily influence operating and support costs — have a disproportionate impact on LCC.

**Total Ownership Cost (TOC)** is a closely related concept, particularly in defence acquisition, capturing all costs borne by the owner/operator across the entire system ownership period.

**CSEP Exam Tip:** Questions on cost of change almost always include a distractor about "reducing cost by starting production early." The correct SE answer is that starting production before requirements and design are mature drives up, not down, total cost because rework is more expensive than getting it right early. Know the cost curve direction — cost increases with life cycle progress — and cite Boehm if asked for the research basis.

---

*Document Version: 1.0 | Created: 2026-04-14 | Source: INCOSE SEH5 Ch2; ISO/IEC/IEEE 15288:2023 §6*
