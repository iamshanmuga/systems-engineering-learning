# CSEP Week 3 — Flashcard Deck
**Topic:** Technical Processes — Part 1A (Business/Mission Analysis → Stakeholder Needs & Requirements Definition)
**Format:** Question (Front) | Answer (Back)
**Total Cards:** 55 | **Sections:** 3 sections mapped to the week's sub-topics
**How to use:** Cover the Answer column; read the Question; say your answer aloud; then check.
Mark cards: ✅ Known | 🔄 Review | ❌ Re-study

---

## 📦 Section 1 — Business or Mission Analysis (Cards 1–17)
*Covers: Days 1 & 2 — BMA purpose, position, activities, artefacts, ConOps vs OpsCon*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 1 | State the ISO/IEC/IEEE 15288 §6.4.1 purpose of the Business or Mission Analysis (BMA) process. | To define the business or mission problem or opportunity, characterise the solution space, and determine potential solution class(es) that could address the problem. (ISO 15288 §6.4.1) |
| 2 | Where does BMA sit among the fourteen ISO 15288 Technical Processes? | BMA is the first Technical Process. It precedes Stakeholder Needs and Requirements Definition (§6.4.2), which precedes System Requirements Definition (§6.4.3). |
| 3 | Name three typical inputs to the BMA process. | Organisational strategy / mission statement; market or mission analysis; enterprise architecture or portfolio decisions; prior system performance data; regulatory or policy constraints. (Any three.) |
| 4 | Name three typical outputs of the BMA process. | Validated problem/opportunity statement; preliminary stakeholder list; preliminary life cycle concepts; candidate solution classes; preliminary ConOps. (Any three.) |
| 5 | Why does BMA precede Stakeholder Needs and Requirements Definition? | BMA defines the problem space — what problem is being solved, for whom, and with what solution classes — before stakeholder requirements are written against that problem. Without BMA, stakeholder requirements are written against an unvalidated problem. |
| 6 | List the five typical activity clusters of the BMA process. | (1) Prepare for BMA; (2) Define the problem or opportunity space; (3) Characterise the solution space; (4) Evaluate alternative solution classes; (5) Manage the BMA results. (ISO 15288 §6.4.1) |
| 7 | Define: Problem Statement (BMA context) | A formal articulation of the gap, need, or opportunity that the system is intended to address. (SEH5 Ch3) |
| 8 | Define: Solution Space | The set of feasible solution classes — conceptual approaches — that could address the business/mission problem identified during BMA. (SEH5 Ch3) |
| 9 | Define: Solution Class | A family of conceptual approaches sharing common characteristics that could address the identified problem (e.g., "airborne surveillance" vs "satellite constellation" vs "ground-based radar"). (SEH5 Ch3) |
| 10 | Define: Preliminary Life Cycle Concept | An early description of how the envisaged system will be acquired, developed, operated, supported, and retired — iteratively refined. (SEH5 Ch3) |
| 11 | Define: Concept of Operations (ConOps) | An acquirer/user-oriented description of how the envisaged system will be operated in its intended environment — mission, users, operations, scenarios, constraints. (ISO 29148 §4.2; SEH5 Ch3) |
| 12 | Define: Operational Concept (OpsCon) | A supplier/system-developer-oriented operational description derived from the ConOps, describing how the system itself behaves to support operations. (ISO 29148 §4.3) |
| 13 | What is the difference between a ConOps and an OpsCon, and who typically writes each? | ConOps is acquirer-oriented (written by or with the acquirer, describing user-facing mission use); OpsCon is supplier-oriented (written by the system developer, describing how the system supports the ConOps). Different perspectives, different audiences. |
| 14 | Define: Capability Gap | The difference between the current capability (what the enterprise can do today) and the required capability (what it needs to do). Supports BMA by identifying the problem to solve. (SEH5 Ch3) |
| 15 | What role does a trade study play in BMA? | Trade studies compare alternative solution classes against weighted criteria (cost, schedule, risk, mission effectiveness, feasibility) to support the BMA decision on which class(es) to progress. (SEH5 Ch3 and Ch4) |
| 16 | Name three common BMA pitfalls. | (1) Solution-first thinking — jumping to a favoured solution before defining the problem; (2) missing stakeholders (especially regulators, maintainers, society); (3) skipping validation of the mission need, treating it as fixed. |
| 17 | Is BMA a one-off activity or iterative? | Iterative. Initial passes may be shallow — sufficient to authorise investment — with successive passes becoming more rigorous as the programme commits to a solution class. (SEH5 Ch3) |

---

