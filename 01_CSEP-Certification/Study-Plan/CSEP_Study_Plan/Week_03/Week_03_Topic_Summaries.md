# CSEP Week 3 — Topic Summaries: Technical Processes — Part 1A (Business/Mission Analysis → Stakeholder Needs)
**Chapter:** INCOSE SEH5 Chapter 3 — Technical Processes (§6.4.1 and §6.4.2)
**ISO Anchor:** ISO/IEC/IEEE 15288:2023 §6.4.1 (Business or Mission Analysis) and §6.4.2 (Stakeholder Needs and Requirements Definition)
**Supporting Standard:** ISO/IEC/IEEE 29148:2018 — Requirements Engineering
**Purpose:** Concise, exam-focused summaries for rapid revision before attempting practice questions

---

## Summary 1: The Business or Mission Analysis (BMA) Process — Purpose and Position

The **Business or Mission Analysis (BMA)** process is the first of the fourteen ISO/IEC/IEEE 15288 **Technical Processes** and sits at the interface between the enterprise strategy and the system life cycle. ISO/IEC/IEEE 15288:2023 §6.4.1 states its purpose as "to define the business or mission problem or opportunity, characterise the solution space, and determine potential solution class(es) that could address the problem." In short: BMA frames *what problem are we solving and for whom*, before any stakeholder requirements are written or any solution is committed to.

BMA exists because technical teams, if left to their own instincts, tend to jump to solutions. A new radar system is proposed without first confirming that the enterprise actually has a surveillance capability gap; a new software platform is scoped before business outcomes are defined. By placing BMA ahead of SN&RD, ISO 15288 forces an explicit problem-space step. Typical BMA inputs include organisational strategy, market or mission analysis, portfolio decisions, and prior system performance data. Typical BMA outputs include a **problem/opportunity statement**, a preliminary **stakeholder list**, a **preliminary life cycle concept**, and the identified **solution class(es)** considered viable.

BMA is normally iterative. The initial pass may be shallow — sufficient to authorise further investment — and successive passes become progressively more rigorous as the programme commits to a solution class. Crucially, BMA is not "owned" by engineering alone: the acquirer, portfolio manager, end-user community, and enterprise architecture team all contribute, with the systems engineer coordinating and ensuring SE rigour is applied. Where BMA is skipped or truncated, the downstream result is predictable — mis-scoped programmes, missing stakeholders, and solutions that are technically excellent but address the wrong problem.

**CSEP Exam Tip:** Memorise the §6.4.1 purpose wording. The exam frequently presents a scenario where a team jumps to SN&RD or directly to System Requirements Definition, and asks which ISO 15288 process should have preceded them — the answer is Business or Mission Analysis.

**Suggested Illustration:** Process flow diagram showing BMA (§6.4.1) sitting between enterprise inputs (strategy, portfolio decisions) on the left and downstream Technical Processes (SN&RD §6.4.2, System Requirements Definition §6.4.3) on the right, with named inputs/outputs on each arrow. 5 labelled boxes: Enterprise Strategy, BMA, SN&RD, System Requirements Definition, Architecture Definition.

---

## Summary 2: BMA Activities, Artefacts and the ConOps/OpsCon Distinction

ISO 15288 §6.4.1 groups BMA into five activity clusters: (1) prepare for BMA, (2) define the problem or opportunity space, (3) characterise the solution space, (4) evaluate alternative solution classes, and (5) manage the BMA results. The SE team plans the BMA activity, assembles relevant data, identifies candidate stakeholders, and sets exit criteria. The problem space is then characterised — often through capability-gap analysis, mission analysis, or market analysis — producing a validated problem statement. The solution space is populated with candidate solution classes (for example: a constellation of small satellites vs a single geostationary satellite vs an airborne platform). Each class is evaluated using **trade studies** against criteria such as feasibility, cost, schedule, risk, and mission effectiveness. Finally, the results are baselined, traceability is established upward to enterprise strategy and downward to stakeholder needs, and the outputs are released as formal inputs to SN&RD.

