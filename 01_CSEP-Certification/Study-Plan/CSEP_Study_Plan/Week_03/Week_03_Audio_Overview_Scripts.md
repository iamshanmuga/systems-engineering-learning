# CSEP Week 3 — Audio Overview Scripts: Business/Mission Analysis & Stakeholder Needs
**Format:** Host (H) / Expert Guest (G) podcast-style dialogue — NotebookLM Audio Overview style
**Total Target Runtime:** ~45 minutes across 7 tracks
**Topic:** INCOSE SEH5 Chapter 3 — Technical Processes (Part 1A); ISO/IEC/IEEE 15288:2023 §6.4.1 (Business or Mission Analysis) and §6.4.2 (Stakeholder Needs and Requirements Definition); ISO/IEC/IEEE 29148:2018 — Requirements Engineering

---

## 🎙️ Track 1 — Why Business/Mission Analysis Exists
*(Est. runtime: ~6 minutes)*

**H:** Welcome to the CSEP prep series, Week 3. Last week we walked the life cycle — stages, processes, decision gates. This week we step inside the Technical Processes and start at the very top. Our topic: Business or Mission Analysis — BMA for short — and Stakeholder Needs and Requirements Definition. Let's start with the most basic question: why does BMA exist at all?

**G:** BMA exists because before you can engineer a system, you have to be sure the system is the right thing to build. That sounds obvious, but it's surprisingly easy to skip.

**H:** So BMA comes *before* the system?

**G:** Yes — and that's the single most important framing. BMA is defined in ISO/IEC/IEEE 15288:2023 §6.4.1 as the first of the Technical Processes. Its purpose is to define the business or mission problem, characterise the solution space, and justify that a system is an appropriate response.

**H:** "Problem space" and "solution space" — why the distinction?

**G:** Because a lot of projects jump straight to the solution. Someone says "we need a new logistics platform" — that's a solution. BMA insists we step back and ask: what is the *problem*? Maybe we have poor inventory visibility. Maybe our distribution network is under-utilised. Until we articulate the problem properly, we can't evaluate whether a new platform — or something else entirely — is the right response.

**H:** So BMA might conclude that no system is needed?

**G:** Absolutely. A legitimate BMA outcome is "don't build." The problem might be solvable by policy change, organisational restructuring, or process improvement. That's one of the things that distinguishes BMA from later processes — it keeps the "no-build" option on the table.

**H:** What feeds BMA? What are the inputs?

**G:** Typically: enterprise strategy, mission statements, market analysis, stakeholder expectations, regulatory drivers, and existing capability assessments. The outputs are where it gets interesting.

**H:** Which are?

**G:** A preliminary Concept of Operations — the ConOps — business requirements, measures of effectiveness, the preferred solution class, and a justification to proceed. Those outputs feed directly into Stakeholder Needs and Requirements Definition, which is §6.4.2.

**H:** So BMA produces the business case; SN&RD produces the stakeholder requirements.

**G:** Exactly. And the exam tests the direction of that flow. BMA outputs feed SN&RD inputs — never the reverse.

**H:** Quick distinction — BMA versus a business case.

**G:** A business case is one artefact. BMA is a full SE process with five activity clusters. The business case is typically a *product* of BMA, not a synonym for it.

**H:** Great setup. Track 2 — the inside of BMA.

---

## 🎙️ Track 2 — Inside BMA: Activities, Artefacts, and ConOps vs OpsCon
*(Est. runtime: ~8 minutes)*

**H:** Let's open up the BMA process. What activities sit inside?

**G:** ISO 15288 §6.4.1.3 organises BMA into five activity clusters. One: prepare for the analysis — establish the scope, assemble the team, agree the approach. Two: define the problem or opportunity space — what is the mission need, what capability gap exists. Three: characterise the solution space — identify candidate solution classes, not specific designs. Four: evaluate alternatives — compare the candidates against measures of effectiveness. Five: manage the results — capture decisions, maintain traceability, support downstream processes.

**H:** Five clusters. And the deliverable everyone asks about: the ConOps.

**G:** Yes — the Concept of Operations. ISO/IEC/IEEE 29148:2018 §4.2 defines it. It describes, from the acquirer or user perspective, how the system or capability is intended to be used in the operational environment.

**H:** And the OpsCon?

**G:** The Operational Concept — 29148 §4.3. From the system's perspective. It describes the system's operational characteristics, modes, missions, and interactions with operators and other systems.

**H:** They sound almost identical. What's the exam-worthy distinction?

**G:** Viewpoint. ConOps is written by — or for — the acquirer. It's about *use*: who does what with the capability, in what context, to achieve what mission outcome. OpsCon is written by — or for — the developer. It's about the *system as an actor*: modes of operation, performance profiles, interactions across interfaces.

