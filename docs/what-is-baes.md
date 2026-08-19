# What Is BAES?

**BAES — Babak AI Engineering Standard**

**Document Status:** Working Definition
**Project Status:** Under Development
**Last Updated:** 2026-08-19

---

## 1. Definition

**BAES (Babak AI Engineering Standard)** is a vendor-neutral engineering standard for systematically designing, governing, and evaluating **Human–AI collaboration for real-world problem solving across domains**.

BAES defines an engineering-oriented framework for understanding and structuring situations in which humans and AI systems participate together in the pursuit of an intended outcome.

The purpose of BAES is not to prescribe a particular AI model, software product, platform, programming language, organization, or technical implementation.

Instead, BAES focuses on the **engineering relationship between human participants, AI participants, intent, authority, scope, actions, decisions, evidence, governance, and outcomes**.

---

## 2. The Central Idea

BAES treats Human–AI collaboration as an engineering problem.

An AI system may participate in activities such as:

* Analysis
* Reasoning
* Research
* Generation
* Planning
* Evaluation
* Transformation
* Decision support
* Execution
* Verification
* Other forms of structured problem solving

However, participation does not by itself establish authority.

BAES therefore seeks to make the relationship between:

```text
Human Intent
     ↓
Authority
     ↓
Delegation
     ↓
AI Participation
     ↓
Actions
     ↓
Evidence
     ↓
Evaluation
     ↓
Outcome
```

explicit, structured, and traceable.

---

## 3. Human and AI Roles

BAES does not define AI as a replacement for human engineering responsibility.

The fundamental direction of BAES is that:

> **AI may participate in engineering activity without becoming the source of human intent or governance authority.**

Human participants may define:

* Intent
* Objectives
* Scope
* Constraints
* Authority boundaries
* Governance requirements
* Approval conditions

AI systems may then operate within the authority and scope explicitly available to them.

The precise mechanisms for delegation, execution, review, escalation, and approval are part of the ongoing development of the BAES specification.

---

## 4. Engineering Authority

A central concept in BAES is the distinction between **authority** and **participation**.

An AI system may have delegated authority to perform a particular action without acquiring general authority over the overall problem.

Accordingly:

> **Authority may be delegated; responsibility for human intent and governance is not thereby transferred.**

BAES therefore investigates and formalizes distinctions such as:

* Human Engineering Authority
* Governance Authority
* Execution Authority
* Delegated Authority
* Scope Authority

These distinctions are intended to prevent implicit authority expansion during Human–AI collaboration.

---

## 5. Scope

BAES is intentionally **domain-general**.

It is not restricted to software engineering.

Potential application domains include, but are not limited to:

* Software engineering
* Scientific research
* Education
* Knowledge work
* Technical analysis
* Business and organizational problem solving
* Engineering disciplines
* Research assistance
* Decision-support environments
* Other structured Human–AI problem-solving contexts

The applicability of BAES to a particular domain must be evaluated according to the requirements and characteristics of that domain.

Domain-general scope does not imply that every BAES mechanism will be applicable without adaptation.

---

## 6. What BAES Is Not

BAES is not:

### 6.1 An AI Model

BAES does not define or provide a foundation model, language model, multimodal model, or AI agent.

### 6.2 A Software Application

BAES is not an application that users install or execute.

Software may implement BAES-related mechanisms, but the standard itself is not software.

### 6.3 An AI Framework

BAES does not require a particular AI framework, orchestration system, agent framework, or development stack.

### 6.4 A Vendor-Specific Method

BAES is not designed around a particular AI provider, model family, platform, or commercial ecosystem.

### 6.5 A Programming Methodology

BAES is not a programming methodology and is not limited to software development.

### 6.6 An Autonomous AI Governance System

BAES does not transfer governance authority to AI systems.

Its purpose is to provide an engineering structure within which Human–AI collaboration can be designed and governed.

### 6.7 A Claim That AI Is Always Correct

BAES does not assume that AI outputs are correct, reliable, complete, or safe.

Evaluation, evidence, verification, uncertainty, and review are therefore relevant parts of the engineering model.

---

## 7. Vendor Neutrality

BAES is intended to remain independent of particular vendors.

The standard should therefore be applicable regardless of whether an AI participant is provided by:

* A commercial vendor
* An open-source project
* A locally hosted model
* A privately developed system
* A research system
* A future AI technology

Vendor neutrality is intended to ensure that BAES principles describe the **engineering relationship**, rather than the capabilities or policies of a particular provider.

---

## 8. Technology Neutrality

BAES is not tied to a specific implementation technology.

A BAES-conformant implementation may involve:

* Cloud-based AI
* Local AI
* Self-hosted systems
* APIs
* Agent systems
* Human-operated interfaces
* Automated workflows
* Hybrid systems
* Technologies that do not yet exist

Technology may change while the underlying engineering requirements remain meaningful.

---

## 9. Domain Generality

The problems addressed by BAES are not inherently specific to one profession or technical discipline.

The common element is the existence of a structured collaboration in which:

1. A human or human group establishes an intended purpose.
2. An AI system participates in one or more activities.
3. Authority and scope may be delegated.
4. Actions or outputs are produced.
5. Evidence may be generated or evaluated.
6. Results require assessment against intended outcomes.

