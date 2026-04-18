# CSEP Study Plan — Week 3: Technical Processes — Part 1A (Business/Mission Analysis → Stakeholder Needs)
**Certification:** INCOSE CSEP (Certified Systems Engineering Professional)
**Primary Reference:** INCOSE Systems Engineering Handbook, 5th Edition (SEH5) — Chapter 3 (§3.1–§3.2 of the Technical Processes)
**Exam Basis:** ISO/IEC/IEEE 15288:2023 §6.4.1 (Business or Mission Analysis) and §6.4.2 (Stakeholder Needs and Requirements Definition)
**Supporting Standard:** ISO/IEC/IEEE 29148:2018 — Requirements Engineering
**Week Theme:** How the "problem space" is defined — from the enterprise mission down to a well-specified set of stakeholder needs and requirements, before the solution is ever designed
**Target:** ~3 hours total study time across 7 days

---

## 🎯 Week 3 Learning Objectives

By the end of Week 3, you should be able to:

1. State the purpose of the **Business or Mission Analysis (BMA)** process using INCOSE SEH5 and ISO/IEC/IEEE 15288 §6.4.1 terminology.
2. State the purpose of the **Stakeholder Needs and Requirements Definition (SN&RD)** process using ISO/IEC/IEEE 15288 §6.4.2 terminology.
3. Name the principal inputs, activities, and outputs of each of these two processes.
4. Distinguish between a **stakeholder need**, a **stakeholder requirement**, and a **system requirement** — a high-frequency CSEP exam topic.
5. Identify who the stakeholders of a system typically are and why **stakeholder identification is itself an SE activity**.
6. Apply the requirements hierarchy (mission → business → stakeholder → system → subsystem) to a realistic scenario.
7. Describe the role of a **Concept of Operations (ConOps)** and an **Operational Concept (OpsCon)** — and distinguish them.
8. Describe common requirements-elicitation techniques (interviews, workshops, observation, use cases, scenarios) and when each is appropriate.
9. Name the characteristics of a "good" requirement per ISO/IEC/IEEE 29148:2018 (necessary, verifiable, unambiguous, etc.) and recognise common requirement defects.
10. Explain the role of **measures of effectiveness (MoEs)** and **measures of performance (MoPs)** in validating stakeholder needs.
11. Cite the ISO/IEC/IEEE 15288 clauses (§6.4.1, §6.4.2) and SEH5 sections that underpin each concept.
12. Apply Week 3's material to recognise CSEP-style questions that probe the problem-space/solution-space boundary (e.g., "is this a stakeholder requirement or a system requirement?").

---

## 📅 Day-by-Day Schedule

---

### Day 1 — Monday | Business or Mission Analysis (BMA) — Purpose and Context
**Estimated Time:** 25 minutes
**SEH5 Coverage:** Chapter 3 — Business or Mission Analysis process
**ISO Coverage:** ISO/IEC/IEEE 15288:2023 §6.4.1

#### Topics to Cover
- The purpose of the BMA process: define the problem, the opportunity, and the solution space at the enterprise or mission level
- Why BMA sits **before** stakeholder requirements — it frames them
- Key inputs: organisational strategy, mission statements, market analysis, enabling-system constraints
- Key outputs: validated business/mission need statement, preliminary stakeholder list, preliminary life cycle concepts, problem/opportunity statement
- The relationship between BMA and portfolio/capability management
- How BMA establishes traceability from enterprise strategy down to system-level work

#### Study Activities
- [ ] Read SEH5 Chapter 3, section on Business or Mission Analysis (§6.4.1 coverage)
- [ ] Write the ISO 15288 §6.4.1 purpose statement from memory; compare to the standard
- [ ] List five possible inputs and five possible outputs of BMA for a hypothetical product or mission you know
- [ ] Review Day 1 Flashcards (Cards 1–8)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Business or Mission Analysis (BMA) | The process that defines the business or mission problem or opportunity, characterises the solution space, and determines potential solution class(es) that could address the problem | ISO 15288 §6.4.1; SEH5 Ch3 |
| Mission | The purpose for which a system is developed or used — what the organisation is trying to achieve | SEH5 Ch3 |
| Problem Statement | A formal articulation of the gap, need, or opportunity that the system is intended to address | SEH5 Ch3 |
| Solution Space | The set of feasible solution classes — conceptual approaches — that could address the business/mission problem | SEH5 Ch3 |
| Preliminary Life Cycle Concept | An early description of how the envisaged system will be acquired, developed, operated, supported, and retired — iteratively refined | SEH5 Ch3 |