**H:** And the timing?

**G:** ConOps emerges in BMA — early, high level, problem-space framed. OpsCon typically emerges in Stakeholder Needs Definition and is refined into Development. More detailed, more bounded.

**H:** Are they mandatory?

**G:** 29148 describes both. Whether a specific programme produces both artefacts is a tailoring decision. But the exam will test that you know which viewpoint each takes.

**H:** Let's talk Measures of Effectiveness — MoEs. They appear in BMA. What are they?

**G:** An MoE is a mission-level measure. It captures how well the mission or business objective is achieved — not how the system performs. Examples: logistics turnaround time, mission success rate, operational availability.

**H:** And MoPs — Measures of Performance?

**G:** MoPs are system-level measures. They characterise how the system performs against specified requirements — throughput, latency, range, accuracy. MoPs are introduced in BMA at a high level but elaborated in SN&RD and Systems Requirements Definition.

**H:** So the hierarchy: MoE is mission-level, MoP is system-level.

**G:** Exactly. A common exam trap: labelling a purely technical metric as an MoE. If it doesn't tie to mission success, it's not an MoE.

**H:** What's the traceability picture from BMA?

**G:** Every BMA output — business requirements, ConOps, MoEs — should have a traceable path forward into stakeholder needs, then stakeholder requirements, then system requirements. That trace is bidirectional. You should be able to pick any system requirement and trace it back up to the business driver that justified it.

**H:** That traceability is the SE backbone.

**G:** It is. And it's how BMA earns its place at the top of the Technical Processes. Everything downstream is accountable to decisions made here.

---

## 🎙️ Track 3 — Stakeholder Needs and Requirements Definition: The Bridge
*(Est. runtime: ~7 minutes)*

**H:** Track 3. We've closed BMA. Now we cross into §6.4.2 — Stakeholder Needs and Requirements Definition. Or SN&RD. What is this process doing?

**G:** SN&RD is the bridge. Its purpose — ISO 15288 §6.4.2.1 — is to define stakeholder needs and transform them into a set of stakeholder requirements that the system must satisfy.

**H:** Bridge between what and what?

**G:** Between the business or mission problem — which BMA articulated — and the engineering definition of the system, which comes later in §6.4.3, System Requirements Definition. SN&RD is the first process where we're engaging stakeholders directly and producing formal requirements.

**H:** Give us the inputs and outputs in one pass.

**G:** Inputs: the preliminary ConOps, business requirements, MoEs, and stakeholder identification output from BMA. Outputs: stakeholder needs, stakeholder requirements, an Operational Concept, validation criteria, and — this is important — a stakeholder requirements baseline.

**H:** Stakeholder requirements baseline. What does baselining mean here?

**G:** A baseline is a formally approved version of a set of artefacts, placed under configuration control. Once baselined, changes go through a change process — typically reviewed by a Change Control Board — not informal edits. The stakeholder requirements baseline is the first major SE baseline, and it sets the contract between acquirer and supplier.

**H:** Now — needs versus requirements. They're often used loosely.

**G:** The exam insists on the distinction. A stakeholder *need* is a statement from the stakeholder in their own language — often aspirational, often ambiguous. A stakeholder *requirement* is the engineered statement of that need — expressed unambiguously, verifiably, and singularly.

**H:** So SN&RD literally transforms one into the other.

**G:** Yes. Take this need: "the system should be easy to use." As-stated, not a requirement — not verifiable. SN&RD transforms it: "A new operator shall complete the onboarding task within 15 minutes with no more than one error, on first attempt." Now it's verifiable.

**H:** And who participates?

**G:** Stakeholders first — but SN&RD also involves systems engineers, domain experts, human factors specialists, safety and security engineers if relevant. It's a collaborative process.

**H:** Many projects struggle because they treat SN&RD as a formality — capture a list, get sign-off, move on.

**G:** That's the anti-pattern. SN&RD done well takes real time. Done poorly, every downstream requirement is suspect because it's traceable to an unverifiable need.

**H:** Bridge metaphor — BMA is the shore of the problem space; System Requirements Definition is the shore of the engineered solution; SN&RD is the crossing.

**G:** That's a good way to keep the processes ordered in your head.

---

## 🎙️ Track 4 — Identifying and Eliciting from Stakeholders
*(Est. runtime: ~7 minutes)*

**H:** You can't satisfy stakeholders you haven't identified. Track 4 — identification and elicitation. What does ISO 15288 say a stakeholder *is*?

**G:** A stakeholder is any individual or organisation with a legitimate interest in — or effect on — the system across its life cycle. That's broader than many teams initially assume.

**H:** How broad?

**G:** Typical categories: acquirer, user, operator, maintainer, supplier, regulator, certifier, disposer, the enterprise owner, and — often overlooked — adversarial stakeholders for safety and security.