Two artefacts deserve special attention for the CSEP exam. The **Concept of Operations (ConOps)** is an acquirer/user-oriented description of how the envisaged system will be operated in its intended environment — who the operators are, what the mission is, what scenarios are expected, and what operational constraints apply. The **Operational Concept (OpsCon)** is a supplier/system-developer-oriented description derived from the ConOps, describing how the system itself behaves to support those operations. Both are defined in ISO/IEC/IEEE 29148:2018 (ConOps in Clause 4.2, OpsCon in Clause 4.3). A common exam trap is to treat ConOps and OpsCon as synonyms; they are related but intentionally distinct, with different authors, different audiences, and different levels of solution detail.

| Artefact | Perspective | Author | Primary Audience | Typical Content |
|---------|------------|--------|-----------------|----------------|
| ConOps | Acquirer / user / mission | Acquirer (often with SE support) | Stakeholders, user community | Mission, users, environment, scenarios |
| OpsCon | Supplier / system developer | Supplier / developer SE team | Internal engineering | How the system supports the ConOps; interfaces; operational modes |

**CSEP Exam Tip:** If the question asks which artefact expresses *what the acquirer wants to achieve in the operational environment*, the answer is ConOps. If it asks which artefact expresses *how the system will behave to support those operations*, the answer is OpsCon.

**Suggested Illustration:** Two-column concept diagram contrasting ConOps and OpsCon, with a central arrow showing ConOps feeding OpsCon. Each column lists perspective, author, audience, and 2–3 typical content items. Use neutral technical styling; label both boxes with their ISO 29148 clause (4.2 and 4.3).

---

## Summary 3: The Stakeholder Needs and Requirements Definition (SN&RD) Process — Purpose and Inputs/Outputs

The **Stakeholder Needs and Requirements Definition (SN&RD)** process is the second of the fourteen Technical Processes. ISO/IEC/IEEE 15288:2023 §6.4.2 states its purpose as "to define the stakeholder requirements for a system that can provide the capabilities needed by users and other stakeholders in a defined environment." It takes the BMA outputs — problem statement, preliminary stakeholder list, preliminary life cycle concepts — and produces a validated, baselined set of **stakeholder requirements** that serves as the authoritative input to the System Requirements Definition process (§6.4.3, covered in Week 4).

Inputs to SN&RD include the BMA outputs, organisational policies, applicable regulatory constraints, prior stakeholder feedback, and the ConOps/OpsCon. The process produces three principal output classes: (1) a documented, validated set of **stakeholder needs**; (2) a documented, validated set of **stakeholder requirements** — engineering-ready statements derived from those needs; and (3) a **stakeholder requirements baseline** that is configuration-controlled and serves as the formal input to downstream processes.

A **stakeholder** is defined in ISO/IEC/IEEE 15288 §3 as "an individual or organisation having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations." The practical implication is that stakeholders extend well beyond paying customers — they include end users, operators, maintainers, suppliers, regulators, acquirers, the wider public, and even the natural environment where environmental legislation applies. Missing a stakeholder at this stage is one of the most expensive SE errors, because unidentified stakeholders tend to surface later in the programme with requirements that the system cannot easily accommodate.

**CSEP Exam Tip:** Memorise the §6.4.2 purpose wording and the ISO 15288 definition of "stakeholder." Exam questions frequently probe whether you can distinguish stakeholder needs, stakeholder requirements, and system requirements — and whether you recognise that stakeholder identification itself is part of SN&RD (and BMA).

**Suggested Illustration:** Input–Process–Output (IPO) box diagram for SN&RD. Left side lists inputs (BMA outputs, regulations, ConOps); centre box "Stakeholder Needs and Requirements Definition (ISO 15288 §6.4.2)"; right side lists outputs (stakeholder needs, stakeholder requirements, baseline). Include stakeholder-feedback loop arrow from outputs back to inputs.

---

