# CSEP Week 3 — Practice Questions: Business/Mission Analysis & Stakeholder Needs
**Topic:** INCOSE SEH5 Chapter 3 — Technical Processes (Part 1A); ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018
**Format:** 20 CSEP-style multiple-choice questions — single best answer
**Coverage:** 30% recall | 50% conceptual application | 20% distinguishing confused concepts

---

## Questions

**Q1.** According to ISO/IEC/IEEE 15288:2023, what is the purpose of the Business or Mission Analysis (BMA) process?

A) To produce the System Requirements Specification used to contract the supplier
B) To define the business or mission problem, characterise the solution space, and justify that a system is an appropriate response
C) To design the system architecture and allocate requirements to subsystems
D) To verify that the delivered system meets the stakeholder requirements baseline

---

**Q2.** A product director insists that the team has already "decided to build a new logistics platform" and instructs the systems engineer to skip BMA and move directly into stakeholder requirements. Which response best reflects correct SE practice?

A) Comply — BMA is optional once the solution direction is decided
B) Decline — BMA must always include a full market analysis before any solution direction is considered
C) Push back — BMA distinguishes the problem space from the solution space, and a premature solution commitment risks building the wrong system; BMA should still be performed to validate (or challenge) the proposed direction
D) Comply — BMA is an acquirer activity and not a supplier responsibility

---

**Q3.** Which of the following best distinguishes a Concept of Operations (ConOps) from an Operational Concept (OpsCon) as defined in ISO/IEC/IEEE 29148:2018?

A) ConOps is written in §4.2 and OpsCon is written in §5.2; there is no viewpoint difference
B) ConOps takes the acquirer/user viewpoint and describes how the capability will be used in the operational environment; OpsCon takes the system/developer viewpoint and describes the system's operational characteristics, modes, and interactions
C) ConOps applies to military systems and OpsCon applies to commercial systems
D) ConOps is a regulatory document; OpsCon is an engineering document

---

**Q4.** A stakeholder states: "The system should be easy to use." Why is this statement, as written, not yet a stakeholder requirement?

A) It uses the word "should" instead of "shall"
B) It has not been approved by the Change Control Board
C) It is ambiguous and not verifiable — there is no single interpretation and no method to confirm the need has been met
D) It describes a business need and must first be converted to a business requirement

---

**Q5.** Which of the following is NOT one of the nine requirement characteristics defined in ISO/IEC/IEEE 29148:2018 §5.2?

A) Unambiguous
B) Verifiable
C) Prioritised
D) Singular

---

**Q6.** A systems engineer writes the following stakeholder requirement: *"The system shall support at least 10,000 concurrent users and shall respond to queries within 200 ms."* Which characteristic of ISO 29148 §5.2 does this statement primarily violate?

A) Feasible
B) Singular
C) Conforming
D) Correct

---

**Q7.** Which of the following is the best example of a Measure of Effectiveness (MoE), as opposed to a Measure of Performance (MoP)?

A) CPU utilisation of the application server shall not exceed 70% at peak load
B) The system shall process 500 transactions per second
C) The logistics operation shall achieve a mission success rate of at least 95% per monthly cycle
D) Database query latency shall be less than 50 ms at the 95th percentile

---

**Q8.** In which ISO/IEC/IEEE 15288:2023 process is the stakeholder requirements baseline produced?

A) §6.4.1 Business or Mission Analysis
B) §6.4.2 Stakeholder Needs and Requirements Definition
C) §6.4.3 System Requirements Definition
D) §6.4.4 Architecture Definition

---

**Q9.** A programme identifies an external cyber-attacker as a relevant actor for the system. In ISO 15288 stakeholder identification terms, this actor is best characterised as:

A) Not a stakeholder — only parties with a legitimate interest qualify
B) A supplier — because the system must procure security capability from the attacker's techniques
C) An adversarial stakeholder — an actor whose interests are in conflict with the system's mission; identifying them supports defining what the system must resist
D) A regulator — because cybersecurity is governed by regulation

