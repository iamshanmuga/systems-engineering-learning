# CSEP Week 1 — Flashcard Deck
**Topic:** Systems Engineering Overview & Fundamentals
**Format:** Question (Front) | Answer (Back)
**Total Cards:** 57 | **Sections:** Days 1–6 topics (SE Introduction, Systems Thinking & Principles, SE Context & Standards Overview)
**How to use:** Cover the Answer column; read the Question; say your answer aloud; then check.
Mark cards: ✅ Known | 🔄 Review | ❌ Re-study

---

## 📦 Section 1 — SE Introduction (Cards 1–20)
*Covers: Days 1 & 2 — What is SE? + Systems Key Concepts & Vocabulary*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 1 | What is the INCOSE definition of Systems Engineering? | "An interdisciplinary approach and means to enable the realization of successful systems. It focuses on defining customer needs and required functionality early in the development cycle, documenting requirements, then proceeding with design synthesis and system validation while considering the complete problem." |
| 2 | What is the ISO/IEC/IEEE 15288 definition of Systems Engineering? | A set of processes, methods, and techniques for defining, realising, sustaining, and retiring a system-of-interest. |
| 3 | Define: System | A set of interacting or interdependent elements forming a unified whole with a defined boundary, operating in an environment to achieve defined objectives. |
| 4 | Define: System-of-Interest (SoI) | The specific system that is being analysed, designed, or developed in the context of a project or study. |
| 5 | Define: Enabling System | A system that provides services needed to support the system-of-interest during one or more life cycle stages (e.g., test bench, training simulator). |
| 6 | Define: System Element | Any constituent part of a system — hardware, software, data, processes, personnel, or facilities. |
| 7 | Define: Emergence | A system-level property that arises from interactions among system elements but is not possessed by any single element alone. |
| 8 | Give two examples of enabling systems for a commercial aircraft. | Test rigs/simulators (development stage) and airline maintenance ground equipment (support stage). |
| 9 | What problem does SE solve that traditional single-discipline engineering cannot? | Managing complexity, interdisciplinary interfaces, and emergent behaviour to ensure the system-as-a-whole meets stakeholder needs. |
| 10 | Name three types of complexity SE is designed to manage. | Technical complexity, organisational complexity, and operational complexity. |
| 11 | What is a system boundary? | The conceptual or physical line that separates the system-of-interest from its external environment. |
| 12 | What is the operational environment? | The external context (physical, organisational, and informational) in which the system will function during the utilization stage. |
| 13 | What is an open system? | A system that exchanges matter, energy, or information with its external environment. Most real engineering systems are open. |
| 14 | What is a closed system? | A system that does not exchange with its environment — a theoretical abstraction; most real systems are open. |
| 15 | Why is SE sometimes called an "integrating" discipline? | Because it coordinates all engineering disciplines and ensures their outputs combine into a coherent, requirement-satisfying whole. |
| 16 | What distinguishes a system from a collection of parts? | A system has defined interactions, interfaces, and emergent properties; a collection of parts does not. |
| 17 | What does "holistic" mean in SE? | Considering and managing the system as a whole, not just optimising individual parts in isolation. |
| 18 | Give a real-world example of an emergent property. | Traffic jams from individual driving behaviour; internet reliability from individual unreliable nodes; aircraft lift from wings alone. |
| 19 | Name three primary reasons for SE project failures (per INCOSE). | Unclear or unstable requirements, poor interface management, and inadequate verification/validation. |
| 20 | What is the CSEP exam format? | 120 questions (100 scored + 20 unscored pilot), 120 minutes, multiple choice, single correct answer, based on INCOSE SEH 5th Edition. |

---