**H:** Adversarial stakeholders?

**G:** Anyone who might intentionally degrade the system — attackers in a cyber context, hostile actors in a defence context. You identify them to capture what the system must *resist*. Their interests are negative; that doesn't make them less relevant.

**H:** And what about indirect stakeholders — someone who doesn't touch the system but is affected by it?

**G:** Absolutely included. If an environmental regulation affects disposal, the regulator is a stakeholder even though they never use the system.

**H:** Now — elicitation. You've got the list. How do you extract their needs?

**G:** Eight classical techniques — and the exam expects you to know roughly when each is useful. Interviews — one-to-one, deep probing, good for tacit knowledge. Workshops — group alignment, consensus building, surface disagreements quickly. Observation — watch operators in context, catches what they don't articulate. Questionnaires — reach many stakeholders, statistical patterns. Use cases — structure interactions into scenarios. Scenarios — richer, narrative-driven exploration. Prototyping — show, don't tell, get feedback on something tangible. Document analysis — existing manuals, regulations, historical incident reports.

**H:** Is one technique best?

**G:** No — and that's the exam's point. Elicitation is a toolkit, not a single method. Good SE practice triangulates — use two or three techniques on the same question and compare the results.

**H:** What's the failure mode if you use only one?

**G:** Every technique has blind spots. Interviews miss groupthink. Workshops miss the quiet voice. Observation is slow. Questionnaires lose nuance. Prototyping biases toward the shown design. Triangulation reduces those biases.

**H:** And stakeholder analysis — after identification?

**G:** Prioritisation, essentially. Often using a power-interest matrix. You rank stakeholders by their power over the programme and their interest in it. High power, high interest — you engage intensively. Low power, low interest — you keep informed. It's not that some stakeholders matter less as people — but the SE engagement effort has to be allocated.

**H:** Does SEH5 prescribe the matrix?

**G:** SEH5 presents it as one supporting practice. It's not mandated by ISO 15288. Like named decision-gate reviews, tools are programme-specific.

**H:** Elicitation, analysis, prioritisation — the chain that makes SN&RD work.

**G:** And the chain where the biggest SE investment pays off, because everything downstream is anchored here.

---

## 🎙️ Track 5 — Requirements Hierarchy and What Makes a Good Requirement
*(Est. runtime: ~8 minutes)*

**H:** Track 5 — the structural backbone. The requirements hierarchy.

**G:** Six levels. Business or mission need. Stakeholder need. Stakeholder requirement. System requirement. Subsystem requirement. Component or element requirement. Each level refines the one above and is traceable to it.

**H:** And each level lives in a different process?

**G:** Exactly. Business and mission needs sit in BMA. Stakeholder needs and stakeholder requirements are produced by SN&RD. System requirements by System Requirements Definition — §6.4.3 — which we'll cover next week. Subsystem and component requirements by Architecture and Design Definition further down.

**H:** The hierarchy enforces discipline.

**G:** It does two things. First, it forces a clean ordering — you can't write a system requirement without a traceable stakeholder requirement above it. Second, it supports impact analysis — change a business need, and you can trace forward to see every system requirement that might need revisiting.

**H:** And the traceability matrix?

**G:** Bidirectional. Every requirement traces up to its parent — the driver — and down to its children, the requirements derived from it. Plus sideways traces: to verification methods, validation methods, source stakeholders.

**H:** Now — what makes a requirement *good*?

**G:** ISO/IEC/IEEE 29148:2018 §5.2 lists nine characteristics. And the exam expects you to recognise all nine, and — for higher-level questions — to classify a defective requirement by which characteristic it violates.

**H:** Let's go through them.

**G:** Necessary — if removed, the system would fail to meet a stakeholder need. Appropriate — written at the correct level and granularity, not too specific, not too abstract. Unambiguous — a single interpretation; avoid "user-friendly," "fast," "adequate." Complete — self-contained; no missing caveats or conditions. Singular — one requirement per statement; no "shall X and shall Y."

**H:** That's five.

**G:** Feasible — achievable with available technology, within cost, schedule, and risk constraints. Verifiable — you can test, analyse, inspect, or demonstrate that it's met. Correct — accurate, free of errors, faithful to the source need. Conforming — written in the approved format, style, and template of the programme.

**H:** Nine. And you also mentioned verifiable specifically.

**G:** Verifiability is arguably the most commonly violated. "The system shall be user-friendly" — not verifiable. No metric, no test, no method. Every time you write a requirement, ask yourself: *how will I prove this?* If you can't answer, it's not a requirement yet.

**H:** Verification methods?

**G:** Four classical methods — and they come up often. Test — operate the system under controlled conditions and measure. Analysis — mathematical or modelling-based proof when test is infeasible. Inspection — examine documentation, code, or physical properties without operating. Demonstration — show the capability in operational use, typically observed rather than instrumented.