#### Self-Check Questions
1. State the ISO 15288 §6.4.1 purpose of the Business or Mission Analysis process in one sentence.
2. Name three inputs and three outputs of the BMA process.
3. Why does BMA precede Stakeholder Needs and Requirements Definition in the ISO 15288 sequence?
4. What is the difference between a "problem" and an "opportunity" in BMA terminology?

---

### Day 2 — Tuesday | BMA in Practice — Activities and Artefacts
**Estimated Time:** 25 minutes
**SEH5 Coverage:** Chapter 3 — BMA activities
**ISO Coverage:** ISO/IEC/IEEE 15288:2023 §6.4.1

#### Topics to Cover
- The five typical BMA activities from ISO 15288 §6.4.1:
  1. Prepare for BMA (plan, identify stakeholders, assemble data)
  2. Define the problem or opportunity space
  3. Characterise the solution space (candidate solution classes)
  4. Evaluate alternative solution classes
  5. Manage the BMA outputs (baselines, traceability, feedback)
- Typical artefacts: mission statement, preliminary ConOps/OpsCon, capability-gap analysis, trade study reports, initial life cycle concept document
- The role of **enterprise architecture** and **portfolio management** as inputs
- Traceability from organisational strategy → mission need → solution class → downstream requirements
- Common BMA pitfalls: solution-first thinking, missing stakeholders, no validation of the mission need

#### Study Activities
- [ ] Read SEH5 Chapter 3 sections on BMA activities and outputs
- [ ] For a system you know (e.g., urban train network, satellite constellation, hospital IT), sketch what each of the five BMA activities would produce
- [ ] Write one example of a BMA artefact for each of: (a) defence mission, (b) commercial product, (c) infrastructure programme
- [ ] Review Day 2 Flashcards (Cards 9–17)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Concept of Operations (ConOps) | An acquirer/user-oriented description of how the envisaged system will be operated in its intended environment, including mission, users, operations, and scenarios | SEH5 Ch3; ISO 29148 §4.2 |
| Operational Concept (OpsCon) | A supplier/system-developer-oriented operational description derived from the ConOps, focusing on how the system itself behaves to support operations | ISO 29148 §4.3 |
| Capability Gap | The difference between the current capability (what the enterprise can do today) and the required capability (what it needs to do) | SEH5 Ch3 |
| Solution Class | A family of conceptual approaches that share common characteristics and could address the identified problem or opportunity | SEH5 Ch3 |
| Trade Study | A structured analytic activity comparing alternative solutions against weighted criteria to support decision-making | SEH5 Ch3 and Ch4 |

#### Self-Check Questions
1. List the five typical activities of the BMA process in order.
2. What is the distinction between a ConOps and an OpsCon, and who writes each?
3. How does a capability gap analysis support the BMA process?
4. Name three common pitfalls when conducting BMA on a new programme.

---

### Day 3 — Wednesday | Stakeholder Needs & Requirements Definition (SN&RD) — Purpose and Context
**Estimated Time:** 25 minutes
**SEH5 Coverage:** Chapter 3 — Stakeholder Needs and Requirements Definition process
**ISO Coverage:** ISO/IEC/IEEE 15288:2023 §6.4.2; ISO/IEC/IEEE 29148:2018 §9

#### Topics to Cover
- The purpose of the SN&RD process: define the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment
- Why SN&RD sits **after** BMA and **before** System Requirements Definition
- Who counts as a **stakeholder** — users, operators, maintainers, acquirers, suppliers, regulators, society, environment
- The distinction between a **stakeholder need** (what the stakeholder wants or requires, often in their language) and a **stakeholder requirement** (the engineering-ready statement of that need, ready to be analysed)
- Key inputs to SN&RD: BMA outputs, stakeholder list, mission statement, applicable policies and constraints
- Key outputs: stakeholder requirements baseline, traceability to business/mission needs, validated ConOps/OpsCon