---

**Q10.** An analyst has interviewed five operators individually and believes the operator needs are now well understood. Which critique of this approach best reflects SE best practice on elicitation?

A) Individual interviews are not a valid elicitation technique under ISO 29148
B) Five operators is too few — CSEP requires a minimum sample size of 20
C) No single elicitation technique is sufficient; good practice triangulates using two or more techniques — for example, adding observation of operators in context or a workshop to surface group dynamics
D) Interviews should never be used; only workshops are acceptable for stakeholder elicitation

---

**Q11.** Which of the following best describes the relationship between a "stakeholder need" and a "stakeholder requirement" in SN&RD?

A) They are synonyms used interchangeably in ISO 15288
B) A stakeholder need is expressed in the stakeholder's own language and may be aspirational or ambiguous; a stakeholder requirement is the engineered statement of that need, written unambiguously and verifiably
C) A stakeholder requirement is produced only by the acquirer; a stakeholder need is produced only by the user
D) A stakeholder need is always a shall-statement; a stakeholder requirement is always a prose description

---

**Q12.** The ISO 15288 requirements hierarchy has six levels. Which of the following lists them in the correct top-to-bottom order?

A) Stakeholder need → Business need → Stakeholder requirement → System requirement → Subsystem requirement → Component requirement
B) Business need → Stakeholder need → Stakeholder requirement → System requirement → Subsystem requirement → Component requirement
C) System requirement → Stakeholder requirement → Stakeholder need → Business need → Subsystem requirement → Component requirement
D) Business requirement → Stakeholder requirement → System requirement → Subsystem requirement → Component requirement → Element requirement

---

**Q13.** Which of the following is the most accurate statement of the verification/validation distinction (ISO 15288 §3)?

A) Verification and validation are synonyms applied at different stages
B) Verification confirms that specified requirements have been met (did we build the system right?); validation confirms that the system satisfies stakeholder needs in the intended operational environment (did we build the right system?)
C) Verification applies to hardware; validation applies to software
D) Validation precedes verification in the ISO 15288 process order

---

**Q14.** Which of the following is the best description of the purpose of baselining stakeholder requirements at the close of SN&RD?

A) To mark the project as complete so the team can be reassigned
B) To fix a formally approved, configuration-controlled reference against which downstream work is judged, change impacts are assessed, and the acquirer-supplier contract is anchored
C) To prevent any further changes to the requirements under any circumstances
D) To satisfy an audit checkbox with no downstream engineering consequence

---

**Q15.** A programme lists the following as outputs of BMA: (i) preliminary ConOps, (ii) business requirements, (iii) MoEs, (iv) architecture diagrams showing software module decomposition. Which item does NOT belong as a BMA output?

A) (i) preliminary ConOps
B) (ii) business requirements
C) (iii) MoEs
D) (iv) architecture diagrams showing software module decomposition

---

**Q16.** During SN&RD, a stakeholder demands a requirement that the system shall "provide all possible user functionality that any operator might ever need." Which ISO 29148 §5.2 characteristic or characteristics does this statement most clearly violate?

A) Singular and Conforming
B) Unambiguous and Feasible
C) Verifiable only
D) Correct only

---

**Q17.** A project team proposes to skip OpsCon development, arguing that the preliminary ConOps from BMA is sufficient for the Development Stage. Which response best reflects SE practice?

A) Accept — once the ConOps exists, the OpsCon is redundant
B) Challenge — ConOps and OpsCon take different viewpoints (acquirer vs system); the OpsCon elaborates system modes, operational characteristics, and interface behaviours that the ConOps does not cover; whether to produce a formal OpsCon artefact is a tailoring decision, but the content is typically needed
C) Accept — OpsCon is only required for defence systems
D) Challenge — ConOps is never produced in BMA; only OpsCon is produced