## Summary 4: Stakeholder Identification, Elicitation and Analysis

Once the SN&RD process is under way, the first task is a systematic **stakeholder identification**. The systems engineer must consciously extend beyond the obvious buyer/user pair. Typical categories include: **users** (who interact with the system during operation), **operators** (who run or monitor it), **maintainers** (who service it), **acquirers** (who procure it), **suppliers** (who deliver elements of it), **regulators** (who impose legal or standards constraints), **society/environment** (non-contractual but legitimate interests), and **enabling-system owners** (who provide infrastructure, training, or support). ISO 15288 §6.4.2 explicitly requires that stakeholders be identified across the full life cycle — not only for the Concept and Development stages.

**Requirements elicitation** is then applied to each stakeholder group. ISO/IEC/IEEE 29148:2018 §5 describes a range of techniques, each with strengths and weaknesses that must be matched to the context. **Interviews** (typically semi-structured, one-on-one) capture rich qualitative detail but are slow and depend heavily on interviewer skill. **Workshops** facilitate consensus-building among multiple stakeholders but can be dominated by strong voices and miss quieter concerns. **Observation** (shadowing users in their operational environment) uncovers tacit needs that users cannot articulate — particularly valuable when the system replaces or augments current practice. **Questionnaires** scale to large stakeholder populations but sacrifice depth. **Use cases and scenarios** provide structured narrative forms that expose missing behaviours. **Prototyping** lets stakeholders react to a draft solution rather than describe needs abstractly. **Document analysis** mines existing policies, regulations, and prior system documentation for implicit requirements. In practice, multiple techniques are used in combination, and elicitation continues iteratively throughout the Concept and early Development stages.

| Technique | Best For | Caution |
|----------|---------|---------|
| Interviews | Deep individual context, influential stakeholders | Slow; interviewer-dependent |
| Workshops | Consensus-building among diverse stakeholders | Dominant voices; group-think |
| Observation | Tacit, unarticulated needs | Labour-intensive; access sensitivities |
| Questionnaires | Large populations; quantitative patterns | Shallow; question-framing bias |
| Use cases / scenarios | Behavioural coverage; gap detection | Need validation with stakeholders |
| Prototyping | Visual/interactive stakeholders; ambiguous needs | Risk of premature solution anchoring |
| Document analysis | Regulatory, legal, prior-system requirements | Documents become stale; must be verified |

Analysis of elicited information consolidates duplicates, flags conflicts between stakeholders, and assigns priority (often by a combination of importance and urgency). Conflict resolution is a formal SE activity: unresolved conflicts between stakeholders at this stage become late, expensive design disputes if they are not surfaced and negotiated before the stakeholder requirements baseline is set.

**CSEP Exam Tip:** The exam often presents a scenario and asks which elicitation technique is most appropriate. Match the scenario's characteristics — number of stakeholders, maturity of the problem space, access to operational sites, need for tacit knowledge — to the technique's strengths. Observation and prototyping in particular are frequently the correct answer for novel or replacement systems where stakeholders cannot articulate their needs in abstract terms.

**Suggested Illustration:** Stakeholder map / 2×2 matrix with axes Influence (low/high) and Interest (low/high). Four quadrants labelled "Keep Informed", "Keep Satisfied", "Monitor", "Manage Closely". Overlay example stakeholder categories (users, regulators, suppliers, society) in illustrative positions. Clean textbook-style layout, neutral palette, UK English labels.

---

## Summary 5: The Requirements Hierarchy and the Stakeholder/System Requirement Distinction

One of the most heavily tested distinctions on the CSEP exam is between a **stakeholder need**, a **stakeholder requirement**, and a **system requirement**. They are not synonyms; each occupies a specific level in the top-down requirements hierarchy.