## 📦 Section 2 — Stakeholder Needs & Requirements Definition (Cards 18–41)
*Covers: Days 3 & 4 — SN&RD purpose, stakeholders, elicitation techniques*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 18 | State the ISO/IEC/IEEE 15288 §6.4.2 purpose of the Stakeholder Needs and Requirements Definition (SN&RD) process. | To define the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment. (ISO 15288 §6.4.2) |
| 19 | Define: Stakeholder | An individual or organisation having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations. (ISO 15288 §3) |
| 20 | Name six categories of stakeholder typically considered in SN&RD. | Users, operators, maintainers, acquirers, suppliers, regulators, society/environment, enabling-system owners. (Any six.) |
| 21 | Define: User | A stakeholder who interacts with the system during its operation to achieve a particular goal. (ISO 15288 §3) |
| 22 | What is the difference between a stakeholder need and a stakeholder requirement? | A stakeholder **need** is expressed in stakeholder language — what the stakeholder wants — without specifying implementation. A stakeholder **requirement** is the engineering-ready statement of that need: structured, analysable, and verifiable. |
| 23 | What is the difference between a stakeholder requirement and a system requirement? | A stakeholder requirement captures *what the stakeholder needs* in stakeholder-facing terms (capability-oriented). A system requirement specifies *what the system must do or be* in engineering-facing terms (behaviour/attribute-oriented). System requirements derive from stakeholder requirements in the next process (§6.4.3). |
| 24 | Name three principal outputs of the SN&RD process. | (1) Validated stakeholder needs; (2) validated stakeholder requirements; (3) stakeholder requirements baseline under configuration control. (ISO 15288 §6.4.2) |
| 25 | Why is stakeholder identification a formal SE activity, not just a "list the obvious people" task? | Missing a stakeholder at this stage is one of the most expensive SE errors — unidentified stakeholders surface later with requirements the system cannot accommodate, forcing costly redesign. SE must systematically cover the full life cycle. (SEH5 Ch3) |
| 26 | What is a stakeholder analysis 2×2 grid typically based on? | Influence (low/high) and Interest (low/high). Produces four quadrants: Manage Closely (high/high), Keep Informed (high interest / low influence), Keep Satisfied (high influence / low interest), Monitor (low/low). |
| 27 | Define: Requirements Elicitation | The process of discovering, capturing, and understanding the needs of stakeholders. (ISO 29148 §5) |
| 28 | Name seven elicitation techniques from ISO 29148. | Interviews, workshops, observation, questionnaires, use cases, scenarios, prototyping, document analysis. (Any seven.) |
| 29 | When is **observation** the most appropriate elicitation technique? | When stakeholders cannot easily articulate their needs in abstract terms — e.g., where tacit knowledge dominates, or where the system replaces or augments an existing practice. Shadowing users in their operational environment uncovers needs interviews miss. |
| 30 | When is a **workshop** most appropriate vs an **interview**? | Workshops suit consensus-building among multiple stakeholders. Interviews suit deep, individual context from influential or senior stakeholders. Workshops are faster but risk domination by strong voices; interviews are slower but richer. |
| 31 | What is the main weakness of **questionnaires** as an elicitation technique? | They sacrifice depth for scale — large population reach but shallow insight, and quality is highly sensitive to question-framing bias. |
| 32 | What is **prototyping** useful for in elicitation, and what is its main risk? | Useful when stakeholders cannot describe needs abstractly — they can react to a visual/interactive draft. Main risk: premature solution anchoring — stakeholders fixate on the prototype rather than the underlying need. |
| 33 | Define: Use Case | A description of a system behaviour initiated by an actor to achieve a specific goal, typically expressed as a sequence of interactions. (ISO 29148 §5; SEH5 Ch3) |
| 34 | Define: Scenario | A narrative description of a specific sequence of events or interactions involving the system and its environment, used to explore behaviour under particular conditions. (SEH5 Ch3) |
| 35 | What is the difference between a use case and a scenario? | A use case is a structured description of a goal-oriented system interaction, typically covering multiple scenarios (main success, alternative, failure). A scenario is a single, concrete sequence of events — one instance of how a use case might unfold. |
| 36 | Define: Actor | An entity — human, organisation, or other system — that interacts with the system to achieve a goal. (ISO 29148 §5) |
| 37 | Why must elicitation continue through the Concept and early Development stages, not end at a single kick-off? | Stakeholder understanding of their own needs evolves as the problem is explored; regulations and mission context change; new stakeholders are discovered. Treating elicitation as a one-off event produces a requirements set that is out of date by baseline. |
| 38 | What is the SE activity when two stakeholders' inputs conflict? | Conflict resolution — a formal SN&RD activity. The systems engineer surfaces the conflict, negotiates with both parties (often with acquirer arbitration), documents the resolution with rationale, and updates the requirements set accordingly. Unresolved conflicts become costly late-stage design disputes. |
| 39 | Define: Measure of Effectiveness (MoE) | A stakeholder/mission-oriented measure of how well the system accomplishes its intended purpose in the operational environment. (SEH5 Ch3) |
| 40 | Define: Measure of Performance (MoP) | A system-oriented measure of a particular system attribute, often derived from an MoE, used for verification of system requirements. (SEH5 Ch3) |
| 41 | How do MoEs and MoPs relate? | One MoE (stakeholder/mission outcome, e.g., "average emergency-response time") is typically supported by multiple MoPs (system attributes, e.g., "dispatch-to-notify latency", "GPS update rate"). MoEs drive validation; MoPs drive verification. |

