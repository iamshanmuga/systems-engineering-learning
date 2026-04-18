# CSEP Week 3 — Assessment Answer Key: Business/Mission Analysis & Stakeholder Needs
**Purpose:** Reference answers for Day 1–6 self-check questions and Day 7 brain dump
**Use:** Review after attempting your own answers; target 25–35 minutes for full review

---

## Day 1 Self-Check Answers — Why BMA Exists

**Q1. State the ISO 15288 §6.4.1 purpose of the Business or Mission Analysis process in one sentence.**
Model answer: The purpose of BMA is to define the business or mission problem or opportunity, characterise the solution space, and determine potential solution class(es) that could address the problem — thereby justifying that a system is an appropriate response.
*Cite: ISO 15288 §6.4.1; SEH5 Ch3*

**Q2. Name three inputs and three outputs of the BMA process.**
Model answer:
- **Inputs:** enterprise strategy and mission statements; market, regulatory, or capability gap analysis; stakeholder expectations and portfolio management direction.
- **Outputs:** preliminary ConOps (and sometimes OpsCon); business/mission requirements and Measures of Effectiveness (MoEs); preferred solution class(es) and justification to proceed (i.e., a business case).
Other valid inputs include existing capability assessments and applicable policies; other valid outputs include the preliminary life cycle concept and stakeholder identification input to SN&RD.
*Cite: ISO 15288 §6.4.1; SEH5 Ch3*

**Q3. Why does BMA precede Stakeholder Needs and Requirements Definition in the ISO 15288 sequence?**
Model answer: BMA establishes that a system is the right response to the business/mission problem *before* engineering effort is committed. Its outputs — preliminary ConOps, business requirements, MoEs, preferred solution class, and stakeholder identification — are the inputs SN&RD needs to define stakeholder needs and requirements coherently. Starting SN&RD without BMA risks defining stakeholder requirements for the wrong problem or the wrong solution class, anchoring all downstream engineering to a flawed premise.
*Cite: ISO 15288 §6.4.1 and §6.4.2; SEH5 Ch3*

**Q4. What is the difference between a "problem" and an "opportunity" in BMA terminology?**
Model answer: A **problem** is a gap between current capability and required capability — something is broken, missing, or underperforming and must be addressed. An **opportunity** is a prospective benefit that could be captured by a new or modified capability — nothing is broken, but value could be created. Both are legitimate drivers for BMA; the analysis activities are similar but the framing affects acquirer motivation, stakeholder identification, and the scope of candidate solution classes.
*Cite: SEH5 Ch3*

---

## Day 2 Self-Check Answers — BMA in Practice: Activities and Artefacts

**Q1. List the five typical activities of the BMA process in order.**
Model answer:
1. **Prepare for BMA** — plan the analysis, identify stakeholders, assemble data sources, agree the approach.
2. **Define the problem or opportunity space** — articulate the mission need, capability gap, or opportunity.
3. **Characterise the solution space** — identify candidate solution classes (families of approaches), not specific designs.
4. **Evaluate alternative solution classes** — trade-study candidates against MoEs and programme criteria.
5. **Manage the BMA outputs** — baseline artefacts, establish traceability, feed downstream SN&RD.
*Cite: ISO 15288 §6.4.1.3; SEH5 Ch3*

**Q2. What is the distinction between a ConOps and an OpsCon, and who writes each?**
Model answer: The **ConOps** (ISO 29148 §4.2) takes the acquirer/user viewpoint — describing *how* the envisaged capability will be used in the operational environment: mission, users, operations, scenarios. It is typically authored by (or for) the acquirer. The **OpsCon** (ISO 29148 §4.3) takes the system/developer viewpoint — describing the system's operational characteristics, modes, and interactions. It is typically authored by (or for) the supplier, derived from the ConOps. The two are complementary, not duplicates.
*Cite: ISO 29148 §4.2 and §4.3; SEH5 Ch3*

**Q3. How does a capability gap analysis support the BMA process?**
Model answer: A capability gap analysis quantifies the difference between what the enterprise can do today (current capability) and what it needs to do (required capability). In BMA, the gap analysis sharpens the problem statement, informs the MoEs, and anchors the evaluation of candidate solution classes — each candidate is assessed on how well it closes the identified gap. Without a gap analysis, BMA becomes hand-wavy about *why* a system is needed.
*Cite: SEH5 Ch3*