**H:** And the acronym people remember?

**G:** TAID. Test, Analysis, Inspection, Demonstration. Not a formal standard acronym but widely used.

**H:** Ambiguity is the silent killer of requirements.

**G:** It is. And the nine characteristics are the antidote.

---

## 🎙️ Track 6 — Validation, MoEs Revisited, and Baselining
*(Est. runtime: ~6 minutes)*

**H:** Track 6. We've built the requirements. Now — validation.

**G:** Validation is not verification. That's the first exam trap.

**H:** ISO definitions?

**G:** ISO 15288 §3 — paraphrasing: verification confirms specified requirements have been met. Validation confirms that the system satisfies stakeholder needs in the intended operational environment. Verification asks "did we build the system right?" Validation asks "did we build the right system?"

**H:** And the examinable consequence?

**G:** You can pass verification and fail validation. You built exactly what the requirements said — but the requirements didn't capture what the stakeholder actually needed. That's a validation failure.

**H:** Where does SN&RD fit in?

**G:** SN&RD produces validation criteria. Each stakeholder requirement has associated validation criteria — what would convince the stakeholder that their need is met. Those criteria get carried forward into the Validation process, §6.4.12, typically exercised in Utilisation.

**H:** Back to MoEs and MoPs — you introduced them in Track 2.

**G:** Let's sharpen. An MoE is mission or business level. Does the operational outcome happen? MoP is system level. Does the system perform as specified? MoEs often support validation; MoPs often support verification.

**H:** So MoEs answer "did we build the right thing" and MoPs answer "did we build it right."

**G:** That mapping isn't absolute, but it's a useful mental model for the exam.

**H:** Baselining — when does it happen in SN&RD?

**G:** At the end of SN&RD, you hold a stakeholder requirements review. On approval, you declare the stakeholder requirements baseline. From that moment, changes flow through change control — usually a Change Control Board.

**H:** Why does the baseline matter so much?

**G:** Three reasons. One: it fixes the contract between acquirer and supplier. Two: it becomes the reference against which downstream work — system requirements, architecture, V&V planning — is judged. Three: it makes impact analysis tractable. Without a baseline, a "change" has nothing to be different from.

**H:** And tooling?

**G:** Typically a requirements management tool — DOORS, Jama, Polarion, Cameo. But the SE principle is independent of tool choice. What matters is that the baseline is identified, versioned, change-controlled, and traceable.

**H:** Validation, MoEs, baselining — the three guardrails that make SN&RD complete.

---

## 🎙️ Track 7 — Closing Recap: Week 3 High-Yield Summary
*(Est. runtime: ~3 minutes)*

**H:** Week 3 in 90 seconds. Go.

**G:** Business or Mission Analysis — ISO 15288 §6.4.1 — is the first Technical Process. It defines the problem, characterises the solution space, and justifies a system response. Five activity clusters. Outputs include ConOps, business requirements, and MoEs.

**H:** ConOps versus OpsCon.

**G:** ConOps — acquirer or user viewpoint, problem-space framing, ISO 29148 §4.2. OpsCon — system or developer viewpoint, system as actor, ISO 29148 §4.3.

**H:** Stakeholder Needs and Requirements Definition.

**G:** §6.4.2. The bridge. Transforms stakeholder needs, expressed in stakeholder language, into stakeholder requirements expressed unambiguously and verifiably. Outputs include stakeholder requirements baseline and validation criteria.

**H:** Identification and elicitation.

**G:** Stakeholders include acquirer, user, operator, maintainer, supplier, regulator, disposer, and adversarial parties. Eight classical techniques — triangulate across two or three, never rely on one.

**H:** Requirements hierarchy.

**G:** Six levels: business need, stakeholder need, stakeholder requirement, system requirement, subsystem, component. Traceability is bidirectional.

**H:** Nine characteristics — ISO 29148 §5.2.

**G:** Necessary, Appropriate, Unambiguous, Complete, Singular, Feasible, Verifiable, Correct, Conforming. Memorise all nine.

**H:** Validation versus verification.

**G:** Verification — did we build the system right. Validation — did we build the right system. Both are formal processes; they are not interchangeable.

**H:** Three things to do before Week 4?

**G:** First: draw the BMA-to-SN&RD flow diagram from memory, showing inputs, activities, and outputs. Second: take a defective requirement and classify which of the nine characteristics it violates. Third: practice stating the ConOps-vs-OpsCon distinction out loud — viewpoint, audience, timing.

**H:** Week 4 moves into §6.4.3 — System Requirements Definition — and §6.4.4 — Architecture Definition. The BMA and SN&RD foundations we've built this week will underpin everything that comes. See you there.

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