At the top sits the **business or mission need** — an enterprise-level statement of why the system is being developed (for example, "the organisation needs to reduce average emergency-call response time by 30%"). From this derive **stakeholder needs** — statements, typically in stakeholder language, of what each stakeholder group wants or expects (for example, an operator says "I need to be able to see all ambulance positions on one screen"). Stakeholder needs are then engineered into **stakeholder requirements** — structured, analysable, and verifiable statements of the same intent (for example, "the system shall display the location of all active ambulance units on a single operator console within 5 seconds of a position update"). Stakeholder requirements become the input to the **System Requirements Definition** process (Week 4), which produces **system requirements** — engineering-ready statements specifying *what the system must do*, typically decomposed further into **subsystem/element requirements** and finally **component/implementation requirements**.

| Level | Example | Process / Reference |
|-------|---------|---------------------|
| Business or mission need | "Reduce emergency-call response time by 30%." | BMA (ISO 15288 §6.4.1) |
| Stakeholder need | "I need to see all ambulance positions on one screen." | SN&RD (ISO 15288 §6.4.2) |
| Stakeholder requirement | "The system shall display the position of all active ambulance units on a single operator console within 5 s of a position update." | SN&RD (ISO 15288 §6.4.2) |
| System requirement | "The system shall accept GPS position updates at ≥1 Hz from each connected ambulance; display latency ≤ 5 s." | System Req. Definition (ISO 15288 §6.4.3) |
| Subsystem / element requirement | "The map-rendering subsystem shall redraw the ambulance layer within 1 s of receiving a position update." | Design Definition (§6.4.5) |
| Component / implementation requirement | "The rendering library shall support ≥ 200 concurrently drawn markers at 30 fps." | Implementation (§6.4.6) |

ISO/IEC/IEEE 29148:2018 §5.2 sets out the nine characteristics of a well-formed requirement: **necessary, appropriate, unambiguous, complete, singular, feasible, verifiable, correct, and conforming**. A written requirement should also specify *what* the system must do, not *how* it should be implemented — implementation constraints belong in a separate "design constraint" category. Each requirement should carry a **rationale** (the justification for its existence) and **source/trace attributes** so that it can be followed up and down the hierarchy — **traceability** being a fundamental property of a managed requirements set.

**CSEP Exam Tip:** When the exam asks whether a stated requirement is at the stakeholder level or the system level, ask yourself two questions: (1) whose language is it in — the stakeholder's or the engineer's?; and (2) does it describe an external-facing need or an internal system behaviour/attribute? Stakeholder requirements are stakeholder-facing and capability-oriented; system requirements are engineering-facing and behaviour/attribute-oriented.

**Suggested Illustration:** Vertical pyramid / hierarchy diagram with 6 layers from top (Business/Mission Need) to bottom (Component Requirement), each layer labelled with its ISO 15288 process and a short example. Arrows indicate both downward derivation (derives from) and upward traceability (trace to). Use distinct shading to mark the stakeholder-facing layers (top 3) versus engineering-facing layers (bottom 3).

---

## Summary 6: Characteristics of a Good Requirement (ISO/IEC/IEEE 29148 §5.2)

ISO/IEC/IEEE 29148:2018 §5.2 defines the characteristics that any well-formed requirement should exhibit. These characteristics are a frequent source of CSEP exam questions, both directly (defining the terms) and indirectly (recognising a poorly formed requirement in a scenario). There are nine individual-requirement characteristics and a further set of set-level characteristics applied to the requirements *set* as a whole.

The nine individual-requirement characteristics are:

| Characteristic | Meaning | Common Defect |
|--------------|--------|--------------|
| Necessary | Defines a capability or constraint that is essential; removing it would create a deficiency | Gold-plating; gratuitous requirements |
| Appropriate | At the right level of detail for its scope; not over- or under-specified | Implementation detail in a stakeholder requirement |
| Unambiguous | Only one reasonable interpretation | Vague terms: "user-friendly", "fast" |
| Complete | Stated in full; nothing important missing | Implicit assumptions; missing conditions |
| Singular | One requirement per statement | Compound requirements joined by "and"/"or" |
| Feasible | Technically and economically achievable within constraints | Impossible performance; infeasible within schedule/budget |
| Verifiable | Can be demonstrated by test, analysis, inspection, or demonstration | Subjective, untestable phrasing |
| Correct | Accurately reflects the source need | Transcription error; misunderstood stakeholder intent |
| Conforming | Follows the organisation's / programme's authoring conventions | Non-standard language, missing attributes |