BAES seeks to provide a common engineering language for reasoning about these relationships.

---

## 10. Engineering Rather Than Prompting

BAES is not primarily a collection of prompting techniques.

Prompting may be one implementation mechanism used within a Human–AI system, but BAES operates at a broader engineering level.

The relevant questions include:

* What is the intended outcome?
* Who established the intent?
* What authority was delegated?
* What is the permitted scope?
* What actions may the AI perform?
* What evidence is required?
* What requires human approval?
* What happens when uncertainty is detected?
* How are decisions recorded?
* How can the process be reviewed?
* How can the result be evaluated?

These questions remain relevant regardless of the specific prompting technique used.

---

## 11. Engineering Rather Than Automation

BAES does not equate greater automation with better Human–AI collaboration.

Automation may increase efficiency, but it may also increase:

* Scope ambiguity
* Authority ambiguity
* Error propagation
* Irreversible actions
* Loss of traceability
* Difficulty of review

BAES therefore treats automation as an engineering decision subject to authority, scope, governance, evidence, and evaluation requirements.

---

## 12. Core Concerns

The developing BAES model currently focuses on several recurring concerns:

### Human Intent

How is the intended purpose established and preserved?

### Authority

Who has authority to define, change, approve, or execute an action?

### Delegation

What authority may be delegated to an AI participant, and under what conditions?

### Scope

What is the AI permitted to do, and what lies outside its authorized scope?

### Traceability

Can significant decisions, actions, changes, and outcomes be reconstructed?

### Evidence

What supports a claim, decision, or conclusion?

### Evaluation

How is an AI contribution or Human–AI outcome assessed?

### Governance

How are decisions, changes, conflicts, exceptions, and approvals controlled?

### Reviewability

Can the resulting process and its important decisions be independently examined?

These concerns are being progressively formalized through BAES development.

---

## 13. The Scope Boundary

BAES is concerned with the **engineering of Human–AI collaboration**.

It does not attempt to standardize every aspect of artificial intelligence, human behavior, organizational management, or a particular application domain.

A useful conceptual boundary is:

```text
                 BAES
                  │
        Human–AI Collaboration
                  │
     ┌────────────┼────────────┐
     │            │            │
   Intent      Authority     Scope
     │            │            │
     └────────────┼────────────┘
                  │
              AI Action
                  │
             Evidence
                  │
             Evaluation
                  │
               Outcome
```

Domain-specific requirements may exist outside BAES and may need to be integrated with BAES when it is applied in a particular context.

---

## 14. BAES as an Engineering Standard

BAES is intended to evolve from a conceptual and research foundation into a formal engineering standard.

The intended development progression is:

```text
Concepts
   ↓
Principles
   ↓
Ontology
   ↓
Evidence
   ↓
Requirements
   ↓
Validation
   ↓
Review
   ↓
Specification
   ↓
Release
```

Not every concept identified during development will necessarily become a normative requirement.

This distinction is fundamental to the development process.

---

## 15. Evidence and Maturity

BAES distinguishes between the maturity of a concept and the validity of the evidence supporting it.

A concept may be identified as a candidate without being sufficiently validated to become a normative requirement.

Likewise, an established project decision may later be revised if new evidence demonstrates that the underlying assumption is inadequate.

Therefore, BAES development maintains a distinction between:

```text
Concept / Decision Status
           ≠
Evidence Validity
```

This distinction supports controlled evolution and discourages premature formalization.

---

## 16. The BAES Development Principle

BAES is intended to apply its own engineering philosophy to its development.

The project therefore emphasizes:

* Documentation before implementation
* Explicit decisions
* Controlled delegation
* Traceability
* Evidence-aware development
* Independent reviewability
* Controlled scope evolution
* Human authority over project intent and governance

In this sense, the development of BAES itself is intended to serve as an ongoing engineering case study of the principles being developed.

---

## 17. Current Maturity

BAES is currently under active development.

The project has established a foundational body of concepts and principles, while several areas remain under ontology discovery, formalization, research, and validation.

BAES is therefore **not yet presented as a finalized normative standard**.

The current objective is to establish a sufficiently rigorous foundation from which a mature specification can be developed and independently examined.

For the current development state, see:

`docs/current-status.md`

For the planned development path, see:

`docs/roadmap.md`

---

## 18. Working Definition

The current working definition of BAES is:

> **BAES is a vendor-neutral engineering standard for systematically designing, governing, and evaluating Human–AI collaboration for real-world problem solving across domains.**

This definition is authoritative for the current project stage but remains subject to controlled revision as BAES development progresses.

---

## 19. Repository Role

The BAES repository serves as the:

> **Public Engineering Record of the BAES project.**

The repository is intended to preserve the evolution of the standard, including its concepts, principles, decisions, research, evidence, reviews, revisions, and releases.

The public record should make it possible for an external reader to understand not only **what BAES currently says**, but also **how and why it came to say it**.

---

## 20. Related Documents

* [Current Status](current-status.md)
* [Development Roadmap](roadmap.md)

Additional sections of the BAES documentation will be added as the standard matures.
