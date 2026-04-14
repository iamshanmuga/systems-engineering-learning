# CSEP Week 2 — Audio Overview Scripts: Life Cycle Concepts
**Format:** Host (H) / Expert Guest (G) podcast-style dialogue — NotebookLM Audio Overview style
**Total Target Runtime:** ~45 minutes across 7 tracks
**Topic:** INCOSE SEH5 Chapter 2 — Life Cycle Concepts; ISO/IEC/IEEE 15288:2023 §6

---

## 🎙️ Track 1 — Why Does a System Need a Life Cycle?
*(Est. runtime: ~6 minutes)*

**H:** Welcome to the CSEP prep series, Week 2. Last week we covered the foundations — what Systems Engineering is and why it exists. This week we're going deeper: life cycle concepts. And I want to start with the obvious question — why does a system even need a life cycle framework?

**G:** Great starting point. Think of it this way: without a life cycle framework, you have no shared language for *when* things happen.

**H:** Meaning — what stage you're in?

**G:** Exactly. The INCOSE SEH5 defines the system life cycle as the evolution of a system over time, encompassing all stages from concept through retirement.

**H:** And ISO 15288 formalises that?

**G:** Right. ISO/IEC/IEEE 15288 names six specific stages: Concept, Development, Production, Utilisation, Support, and Retirement. In that order.

**H:** So the life cycle is the framework that answers "when" — when do we plan, when do we build, when do we operate?

**G:** Precisely. And one thing the exam tests heavily: the difference between a system life cycle and a project life cycle.

**H:** Tell us more.

**G:** The system life cycle spans the entire existence of the system — from the first concept through to disposal. The project life cycle is much narrower — it covers the timeline of the project that creates or modifies the system.

**H:** So a project might cover only the Concept and Development stages?

**G:** Often, yes. And here's what the exam tests: when a project ends, the system life cycle continues.

**H:** And there's also the product life cycle?

**G:** Yes — which is a commercial, market-oriented construct. Introduction, growth, maturity, decline. Very different from the engineering life cycle in ISO 15288.

**H:** So three different constructs — system life cycle, project life cycle, product life cycle — don't confuse them.

**G:** That's exactly what the exam wants you to know.

**H:** Perfect setup for Track 2, where we go stage by stage. Stay with us.

---

## 🎙️ Track 2 — The Six Life Cycle Stages: A Stage-by-Stage Tour
*(Est. runtime: ~8 minutes)*

**H:** Let's walk through all six ISO 15288 life cycle stages one by one. You've described them as a "tour." What's the opening stop?

**G:** We start at the Concept Stage — and this is arguably the most important stage for SE.

**H:** Why most important?

**G:** Because everything that follows flows from decisions made here. The Concept Stage is where stakeholder needs are identified, alternatives are explored, and a preferred solution concept is selected.

**H:** And the key artefact?

**G:** The Concept of Operations — the ConOps. It describes how the system will be used by operators in the real world.

**H:** And what the exam tests on this stage?

**G:** That the acquirer has the most influence here, before design commitments are made. Once you're into Development, changing direction costs much more.

**H:** Next: Development.

**G:** The Development Stage is the SE-intensive stage. Requirements are refined and baselined. Architecture and design are defined. The system is built, integrated, verified, and validated.

**H:** That's a lot in one stage.

**G:** It is. And it's where the largest share of SE resources are applied. Verification and validation both occur here.

**H:** Then Production.

**G:** Production is often misunderstood. You're not designing here — you're manufacturing instances of the system against the approved configuration.

**H:** And testing in Production is different from testing in Development?

**G:** Critical distinction for the exam. Development testing verifies the *design*. Production testing verifies that manufactured instances *conform to the approved configuration*.

**H:** Fourth: Utilisation.

**G:** The system is operated in its intended environment. SE activities here are monitoring, anomaly capture, and supporting operational decisions.

**H:** Fifth: Support.

**G:** Support is about sustaining availability. Corrective maintenance — fixing failures. Preventive — scheduled servicing. Adaptive — modifications for changed needs.

**H:** And many programmes underestimate this stage.

**G:** Dramatically. In defence, the Support Stage often runs for 20–30 years and dominates total life cycle cost.

**H:** And the final stage: Retirement.

**G:** Retirement is decommissioning, disposal, archiving, knowledge transfer. And the exam tip here: failure to plan for retirement in the Concept Stage creates nasty surprises — think hazardous materials, nuclear decommissioning costs, stranded data.

**H:** Six stages, all essential. Up next: the gatekeepers between them.

---

## 🎙️ Track 3 — Decision Gates: The Gatekeepers of the Life Cycle
*(Est. runtime: ~7 minutes)*

**H:** Every time a system moves from one stage to the next, something formal has to happen. That's the topic of Track 3 — decision gates.