**Q4. Name three common pitfalls when conducting BMA on a new programme.**
Model answer:
- **Solution-first thinking** — the programme has already "decided" on a solution (e.g., "we need a new logistics platform") and treats BMA as justification theatre rather than genuine analysis.
- **Missing stakeholders** — adversarial parties, regulators, disposers, or indirect stakeholders are overlooked; needs and constraints surface painfully in later stages.
- **No validation of the mission need** — the stated mission is assumed rather than tested against enterprise strategy or stakeholder consensus.
Other valid pitfalls: skipping the "do nothing" baseline in trade studies; optimising on acquisition cost rather than life cycle cost; treating BMA as a one-off document rather than a process that iterates as information matures.
*Cite: SEH5 Ch3*

---

## Day 3 Self-Check Answers — SN&RD Purpose and Context

**Q1. State the ISO 15288 §6.4.2 purpose of the SN&RD process.**
Model answer: The purpose of SN&RD is to define the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment. It transforms stakeholder needs (often expressed in stakeholder language) into stakeholder requirements that are unambiguous, verifiable, and ready to drive System Requirements Definition.
*Cite: ISO 15288 §6.4.2; ISO 29148 §9*

**Q2. What is the difference between a stakeholder need and a stakeholder requirement?**
Model answer: A **stakeholder need** is a statement — typically in the stakeholder's own language — of what they want or expect from the system, often aspirational, ambiguous, or implementation-unspecified. A **stakeholder requirement** is the engineered statement of that need: structured, unambiguous, verifiable, and singular — ready to anchor downstream system requirements. SN&RD is the process that performs that transformation.
*Cite: ISO 29148 §9; SEH5 Ch3*

**Q3. Name five different categories of stakeholder for a typical system and give an example of each.**
Model answer (examples):
- **User** — a call-centre agent operating a customer service system.
- **Operator** — a train driver operating a rail signalling system.
- **Maintainer** — a field engineer servicing a wind turbine.
- **Acquirer** — the transport authority procuring a new ticketing system.
- **Regulator** — the aviation authority certifying an airborne system.
Other valid categories: supplier, disposer, society/environment, adversarial (cyber attacker, threat actor), enterprise owner.
*Cite: ISO 15288 §3; SEH5 Ch3*

**Q4. What is the role of the ConOps/OpsCon as an input to SN&RD?**
Model answer: The ConOps (and, if produced, OpsCon) from BMA anchors SN&RD in the operational context. It tells SN&RD *who* uses the system, *how* it is used, and *under what conditions* — so that elicited needs can be interpreted correctly and stakeholder requirements can be shaped to fit the operational reality. Without the ConOps, SN&RD risks producing requirements that are technically sound but operationally misaligned.
*Cite: ISO 29148 §4.2; SEH5 Ch3*

**Q5. Why must stakeholder identification happen early — what is the risk of missing a stakeholder?**
Model answer: A missed stakeholder at the start of SN&RD means a missed need set; the resulting stakeholder requirements baseline will be incomplete. Surfaced later — in Development, Production, or Utilisation — that stakeholder's needs force costly rework (recall the cost-of-change curve). Adversarial stakeholders and regulators are the most common omissions and create the most expensive late surprises (e.g., a safety regulator invoked in late Development can trigger full redesigns). Early, comprehensive stakeholder identification is a high-leverage SE activity.
*Cite: SEH5 Ch3; ISO 15288 §6.4.2*

---

## Day 4 Self-Check Answers — Stakeholder Identification, Elicitation and Analysis

**Q1. Name six elicitation techniques and give one strength and one weakness of each.**
Model answer:
- **Interviews** — Strength: rich, tacit insights; Weakness: time-consuming, susceptible to interviewer bias.
- **Workshops** — Strength: surface disagreements and build consensus; Weakness: quiet voices get overshadowed, groupthink risk.
- **Observation** — Strength: captures what stakeholders cannot articulate; Weakness: slow and scope-limited.
- **Questionnaires** — Strength: scales to many stakeholders; Weakness: shallow, loses nuance.
- **Use cases / scenarios** — Strength: structures behaviour in concrete terms; Weakness: can bias toward the scenarios chosen.
- **Prototyping** — Strength: feedback on something tangible; Weakness: anchors thinking to the prototype design.
Other valid techniques: document analysis (strength: leverages existing artefacts; weakness: outdated or context-free), brainstorming, focus groups.
*Cite: SEH5 Ch3; ISO 29148 §5; INCOSE GtWR*