#### Study Activities
- [ ] Read SEH5 Chapter 3, section on Stakeholder Needs and Requirements Definition
- [ ] Read ISO/IEC/IEEE 29148:2018 Clause 9 (Stakeholder Requirements Definition) if accessible
- [ ] Write a "stakeholder need" and its corresponding "stakeholder requirement" for a scenario you know; note what changed between the two
- [ ] Review Day 3 Flashcards (Cards 18–29)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Stakeholder | An individual or organisation having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations | ISO 15288 §3; SEH5 Ch3 |
| Stakeholder Needs and Requirements Definition Process | The process that defines the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment | ISO 15288 §6.4.2 |
| Stakeholder Need | A statement — often expressed in stakeholder language — of what the stakeholder wants or expects the system to do or be, without specifying implementation | SEH5 Ch3; ISO 29148 §9 |
| Stakeholder Requirement | An engineering-ready statement of a stakeholder need, structured, analysable, and verifiable, ready to drive system requirements | ISO 29148 §9 |
| User | A stakeholder who interacts with the system during its operation to achieve a particular goal | ISO 15288 §3 |

#### Self-Check Questions
1. State the ISO 15288 §6.4.2 purpose of the SN&RD process.
2. What is the difference between a stakeholder need and a stakeholder requirement?
3. Name five different categories of stakeholder for a typical system and give an example of each.
4. What is the role of the ConOps/OpsCon as an input to SN&RD?
5. Why must stakeholder identification happen early — what is the risk of missing a stakeholder?

---

### Day 4 — Thursday | Stakeholder Identification, Elicitation and Analysis
**Estimated Time:** 30 minutes
**SEH5 Coverage:** Chapter 3 — Stakeholder identification and elicitation
**ISO Coverage:** ISO/IEC/IEEE 29148:2018 §9 (Stakeholder Requirements Definition) and §5 (Requirements Fundamentals)

#### Topics to Cover
- Stakeholder identification: methods (role analysis, enterprise mapping, life cycle walk-through) and categories (users, operators, maintainers, acquirers, suppliers, regulators, society, environment)
- Stakeholder analysis: interest, influence, authority — why this matters for prioritisation
- Elicitation techniques:
  - **Interviews** — one-on-one, semi-structured; rich but slow
  - **Workshops** — group consensus-building
  - **Observation** — shadowing users in their environment
  - **Questionnaires** — scale, but low depth
  - **Use cases and scenarios** — structured narrative of system use
  - **Prototyping** — "show me" in place of "tell me"
  - **Document analysis** — extracting needs from existing documents, policies, regulations
- How to analyse and consolidate elicited information — deduplication, conflict resolution, priority weighting
- Bounding scope: what is in and out of scope for the system
- Why elicitation must continue through the life cycle — not a one-off event

#### Study Activities
- [ ] Read SEH5 Chapter 3 sections on stakeholder identification and elicitation techniques
- [ ] Build a stakeholder map for a system you know, categorising by role and by influence/interest (2×2 grid)
- [ ] For each elicitation technique, note one scenario where it is the best choice and one where it is not
- [ ] Draft a use case and a scenario for a simple stakeholder need — note the difference between them
- [ ] Review Day 4 Flashcards (Cards 30–41)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Stakeholder Identification | The activity of systematically identifying all parties with an interest in or influence over the system across its life cycle | SEH5 Ch3 |
| Requirements Elicitation | The process of discovering, capturing, and understanding the needs of stakeholders | ISO 29148 §5 |
| Use Case | A description of a system behaviour initiated by an actor to achieve a specific goal, typically expressed as a sequence of interactions | ISO 29148 §5; SEH5 Ch3 |
| Scenario | A narrative description of a specific sequence of events or interactions involving the system and its environment, used to explore behaviour under particular conditions | SEH5 Ch3 |
| Actor | An entity — human, organisation, or other system — that interacts with the system to achieve a goal | ISO 29148 §5 |
| Measure of Effectiveness (MoE) | A measure from the stakeholder's/operator's perspective of how well a system accomplishes its mission or purpose in the operational environment | SEH5 Ch3 |
| Measure of Performance (MoP) | A measure of a specific system attribute or capability used to assess whether the system meets its performance requirements | SEH5 Ch3 |

#### Self-Check Questions
1. Name six elicitation techniques and give one strength and one weakness of each.
2. What is the difference between a use case and a scenario?
3. Why is it dangerous to treat elicitation as a one-off activity at the start of the programme?
4. Define Measure of Effectiveness (MoE) and Measure of Performance (MoP), and explain how they relate to validation.
5. Who is usually responsible for resolving conflicts between stakeholder inputs?

---