Additional **set-level** characteristics apply to the requirements collection: **complete** (as a set), **consistent** (no internal contradictions), **feasible** (achievable as an integrated whole), **comprehensible** (readable and understandable), and **able to be validated** (stakeholders can confirm the set reflects their needs).

Four verification methods are defined (and carry over into Week 6 on Verification): **test** (operating the system and measuring results), **analysis** (mathematical or logical derivation), **inspection** (visual examination of the artefact), and **demonstration** (showing operational use without detailed measurement). A requirement that cannot be verified by at least one of these four methods fails the "verifiable" characteristic and must be rewritten or decomposed.

**CSEP Exam Tip:** Expect questions that show a requirement and ask which characteristic it violates. Classic exam-bait includes: "The system shall be user-friendly" (unambiguous and verifiable — both violated), "The system shall process requests quickly and reliably" (singular — compound with "and"), "The system shall be implemented in Java 21" (appropriate — implementation bias at the wrong level).

**Suggested Illustration:** N/A — text only. The 9-characteristic table is itself the primary teaching visual; a diagram would not add pedagogical value beyond the table.

---

## Summary 7: Validation of Stakeholder Requirements, MoEs/MoPs, and Baselining

**Validation** is formally defined in ISO/IEC/IEEE 15288 §3 as "confirmation, through the provision of objective evidence, that the requirements for a specific intended use or application have been fulfilled." In the SN&RD context, validation specifically means confirming with the stakeholders that the captured stakeholder requirements correctly and completely reflect their needs — **before** any system-requirement derivation begins. This upstream validation is a critical risk-reduction activity: a requirement that is well-formed but validates against the *wrong* need still produces an unusable system.

Two measurement concepts support validation. A **Measure of Effectiveness (MoE)** is a stakeholder/mission-oriented measure expressing how well the system accomplishes its purpose in the operational environment — for example, "average response time from emergency call to on-scene arrival (minutes)." A **Measure of Performance (MoP)** is a system-oriented measure of a particular attribute — for example, "time from dispatch console button-press to unit notification (seconds)." MoPs are typically derived from MoEs and are the measurable quantities that engineering can trace to system requirements. One MoE is usually supported by several MoPs. This MoE/MoP split enables validation (against MoEs) to be distinguished from verification (against MoPs), a distinction explored further in Week 6.

Finally, once stakeholder requirements have been validated and consolidated, they are **baselined** — formally approved, versioned, and placed under configuration control. This **stakeholder requirements baseline** is the authoritative input handed to the System Requirements Definition process (Week 4). From this point onward, changes to stakeholder requirements require formal change control, typically administered through the Configuration Management process (Technical Management Processes, Week 7). A disciplined baseline prevents the common SE failure mode of silently drifting requirements — where a programme designs against one understanding of stakeholder intent while stakeholders quietly evolve their expectations.

**CSEP Exam Tip:** Validation (are we building the right thing?) and verification (are we building the thing right?) are deliberately tested together on the exam. Remember that validation **can and should begin in Week 3** — with stakeholder validation of the stakeholder requirements baseline — not only at the end of Development. Also remember the MoE ↔ validation, MoP ↔ verification mental pairing.

**Suggested Illustration:** A Venn-style or parallel-track diagram showing Validation (operating on MoEs, stakeholder-facing, asks "right thing?") on one side and Verification (operating on MoPs, system-facing, asks "thing right?") on the other, with SN&RD outputs feeding both. Label with ISO 15288 §3 definitions verbatim and the §6.4.11 (Validation) and §6.4.9 (Verification) process references.

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