**Q2. What is the difference between a use case and a scenario?**
Model answer: A **use case** is a structured description of a system behaviour initiated by an actor to achieve a specific goal — typically expressed as a sequence of interactions with pre-conditions, main flow, and alternate flows. A **scenario** is a narrative description of a specific sequence of events or interactions, usually exploring a particular condition or pathway. Loosely: a scenario is an instance of a use case (one path through it, often under specific conditions). Use cases are more formal and reusable; scenarios are more exploratory and concrete.
*Cite: ISO 29148 §5; SEH5 Ch3*

**Q3. Why is it dangerous to treat elicitation as a one-off activity at the start of the programme?**
Model answer: Stakeholders, operational environment, technology, regulation, and strategy all evolve. A one-off elicitation produces a snapshot of needs that becomes progressively stale as the programme advances. Late-surfacing needs then hit the system at the point of highest change cost (Boehm's cost-of-change curve). SE practice treats elicitation as continuous — revisited at stage gates, at major stakeholder changes, and when external context shifts.
*Cite: SEH5 Ch3*

**Q4. Define Measure of Effectiveness (MoE) and Measure of Performance (MoP), and explain how they relate to validation.**
Model answer: An **MoE** is a mission/stakeholder-perspective measure of how well the system accomplishes its intended purpose in the operational environment (e.g., "mission success rate ≥ 95% per monthly cycle"). An **MoP** is a system-perspective measure of a specific system attribute, usually derived from an MoE and used in verification (e.g., "throughput ≥ 500 transactions/sec"). Relation to validation: MoEs typically anchor validation (did we build the right system?), because they describe stakeholder success; MoPs anchor verification (did we build the system right?), because they describe specified system behaviour. The chain runs MoE → MoP → system requirement → verification.
*Cite: SEH5 Ch3; ISO 15288 §3*

**Q5. Who is usually responsible for resolving conflicts between stakeholder inputs?**
Model answer: The **systems engineer** (or the responsible SE lead) is the custodian of the consolidated stakeholder requirements, supported by the programme manager and, where authority is contested, the **acquirer**. Conflict resolution techniques include structured trade-off analysis, escalation to the acquirer's representative, and — for significant disputes — invoking the Technical Management Processes (Decision Management, ISO 15288 §6.3.4) to document the decision rationale. The systems engineer does not decide in isolation; the acquirer holds the governance authority for irreconcilable conflicts.
*Cite: ISO 15288 §6.3.4 and §6.4.2; SEH5 Ch3*

---

## Day 5 Self-Check Answers — Requirements Hierarchy and Characteristics

**Q1. List the 9 ISO 29148 characteristics of a well-formed requirement.**
Model answer:
1. **Necessary** — essential to meeting a stakeholder need; removing it would leave the need unmet.
2. **Appropriate** — at the correct level and scope for the artefact; not too detailed, not too abstract.
3. **Unambiguous** — admits only one reasonable interpretation.
4. **Complete** — self-contained; no missing caveats or conditions.
5. **Singular** — one requirement per statement; no compound "and"/"or".
6. **Feasible** — technically and economically achievable within cost, schedule, and risk.
7. **Verifiable** — demonstrable by test, analysis, inspection, or demonstration.
8. **Correct** — accurately reflects the stakeholder need or parent requirement.
9. **Conforming** — consistent with the programme's approved format, style, and templates.
*Cite: ISO 29148 §5.2*

**Q2. Name the four verification methods used to demonstrate a requirement is met.**
Model answer: **Test** (operate under controlled conditions and measure), **Analysis** (mathematical or model-based proof), **Inspection** (examine documentation or physical properties without operation), **Demonstration** (show the capability operationally, typically observed). Mnemonic: **TAID**.
*Cite: ISO 29148; SEH5 Ch3*

**Q3. Give an example of a compound requirement and rewrite it as two singular requirements.**
Model answer:
- **Compound (bad):** "The system shall log all user actions and shall alert the security team within 60 seconds of a suspicious event."
- **Singular rewrite 1:** "The system shall record every user action in an append-only audit log within 1 second of the action occurring."
- **Singular rewrite 2:** "The system shall notify the security team within 60 seconds of classifying a user action as suspicious per the approved threat model."
The compound form fails the Singular characteristic (ISO 29148 §5.2); splitting allows each to be verified independently and traced separately.
*Cite: ISO 29148 §5.2*

**Q4. Why should requirements specify *what* rather than *how*?**
Model answer: Specifying *what* keeps the requirement at the correct level — describing the need or behaviour to be achieved, without constraining the supplier's design choices. Specifying *how* ("shall use MySQL", "shall be implemented in Java") is implementation bias: it over-constrains the solution, forecloses potentially better designs, and conflates Stakeholder Needs (problem) with System Design (solution). The "how" belongs to the Architecture and Design Definition processes, not SN&RD. Exception: when a design constraint is genuinely required by stakeholders (e.g., regulatory mandate, interface compatibility), it may legitimately appear as a constraint requirement — but must be justified.
*Cite: SEH5 Ch3; ISO 29148 §5*

**Q5. What is the purpose of a requirement's rationale attribute?**
Model answer: The rationale records *why* a requirement exists — the justification, the source, the stakeholder concern, or the constraint driving it. It enables three things: (1) **impact analysis** — when changes occur, rationale shows what the requirement was protecting; (2) **stakeholder review** — stakeholders can validate that the requirement correctly captures their intent; (3) **tailoring and relaxation** — over a programme's life, when schedule or cost pressure forces requirement changes, the rationale lets the engineer judge whether a change is safe. A requirement without rationale is undefendable under pressure.
*Cite: ISO 29148 §5.2; INCOSE GtWR*

---

## Day 6 Self-Check Answers — Validation, MoEs, and Baselining

**Q1. Define validation using the ISO 15288 §3 wording. How does this differ from verification?**
Model answer:
- **Validation** (ISO 15288 §3): confirmation, through the provision of objective evidence, that the requirements for a specific intended use or application have been fulfilled.
- **Verification** (ISO 15288 §3): confirmation, through the provision of objective evidence, that specified requirements have been fulfilled.
The difference: **verification** checks the system against *specified requirements* — did we build the system right. **Validation** checks the system against *stakeholder needs and intended use* — did we build the right system. A system can pass verification and fail validation if the requirements did not correctly capture the stakeholder's intent.
*Cite: ISO 15288 §3*

**Q2. What is an MoE, and how does it relate to an MoP?**
Model answer: An **MoE** is a mission/stakeholder-perspective measure of how well the system accomplishes its intended purpose in the operational environment. An **MoP** is a system-perspective measure of a specific system attribute or behaviour. MoPs are typically *derived from* MoEs during SN&RD and System Requirements Definition — they are the system-level measurable translations of mission-level outcomes. One MoE may be supported by multiple MoPs. MoPs feed verification; MoEs feed validation.
*Cite: SEH5 Ch3*

**Q3. What does "baseline" mean in the context of stakeholder requirements, and why is it important?**
Model answer: A **baseline** is a formally approved, version-controlled set of artefacts placed under configuration control. The **stakeholder requirements baseline** is the first formally controlled artefact in the Technical Processes chain — produced at the close of SN&RD after stakeholder review and approval. It is important because: (1) it fixes the contract between acquirer and supplier; (2) it is the authoritative input to System Requirements Definition; (3) it becomes the reference against which change impacts and programme progress are measured. Without a baseline, there is no shared definition of "done" for SN&RD and no stable foundation for downstream work.
*Cite: SEH5 Ch3; ISO 15288 §6.4.2*

**Q4. What input does the next process (System Requirements Definition, Week 4) expect from SN&RD?**
Model answer: System Requirements Definition expects from SN&RD: (a) the **stakeholder requirements baseline** (the authoritative set of stakeholder requirements); (b) **traceability** to business/mission needs and source stakeholders; (c) **validated ConOps/OpsCon** providing operational context; (d) **MoEs and MoPs** that anchor what "success" means; (e) **validation criteria** for each stakeholder requirement. With these inputs, System Requirements Definition can analyse the stakeholder requirements and derive the system requirements that will shape Architecture and Design.
*Cite: ISO 15288 §6.4.2 (outputs) and §6.4.3 (inputs); SEH5 Ch3*

---

## Day 7 Brain Dump — Model Answers

**1. State the purpose of BMA and SN&RD in one sentence each, as per ISO 15288 §6.4.1 and §6.4.2.**
- **BMA (§6.4.1):** Define the business or mission problem or opportunity, characterise the solution space, and determine potential solution class(es) — justifying that a system is an appropriate response.
- **SN&RD (§6.4.2):** Define the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment.

**2. List the five typical BMA activities.**
Prepare for BMA → Define the problem/opportunity space → Characterise the solution space → Evaluate alternative solution classes → Manage the BMA outputs.

**3. Name six elicitation techniques.**
Interviews; Workshops; Observation; Questionnaires; Use cases and scenarios; Prototyping. (Also valid: document analysis, brainstorming, focus groups.)

**4. List the 9 ISO 29148 characteristics of a good requirement.**
Necessary, Appropriate, Unambiguous, Complete, Singular, Feasible, Verifiable, Correct, Conforming.

**5. Draw the requirements hierarchy from business need to component requirement (6 levels).**

| Level | Type | Produced by (process) |
|-------|------|----------------------|
| 1 | Business / mission need | BMA (§6.4.1) |
| 2 | Stakeholder need | SN&RD (§6.4.2) |
| 3 | Stakeholder requirement | SN&RD (§6.4.2) |
| 4 | System requirement | System Requirements Definition (§6.4.3) — Week 4 |
| 5 | Subsystem / element requirement | Architecture and Design Definition (§6.4.4 / §6.4.5) |
| 6 | Component / implementation requirement | Architecture and Design Definition / Implementation |

**6. Give one MoE and two MoPs for a system of your choice.**
Example (urban bus fleet management system):
- **MoE:** On-time performance rate ≥ 92% for scheduled services measured over a rolling monthly window.
- **MoP 1:** GPS position update latency ≤ 5 seconds at the 95th percentile across the fleet.
- **MoP 2:** Arrival prediction accuracy within ±60 seconds for 90% of stop arrivals.

**7. State the difference between a stakeholder need and a stakeholder requirement in two sentences.**
A stakeholder need is a statement — often in the stakeholder's own language — of what the stakeholder wants or expects from the system; it may be aspirational, ambiguous, or implementation-vague. A stakeholder requirement is the engineered statement of that need, structured unambiguously, verifiably, and singularly so that it can drive System Requirements Definition.

---

## Competency Rubric — Week 3

| Competency | 3/5 Mastery | 5/5 Mastery |
|-----------|-------------|-------------|
| State the ISO 15288 §6.4.1 purpose of BMA | Can give a rough paraphrase with prompting | Can state verbatim from memory using ISO 15288 wording |
| State the ISO 15288 §6.4.2 purpose of SN&RD | Can give a rough paraphrase with prompting | Can state verbatim from memory using ISO 15288 wording |
| Distinguish stakeholder need vs stakeholder requirement vs system requirement | Can explain with an example | Can spontaneously walk through all three levels with the transformations between them |
| List at least six elicitation techniques with strengths/weaknesses | Can name six techniques | Can name eight+ techniques and state one scenario where each is the best choice and one where it is not |
| List the 9 ISO 29148 requirement characteristics | Can name seven or more | Can name all nine and classify a defective requirement against the violated characteristic(s) |
| Define MoE and MoP and give an example of each | Can define both and give examples | Can explain the MoE→MoP chain and how each ties to validation vs verification |
| Distinguish ConOps from OpsCon | Can state that they take different viewpoints | Can name the ISO 29148 clauses (§4.2 / §4.3), viewpoint, audience, and timing for each |
| Draw the 6-level requirements hierarchy from memory | Draws four or five levels correctly | Draws all six levels and names the ISO 15288 process that produces each |

---

## Next Steps if You Scored Below 70%

- **BMA purpose unclear?** Re-read SEH5 Chapter 3 BMA section and ISO 15288 §6.4.1; use Day 1 Flashcards (Cards 1–8).
- **BMA activities hazy?** Re-read Topic Summary 2 and Day 2 Flashcards (Cards 9–17); sketch the five activities for a system you know.
- **SN&RD purpose not solid?** Re-read SEH5 Chapter 3 SN&RD section and ISO 15288 §6.4.2; use Day 3 Flashcards (Cards 18–29).
- **Elicitation techniques missing?** Re-read Topic Summary 4 and Day 4 Flashcards (Cards 30–41); write one scenario per technique.
- **9 characteristics not memorised?** Use the **NAU CSF VCC** ordering (Necessary, Appropriate, Unambiguous, Complete, Singular, Feasible, Verifiable, Correct, Conforming); drill Day 5 Flashcards (Cards 42–51).
- **MoE/MoP blurred?** Re-read Topic Summary 7 and Day 6 Flashcards (Cards 52–55); define one MoE with two supporting MoPs for three different systems.
- **ConOps vs OpsCon confused?** Re-read ISO 29148 §4.2 and §4.3 directly; practise stating the viewpoint, audience, and timing of each aloud until automatic.
- **Requirements hierarchy wobbly?** Draw the 6-level table three times from memory; annotate which ISO 15288 clause produces each level.

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