### Day 5 — Friday | The Requirements Hierarchy & Characteristics of a "Good" Requirement
**Estimated Time:** 30 minutes
**SEH5 Coverage:** Chapter 3 — Requirements characteristics; Chapter 4 cross-reference
**ISO Coverage:** ISO/IEC/IEEE 29148:2018 §5.2 (Characteristics of good requirements)

#### Topics to Cover
- The requirements hierarchy (top-down):
  1. Business/Mission need
  2. Stakeholder need
  3. **Stakeholder requirement** (SN&RD output)
  4. **System requirement** (System Requirements Definition output — Week 4)
  5. Subsystem / element requirement
  6. Component / implementation requirement
- Why each level exists and how traceability flows down and up the hierarchy
- Characteristics of a well-formed requirement per ISO/IEC/IEEE 29148:2018:
  - **Necessary** — essential; no gratuitous requirements
  - **Appropriate** — at the right level of detail
  - **Unambiguous** — only one reasonable interpretation
  - **Complete** — nothing important missing
  - **Singular** — one requirement per statement
  - **Feasible** — technically and economically achievable
  - **Verifiable** — can be demonstrated by test, analysis, inspection, or demonstration
  - **Correct** — accurately reflects the need
  - **Conforming** — consistent with set conventions
- Common requirement defects to watch for: vague ("user-friendly"), compound ("and", "or"), implementation-biased ("shall use MySQL"), untestable, missing rationale
- The role of **rationale** and **source/trace attributes** for each requirement

#### Study Activities
- [ ] Read SEH5 Chapter 3 section on requirements characteristics
- [ ] Take five requirements from a real document (any source) and classify each against the 9 ISO 29148 characteristics
- [ ] Rewrite one poor requirement into a well-formed requirement
- [ ] Review Day 5 Flashcards (Cards 42–51)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Requirement | A statement that identifies a product or process operational, functional, or design characteristic or constraint, which is unambiguous, verifiable, and deemed necessary for product or process acceptability | ISO 29148 §3.1; SEH5 Ch3 |
| Verifiable (requirement characteristic) | A characteristic such that compliance of the product or process with the requirement can be demonstrated by one of the four verification methods — test, analysis, inspection, or demonstration | ISO 29148 §5.2 |
| Unambiguous (requirement characteristic) | The requirement is stated in such a way that it can have only one interpretation | ISO 29148 §5.2 |
| Traceability | The ability to follow the life of a requirement in both a forward and a backward direction — from origin, through development, to deployment and use | ISO 29148 §6 |
| Rationale | The reason a requirement exists — the justification linking it back to a higher-level need | ISO 29148 §5.2 |

#### Self-Check Questions
1. List the 9 ISO 29148 characteristics of a well-formed requirement.
2. Name the four verification methods used to demonstrate a requirement is met.
3. Give an example of a compound requirement and rewrite it as two singular requirements.
4. Why should requirements specify *what* rather than *how*?
5. What is the purpose of a requirement's rationale attribute?

---

### Day 6 — Saturday | Validation, MoEs, and Baselining Stakeholder Requirements
**Estimated Time:** 25 minutes
**SEH5 Coverage:** Chapter 3 — Validation of stakeholder requirements; baselining
**ISO Coverage:** ISO/IEC/IEEE 15288:2023 §6.4.2 (outputs) and §6.4.11 (Validation process)

#### Topics to Cover
- **Validation of stakeholder requirements** — confirming with stakeholders that the requirements correctly express their needs **before** engineering effort is sunk into system requirements
- The critical CSEP distinction between **verification** ("did we build the thing right?") and **validation** ("did we build the right thing?") — previewed here, covered in depth in Week 6
- The role of **Measures of Effectiveness (MoEs)** in defining what "successful" means in the stakeholder's terms
- The role of **Measures of Performance (MoPs)** in translating MoEs into measurable system behaviours
- Baselining: the stakeholder requirements baseline is the first formally controlled artefact in the Technical Processes chain
- Change control: once baselined, changes require approval — typically via Configuration Management (Technical Management Processes, Week 7)
- Handoff to System Requirements Definition — what the next process expects to receive

#### Study Activities
- [ ] Read SEH5 Chapter 3 section on validation of stakeholder requirements
- [ ] For a system you know, define one MoE and two supporting MoPs
- [ ] Write a 3-sentence explanation of why baselining stakeholder requirements is a CSEP high-value concept
- [ ] Review Day 6 Flashcards (Cards 52–55)