## 📦 Section 2 — Systems Thinking & SE Principles (Cards 21–50)
*Covers: Days 3, 4 & 5 — Systems Thinking, SE Principles Part 1 & Part 2*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 21 | What is systems thinking? | An approach to problem solving that views issues as part of a wider, dynamic system — considering feedback loops, time delays, and non-linear causality rather than isolating individual cause-and-effect chains. |
| 22 | Who founded General Systems Theory, and when? | Ludwig von Bertalanffy in the 1940s–1950s. |
| 23 | What is reductionist (analytical) thinking? | Breaking a problem into parts, solving each part separately, then reassembling — assumes the whole equals the sum of its parts. |
| 24 | Why is reductionist thinking insufficient for complex systems? | Because it ignores emergent properties and interactions between parts that only manifest at the system level. |
| 25 | Who developed System Dynamics, and what is it? | Jay Forrester — a method for modelling and simulating complex systems using feedback loops, time delays, and non-linear relationships. |
| 26 | Who wrote "Thinking in Systems"? | Donella Meadows. |
| 27 | Who wrote "The Fifth Discipline" on systems thinking? | Peter Senge. |
| 28 | What is a "wicked problem"? | A problem that is difficult or impossible to solve because of incomplete, contradictory, or changing requirements — used to describe many complex SE challenges. |
| 29 | What is negative (balancing) feedback? Give an example. | Feedback that reduces deviation from a goal. Example: a thermostat — if temperature drops, heating activates to restore the set point. |
| 30 | What is positive (reinforcing) feedback? Give an example. | Feedback that amplifies deviation from a reference. Example: microphone placed near a speaker causes a runaway audio feedback loop. |
| 31 | Name three characteristics of complex systems. | Non-linearity, feedback loops, emergent behaviour, self-organisation, path dependence (any 3). |
| 32 | What is the key contrast between systems thinking and reductionist thinking? | Reductionist: whole = sum of parts, linear causality. Systems thinking: whole ≠ sum of parts, non-linear feedback, emergent properties. |
| 33 | Define: Holism (SE Principle) | The principle that a system must be understood and managed as a whole; the whole is greater than — or different from — the sum of its parts. |
| 34 | Define: Hierarchy (SE Principle) | The principle that systems exist within systems — elements nest within subsystems, which nest within systems, which may form a system-of-systems. |
| 35 | Define: Abstraction (SE Principle) | Representing a system at a level of detail appropriate to the problem, suppressing irrelevant detail to reduce cognitive complexity. |
| 36 | Define: Encapsulation (SE Principle) | Hiding the internal implementation of a system element behind a well-defined interface so internal details do not affect other elements. |
| 37 | Define: Modularity (SE Principle) | Designing a system as a set of loosely coupled, highly cohesive elements whose internal details are hidden from each other. |
| 38 | What is the difference between encapsulation and modularity? | Encapsulation focuses on hiding internal details behind an interface (information hiding). Modularity focuses on the structure of the system as loosely coupled, cohesive units. They are complementary. |
| 39 | Give an example of hierarchy in a military system. | System-of-Systems (Joint Force) → System (Warship) → Subsystem (Combat Management System) → Element (Radar sensor). |
| 40 | Give an example of abstraction in SE practice. | A UML block definition diagram represents a system's logical structure without specifying circuit-level electrical details. |
| 41 | Define: Separation of Concerns (SE Principle) | Addressing different aspects of a system (e.g., function, performance, safety, cost) independently to reduce complexity and allow parallel work. |
| 42 | Define: Feedback (SE Principle) | A mechanism whereby information about a system's outputs is used to influence its inputs or behaviour, enabling control and adaptation. |
| 43 | Define: Evolvability (SE Principle) | Designing a system to accommodate future changes in requirements, technology, or operational environment without requiring complete redesign. |
| 44 | What is an interface in SE? | The shared boundary between two system elements across which signals, data, energy, material, or humans pass. |
| 45 | Why is interface management critical in SE? | Most system integration failures occur at interfaces — poorly defined or uncontrolled interfaces lead to emergent defects and integration failures. |
| 46 | What is separation of concerns useful for in large engineering teams? | It allows different teams to work on different aspects (functional design, safety analysis, cost modelling) simultaneously without coupling their work. |
| 47 | Give an example of feedback in a human-machine system. | An aircraft autopilot: actual altitude is fed back and compared to target altitude; the difference drives control surface adjustments. |
| 48 | Why should evolvability be designed in from the start? | Requirements and environments change — retrofitting evolvability is far more expensive than building in modular, adaptable architecture from the outset. |
| 49 | What is the practical consequence of a poorly defined interface? | Integration failures, unexpected emergent behaviour, cost overruns, and schedule delays when the two elements are brought together. |
| 50 | Name the eight SE Principles covered in SEH5 Chapter 3. | Holism, Hierarchy, Abstraction, Encapsulation, Modularity, Separation of Concerns, Feedback, Evolvability. |

---

## 📦 Section 3 — SE Context, Stakeholders & Standards Overview (Cards 51–55)
*Covers: Day 6 — SE in Practice, ISO 15288 Overview, CSEP Exam*

| # | 🃏 QUESTION (Front) | ✅ ANSWER (Back) |
|---|---|---|
| 51 | Who is a "stakeholder" in SE? | Any individual, organisation, or group with a legitimate interest in the system — including users, operators, acquirers, maintainers, regulators, and developers. |
| 52 | Name three stakeholder types for a railway signalling system. | Train operators (users), infrastructure managers/Network Rail (acquirers), and safety regulators (regulatory authority). |
| 53 | What are the four ISO/IEC/IEEE 15288 process groups? | 1. Agreement Processes, 2. Organizational Project-Enabling Processes, 3. Technical Management Processes, 4. Technical Processes |
| 54 | What is the purpose of the ISO/IEC/IEEE 15288 standard? | To define the processes required to conceive, develop, produce, operate, maintain, and retire systems throughout their life cycle. |
| 55 | What is the primary INCOSE reference for the CSEP exam? | INCOSE Systems Engineering Handbook, 5th Edition (SEH5), which is aligned with ISO/IEC/IEEE 15288:2023. |
| 56 | Name three common SE project failure modes per INCOSE research. | 1. Unclear or unstable requirements, 2. Poor interface management (undefined or uncontrolled interfaces), 3. Inadequate verification and validation (defects found too late). |
| 57 | What is the role of the SE team on a project? | The SE team acts as an integrating function — coordinating all engineering disciplines, managing interfaces, ensuring requirements flow through to design and verification, and maintaining system-level coherence. |

---

*Flashcard Deck Version: 2.0 | Updated: 2026-04-03 | Source: INCOSE SEH 5th Edition + ISO/IEC/IEEE 15288:2023*
*Next deck: week_02_flashcards.md — System Life Cycle Concepts (Cards covering the six life cycle stages, life cycle models, and tailoring)*