---

**Q18.** A power-interest matrix is used to prioritise stakeholder engagement. Which of the following statements about this tool is most accurate?

A) ISO 15288 mandates the use of the power-interest matrix for all programmes
B) The matrix is presented in SEH5 as one supporting practice for stakeholder analysis; it is not mandated by ISO 15288, and alternative analytical approaches may be used
C) The matrix is prohibited by ISO 15288 because it introduces subjectivity into stakeholder analysis
D) The matrix is used only in BMA, never in SN&RD

---

**Q19.** Which of the following verification methods is most appropriate for a requirement stating: *"The system enclosure shall be painted matte black to RAL 9005, applied to all external surfaces visible to the operator"*?

A) Test — operate the system and measure enclosure colour under load
B) Analysis — perform mathematical modelling of paint reflectance
C) Inspection — examine the enclosure against the specified colour standard and coverage criterion
D) Demonstration — show the paint being applied to the enclosure

---

**Q20.** Which of the following statements about the direction of information flow between BMA and SN&RD is most accurate?

A) SN&RD outputs feed BMA inputs; BMA always follows SN&RD in the process order
B) BMA and SN&RD operate independently and do not exchange information
C) BMA outputs (preliminary ConOps, business requirements, MoEs, stakeholder identification) feed SN&RD inputs; the reverse flow is incorrect in the standard process order
D) Both directions are equally valid; the order is determined by the programme's life cycle model

---

## Answer Key and Rationale

**Q1 — B**
ISO/IEC/IEEE 15288:2023 §6.4.1.1 states the purpose of BMA as defining the business/mission problem, characterising the solution space, and justifying a system response. Option A describes System Requirements Definition (§6.4.3). Option C describes Architecture Definition (§6.4.4). Option D describes Validation (§6.4.12).

**Q2 — C**
BMA's primary value is separating problem space from solution space. A premature solution commitment risks building the wrong system (SEH5 Ch3). Even when a direction has been "decided," BMA should be performed to validate or challenge that decision. Options A and D misrepresent BMA as optional or supplier-only; Option B overstates mandatory activities.

**Q3 — B**
ISO/IEC/IEEE 29148:2018 §4.2 defines ConOps as acquirer/user-viewpoint ("how the capability will be used"); §4.3 defines OpsCon as system/developer-viewpoint ("system operational characteristics, modes, interactions"). Option A has the clause numbers wrong. Options C and D misattribute domain-specific applicability.

**Q4 — C**
ISO 29148 §5.2 requires requirements to be Unambiguous and Verifiable. "Easy to use" admits multiple interpretations and has no verification method, failing both. Option A confuses style with substance. Option B conflates formal approval with intrinsic quality. Option D is not the primary defect — converting to a business requirement would not fix the ambiguity.

**Q5 — C**
The nine characteristics in ISO 29148 §5.2 are: Necessary, Appropriate, Unambiguous, Complete, Singular, Feasible, Verifiable, Correct, Conforming. "Prioritised" is a requirement attribute in some frameworks but is *not* one of the nine characteristics.

**Q6 — B**
The statement combines two requirements ("concurrent users" and "response time") with "and shall." ISO 29148 §5.2 requires each requirement to be Singular — one statement, one requirement. The correct form is to split them into two separate requirements. Options A, C, and D are not the primary defect.

**Q7 — C**
MoEs are mission/business-level measures of mission success. A mission success rate of 95% per monthly cycle is mission-level. Options A, B, and D are system-level performance measures (MoPs), not MoEs. (SEH5 Ch3; SEBoK "Measures")

**Q8 — B**
The stakeholder requirements baseline is produced at the close of §6.4.2 Stakeholder Needs and Requirements Definition. BMA produces business requirements and preliminary ConOps, not the stakeholder requirements baseline. §6.4.3 produces the system requirements baseline. §6.4.4 produces the architectural baseline. (ISO 15288 §6.4.2)