#### Key Definitions to Memorise
| Term | Definition | Source |
|------|-----------|--------|
| Validation (requirements) | Confirmation, through the provision of objective evidence, that the requirements for a specific intended use or application have been fulfilled | ISO 15288 §3; SEH5 Ch3 |
| Verification (contrast only — detail in Week 6) | Confirmation, through the provision of objective evidence, that specified requirements have been fulfilled | ISO 15288 §3 |
| Stakeholder Requirements Baseline | The formally agreed and version-controlled set of stakeholder requirements that serves as the authoritative input to System Requirements Definition | SEH5 Ch3 |
| Measure of Effectiveness (MoE) | A stakeholder/mission-oriented measure of how well the system accomplishes its intended purpose in the operational environment | SEH5 Ch3 |
| Measure of Performance (MoP) | A system-oriented measure of a particular system attribute, often derived from an MoE and used in verification | SEH5 Ch3 |

#### Self-Check Questions
1. Define validation using the ISO 15288 §3 wording. How does this differ from verification?
2. What is an MoE, and how does it relate to an MoP?
3. What does "baseline" mean in the context of stakeholder requirements, and why is it important?
4. What input does the next process (System Requirements Definition, Week 4) expect from SN&RD?

---

### Day 7 — Sunday | Review, Brain Dump & Week 3 Self-Assessment
**Estimated Time:** 30 minutes

#### Review Activities
- [ ] Review all Day 1–6 self-check questions without notes; check answers in `Week_03_Assessment_Answers.md`
- [ ] Re-read any definition tables where you hesitated
- [ ] Re-attempt any flashcards marked ❌ or 🔄 from earlier in the week
- [ ] Attempt 10 of the 20 practice questions in `Week_03_Practice_Questions.md`

#### Brain Dump (write from memory, no notes)
1. State the purpose of BMA and SN&RD in one sentence each, as per ISO 15288 §6.4.1 and §6.4.2.
2. List the five typical BMA activities.
3. Name six elicitation techniques.
4. List the 9 ISO 29148 characteristics of a good requirement.
5. Draw the requirements hierarchy from business need to component requirement (6 levels).
6. Give one MoE and two MoPs for a system of your choice.
7. State the difference between a stakeholder need and a stakeholder requirement in two sentences.

#### Week 3 Competency Checklist (self-rate 1–5)
| Competency | Self-Rating (1–5) |
|-----------|-----------------|
| Can state the ISO 15288 §6.4.1 purpose of BMA verbatim | |
| Can state the ISO 15288 §6.4.2 purpose of SN&RD verbatim | |
| Can distinguish stakeholder need vs stakeholder requirement vs system requirement | |
| Can list at least six elicitation techniques with strengths/weaknesses | |
| Can list the 9 ISO 29148 requirement characteristics | |
| Can define MoE and MoP and give an example of each | |
| Can distinguish ConOps from OpsCon | |
| Can draw the 6-level requirements hierarchy from memory | |

---

## 📊 Week 3 Study Hours Summary

| Day | Topic | Est. Time |
|-----|-------|----------|
| Day 1 (Mon) | BMA — Purpose and Context | 25 min |
| Day 2 (Tue) | BMA — Activities and Artefacts | 25 min |
| Day 3 (Wed) | SN&RD — Purpose and Context | 25 min |
| Day 4 (Thu) | Stakeholder Identification, Elicitation & Analysis | 30 min |
| Day 5 (Fri) | Requirements Hierarchy & Characteristics | 30 min |
| Day 6 (Sat) | Validation, MoEs & Baselining | 25 min |
| Day 7 (Sun) | Review & Brain Dump | 30 min |
| **Total** | | **~3 hours (+10% buffer)** |

---

## 🔭 Upcoming Preview — Week 4 Topics

Week 4 continues **Technical Processes — Part 1B**: the next two technical processes that take the Week 3 stakeholder requirements baseline forward into a defined architecture.

Key topics ahead:
- **System Requirements Definition Process** (ISO 15288 §6.4.3) — transforming stakeholder requirements into a system-oriented, engineering-tractable specification
- **Architecture Definition Process** (ISO 15288 §6.4.4) — defining alternative architectures and selecting the one that best addresses system requirements
- Functional, logical, and physical architecture views
- ISO/IEC/IEEE 42010:2022 — Architecture description
- The architecture–design distinction (a classic CSEP exam trap)

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