---

## 📦 Section 3 — Requirements Hierarchy, Characteristics & Baselining (Cards 42–55)
*Covers: Days 5 & 6 — requirements hierarchy, ISO 29148 characteristics, validation, MoEs, baselining*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 42 | Name the six levels of the requirements hierarchy from top to bottom. | (1) Business/mission need; (2) stakeholder need; (3) stakeholder requirement; (4) system requirement; (5) subsystem/element requirement; (6) component/implementation requirement. |
| 43 | Which two ISO 15288 Technical Processes produce the top two engineering levels of the requirements hierarchy? | Stakeholder Needs and Requirements Definition (§6.4.2) produces stakeholder requirements; System Requirements Definition (§6.4.3) produces system requirements. |
| 44 | Define: Requirement | A statement that identifies a product or process operational, functional, or design characteristic or constraint, which is unambiguous, verifiable, and deemed necessary for product or process acceptability. (ISO 29148 §3.1) |
| 45 | List the 9 ISO/IEC/IEEE 29148 §5.2 characteristics of a well-formed requirement. | Necessary, Appropriate, Unambiguous, Complete, Singular, Feasible, Verifiable, Correct, Conforming. (ISO 29148 §5.2) |
| 46 | Define the "verifiable" characteristic of a requirement. | A characteristic such that compliance of the product or process with the requirement can be demonstrated by one of the four verification methods — test, analysis, inspection, or demonstration. (ISO 29148 §5.2) |
| 47 | Name the four verification methods used to demonstrate a requirement is met. | Test, Analysis, Inspection, Demonstration. (ISO 29148 §5.2; expanded in ISO 15288 §6.4.9) |
| 48 | Give an example of a compound requirement and show how to fix it. | Bad: "The system shall process requests quickly **and** reliably." Fix — split into two singular requirements: (1) "The system shall process requests with a mean response time ≤ 2 s." (2) "The system shall achieve ≥ 99.9% request success rate over a 24 h period." |
| 49 | Why should a requirement specify *what* rather than *how*? | Specifying *how* prematurely constrains the designer, may exclude better implementations, and mixes requirements with design. Stakeholder and system requirements must describe needed behaviour/attributes; implementation choices belong to Design Definition (§6.4.5). |
| 50 | Define: Rationale (requirement attribute) | The reason a requirement exists — the justification linking it back to a higher-level need. Captured as a requirement attribute alongside source and trace information. (ISO 29148 §5.2) |
| 51 | Define: Traceability | The ability to follow the life of a requirement in both forward and backward directions — from origin (stakeholder need) through development to deployment and use. (ISO 29148 §6) |
| 52 | State the ISO/IEC/IEEE 15288 §3 definition of validation. | Confirmation, through the provision of objective evidence, that the requirements for a specific intended use or application have been fulfilled. (ISO 15288 §3) |
| 53 | How does verification differ from validation, in one sentence each? | Verification asks: "did we build the thing right?" — confirming the system meets its specified requirements. Validation asks: "did we build the right thing?" — confirming the system (and its requirements) meet stakeholder needs for the intended use. (ISO 15288 §3) |
| 54 | Define: Stakeholder Requirements Baseline | The formally agreed and version-controlled set of stakeholder requirements that serves as the authoritative input to System Requirements Definition (§6.4.3). (SEH5 Ch3) |
| 55 | Why does the stakeholder requirements baseline require configuration control? | To prevent silent requirement drift: once baselined, changes require formal approval (typically via Configuration Management, §6.3.5). Without this, the programme designs against one understanding while stakeholders quietly evolve their expectations, producing late, expensive mismatches. |

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