**Q9 — C**
ISO 15288 stakeholder identification includes adversarial stakeholders — actors whose interests conflict with the system's mission. Identifying them is essential for defining what the system must resist (e.g., security requirements). Option A misunderstands stakeholder scope. Option B is nonsensical. Option D is too narrow — an attacker is not a regulator.

**Q10 — C**
Good SE practice triangulates across multiple elicitation techniques because each has blind spots (SEH5 Ch3; INCOSE GtWR). Five individual interviews miss group dynamics, tacit contextual knowledge, and groupthink artefacts. Observation, workshops, or prototyping can surface what interviews miss. Options A, B, and D are factually wrong.

**Q11 — B**
Stakeholder *needs* are expressed in stakeholder language — often aspirational and ambiguous. Stakeholder *requirements* are engineered — unambiguous, verifiable, and singular. The transformation of one into the other is the core work of SN&RD. (ISO 29148; ISO 15288 §6.4.2)

**Q12 — B**
The correct top-to-bottom ordering is: Business/mission need → Stakeholder need → Stakeholder requirement → System requirement → Subsystem requirement → Component/element requirement. (SEH5 Ch3; SEBoK "System Requirements")

**Q13 — B**
ISO 15288 §3 distinguishes verification (specified requirements met — "right system built") from validation (stakeholder needs met in intended environment — "right system built right"). Options A, C, and D are incorrect.

**Q14 — B**
A baseline is a formally approved, configuration-controlled reference. Its purposes include anchoring the acquirer-supplier contract, serving as the reference for impact analysis, and providing a stable foundation for downstream work. Baselines do not prevent change — they channel change through controlled processes. (SEH5 Ch3; ISO 15288 §6.4.2)

**Q15 — D**
BMA produces preliminary ConOps, business requirements, MoEs, preferred solution class, and justification. Software module decomposition is an Architecture Definition (§6.4.4) output, not a BMA output. BMA characterises the *solution space*, not specific decompositions.

**Q16 — B**
"All possible user functionality that any operator might ever need" is both unbounded (Unambiguous violation — multiple interpretations) and unachievable within any finite cost/schedule (Feasible violation). Option A (Singular/Conforming) is not the primary defect. Options C and D understate the problems. (ISO 29148 §5.2)

**Q17 — B**
ConOps (acquirer viewpoint) and OpsCon (system viewpoint) are complementary, not redundant. The OpsCon describes system modes, operational characteristics, and interface behaviours absent from ConOps. Whether a separate formal OpsCon artefact is produced is a tailoring decision, but the content is typically required by downstream processes. (ISO 29148 §4.2 and §4.3)

**Q18 — B**
The power-interest matrix is a common practice introduced in SEH5 as one analytical technique for stakeholder prioritisation. ISO 15288 does not mandate it. Programmes may use other approaches (e.g., salience model) as appropriate. (SEH5 Ch3)

**Q19 — C**
Inspection — examination of documentation, code, or physical properties without operating the system — is the appropriate verification method for a colour/coverage requirement. Test (operation and measurement) is overkill and may not address coverage. Analysis (mathematical modelling) is not needed. Demonstration would not confirm the colour against the RAL standard rigorously.

**Q20 — C**
The ISO 15288 process order places BMA (§6.4.1) before SN&RD (§6.4.2). BMA outputs (preliminary ConOps, business requirements, MoEs, stakeholder identification) feed SN&RD inputs. The reverse flow is incorrect, though iteration may occur in practice — that is refinement, not a reversal of the standard direction. (ISO 15288 §6.4.1 and §6.4.2)

---

*Document Version: 1.0 | Created: 2026-04-18 | Source: INCOSE SEH5 Ch3; ISO/IEC/IEEE 15288:2023 §6.4.1 and §6.4.2; ISO/IEC/IEEE 29148:2018*