**G:** A decision gate is a formal review point at the boundary between life cycle stages. The purpose: assess whether the exit criteria for the current stage have been met, and authorise — or deny — progression.

**H:** What are the possible outcomes?

**G:** Four. Proceed. Conditional Proceed. Return — back to the current or a previous stage. Or Terminate.

**H:** Terminate sounds dramatic.

**G:** But it's a legitimate outcome. If a system concept is fundamentally flawed, terminating at a Concept Stage gate is far cheaper than discovering that in Production.

**H:** Now — named reviews. SRR, PDR, CDR. Are these ISO 15288 requirements?

**G:** This is a classic exam trap. ISO 15288 mandates the *principle* of decision gates with exit criteria. It does not mandate named reviews like SRR or CDR — those are programme-specific implementations.

**H:** So a programme could hold different named reviews?

**G:** Exactly. And the mapping varies. Broadly: SRR sits at the Concept-to-Development boundary. PDR is early Development, before detailed design. CDR is mid-Development, before fabrication. ORR — Operational Readiness Review — sits at the Development-to-Utilisation boundary.

**H:** And who authorises the stage transition?

**G:** Typically the acquirer authorises transitions, particularly major ones. On complex programmes, both acquirer and supplier representatives are present.

**H:** What are exit criteria exactly?

**G:** The specific conditions that must be satisfied before stage transition. They might include: all system requirements reviewed and baselined, all open technical risks closed or accepted, supplier readiness confirmed.

**H:** And if you have open items — you might get a conditional proceed?

**G:** Right. Open items are tracked with owners and close-out dates. It's a pragmatic outcome — few programmes are perfectly clean at a gate.

**H:** Decision gates: not a bureaucratic hurdle — a genuine risk management tool.

**G:** That's exactly how the exam treats them.

---

## 🎙️ Track 4 — Life Cycle Models: Choosing the Right Framework
*(Est. runtime: ~7 minutes)*

**H:** ISO 15288 defines the stages and the processes — but it doesn't say *how* you have to sequence them. That's where life cycle models come in.

**G:** Correct. A life cycle model is a framework that describes stages, decision gates, and the overall approach. ISO 15288 deliberately separates process definitions from model selection.

**H:** So the model is chosen per programme?

**G:** Yes — and tailored to the programme's specific characteristics.

**H:** Let's go through the main models. Start with sequential.

**G:** Sequential — sometimes called waterfall-like. Stages run in order, one substantially complete before the next begins. Clear gates, clear deliverables.

**H:** When does it work?

**G:** Stable requirements. Mature technology. Regulatory frameworks requiring strict stage separation — nuclear, medical devices, aviation certification.

**H:** Iterative?

**G:** Multiple cycles through requirements, design, build, and V&V — each cycle more complete than the last. Best when requirements will evolve or when risk must be managed through early prototyping.

**H:** Concurrent?

**G:** Multiple stages overlap to compress schedule. You start Production planning while Development is still ongoing. High risk — upstream changes can cascade expensively.

**H:** Evolutionary?

**G:** Deliver the system in capability increments. Each increment is usable. Common in large defence programmes — think Block 1, Block 2, Block 3 capability deliveries.

**H:** And Agile SE — which is increasingly relevant.

**G:** Agile SE puts iterative sprint cycles within an overarching SE framework. And here's the exam distinction: Agile SE manages the full system life cycle, interfaces, and system-level V&V. Pure Agile software development does not.

**H:** So a software team can sprint — but the SE layer still manages the system.

**G:** Exactly. The system requirements, architecture, and system-level verification don't happen in sprints — they sit above them.

**H:** And life cycle model tailoring?

**G:** Adapting the chosen model to your programme's specific risks, constraints, and regulations. ISO 15288 expects this. Applying a standard model blindly without tailoring is poor SE practice.

**H:** Track 5 tackles the concept that trips up the most candidates. Don't miss it.

---

## 🎙️ Track 5 — Processes vs Stages: The Most Tested Distinction
*(Est. runtime: ~7 minutes)*

**H:** Track 5 — this is the one our expert tells me is the most heavily tested topic in Week 2. Processes versus stages.

**G:** It trips up experienced engineers, not just students. Let me make it crystal clear.

**H:** Go ahead.

**G:** A life cycle *stage* answers the question "When?" It is a period in the system's evolution. It is bounded by decision gates.

**H:** And a process?

**G:** A life cycle *process* answers "What?" It is a set of interrelated activities with defined inputs, outputs, and outcomes. And — crucially — it can be applied in *any* applicable stage.

**H:** Give us an example.

**G:** Take Verification. The Verification process is defined in ISO 15288 as a Technical Process. It runs in the Development Stage to verify the design. But it also runs in the Production Stage to verify manufactured instances. And in the Support Stage to verify a system after maintenance.

**H:** So the same process in three different stages.

**G:** Same process, different application. The process doesn't care which stage you're in.

**H:** Now — how many processes does ISO 15288 define?

**G:** Thirty. Across four process groups.

**H:** Name the four groups.

**G:** Technical Processes — fourteen of them. Technical Management Processes — eight. Agreement Processes — two. Organisational Project-Enabling Processes — six.

**H:** And the exam trap you mentioned?

**G:** The "Development process" trap. Candidates hear "Development Stage" and assume there must be a corresponding process called "Development." There is no such process in ISO 15288.

**H:** So what does the work of development?

**G:** The fourteen Technical Processes — requirements definition, architecture, design, implementation, integration, verification, validation, and so on. Those are invoked within the Development Stage. But they're also invoked in other stages.

**H:** Configuration Management — which process group?

**G:** Technical Management Processes, ISO 15288 §6.3.

**H:** And the Agreement Processes?

**G:** Two: Acquisition and Supply. They govern the acquirer-supplier relationship.

**H:** Stages tell you when. Processes tell you what. Never confuse them.

**G:** Say that ten times before your exam.

---

## 🎙️ Track 6 — Cost of Change: Why Early SE Investment Pays
*(Est. runtime: ~6 minutes)*

**H:** Track 6. This is where we make the economic case for Systems Engineering. The cost-of-change curve.

**G:** Also called the cost-of-correction curve. The fundamental finding: the cost of correcting an error increases exponentially with life cycle progression.

**H:** Who proved this?

**G:** Barry Boehm, in his 1981 research on software development. SEH5 cites this work. The numbers: fixing an error in the Concept Stage might cost one unit. The same error found in Development: ten times. In Production: a hundred times. In Utilisation: potentially a thousand times.

**H:** Exponential is a strong word.

**G:** It's empirically supported. And the implication is profound for SE strategy.

**H:** Which is?

**G:** Front-load your SE effort. Invest heavily in requirements, architecture, and V&V planning in the Concept and early Development stages — because finding issues there is cheap.

**H:** This is the SE value proposition.

**G:** Exactly. Spend more early. Spend far less overall. The total life cycle cost goes down.

**H:** Speaking of total life cycle cost — LCC. What is it?

**G:** Life Cycle Cost is the total cost across all stages — concept through retirement — including acquisition, operation, maintenance, and disposal.

**H:** And why does that matter?

**G:** Because acquisition cost — what you pay to build the system — is often only 20 to 30 percent of total LCC. The other 70 to 80 percent is incurred operating and supporting the system.

**H:** So optimising for low acquisition cost is misleading?

**G:** It can produce a system that's cheap to build but expensive to operate and maintain. SE should optimise for minimum LCC, not minimum acquisition cost.

**H:** And the exam will test this?

**G:** Almost certainly. A question will offer an option like "start Production earlier to reduce acquisition cost" — that's the wrong answer. Early Production with immature requirements drives up total cost via rework.

**H:** Spend smart early. The life cycle cost curve rewards it.

---

## 🎙️ Track 7 — Closing Recap: Week 2 High-Yield Summary
*(Est. runtime: ~4 minutes)*

**H:** We're at the recap. Week 2 in 90 seconds. Fire away.

**G:** Six life cycle stages: Concept, Development, Production, Utilisation, Support, Retirement. In that order. Each bounded by decision gates.

**H:** Decision gates.

**G:** Four outcomes: Proceed, Conditional Proceed, Return, Terminate. ISO 15288 mandates the principle — not the named reviews like SRR and CDR. Those are programme choices.

**H:** Life cycle models.

**G:** Sequential for stable requirements. Iterative for evolving requirements. Concurrent for schedule compression at higher risk. Evolutionary for incremental capability delivery. Agile SE wraps iterative sprints in an SE framework.

**H:** Processes vs stages.

**G:** The most tested concept. Stages = when. Processes = what. Processes can run in any stage. There is no "Development process" in ISO 15288 — the work of development is done by the 14 Technical Processes.

**H:** Cost of change.

**G:** Exponential increase with life cycle progression. Boehm's research. Invest early. Optimise for Life Cycle Cost, not acquisition cost.

**H:** Three things to do before Week 3?

**G:** First: draw the cost-of-change curve from memory and annotate each stage. Second: build the process group / life cycle stage matrix and confirm which processes run where. Third: practice stating the process-vs-stage distinction out loud until it's second nature.

**H:** Week 3 takes us into the Technical Processes — starting with Business/Mission Analysis and Stakeholder Needs Definition. That's where the real SE depth begins. See you there.

---

*Document Version: 1.0 | Created: 2026-04-14 | Source: INCOSE SEH5 Ch2; ISO/IEC/IEEE 15288:2023 §6*
