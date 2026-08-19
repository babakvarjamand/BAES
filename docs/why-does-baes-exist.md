# Why Does BAES Exist?

**BAES — Babak AI Engineering Standard**

**Document Status:** Working Definition
**Project Status:** Under Development
**Last Updated:** 2026-08-19

---

## 1. Purpose

BAES exists because Human–AI collaboration is becoming an increasingly important mode of solving real-world problems, while the engineering structures used to design, govern, evaluate, and review such collaboration remain fragmented.

AI systems are increasingly capable of participating in activities that previously depended primarily on human effort, including:

* Research
* Analysis
* Planning
* Writing
* Programming
* Design
* Decision support
* Knowledge synthesis
* Evaluation
* Execution

However, capability does not automatically provide a sufficient engineering model for collaboration.

BAES is being developed to address that gap.

---

## 2. The Problem

A Human–AI interaction can appear simple:

```text
Human
  ↓
Instruction
  ↓
AI
  ↓
Output
```

Real-world problem solving is rarely this simple.

A more realistic interaction may involve:

```text
Human Intent
      ↓
Objectives
      ↓
Constraints
      ↓
Delegated Authority
      ↓
AI Actions
      ↓
Intermediate Results
      ↓
Evidence
      ↓
Human / AI Decisions
      ↓
Verification
      ↓
Final Outcome
```

As the complexity of the interaction increases, questions arise that are not adequately answered by the existence of an AI model or a prompting technique alone.

For example:

* Who defines the intended outcome?
* What authority does the AI actually have?
* What may the AI change?
* What may it not change?
* When should the AI ask for clarification?
* Which decisions require human approval?
* How can an AI action be reconstructed later?
* What evidence supports an AI-generated conclusion?
* How should conflicting evidence be handled?
* How can an AI contribution be evaluated?
* What happens when an AI system exceeds its intended scope?
* How should the collaboration evolve when the original assumptions change?

These are engineering questions.

---

## 3. Capability Is Not Governance

Increasing AI capability creates a distinction between:

> **What an AI system can do**

and:

> **What an AI system should be authorized to do.**

These are not equivalent.

An AI system may technically be capable of:

* Modifying information
* Generating decisions
* Executing actions
* Changing plans
* Producing recommendations
* Interacting with external systems

without being authorized to perform all of those activities in a particular context.

BAES therefore treats capability and authority as separate concepts.

The existence of a capability does not establish permission to exercise that capability.

---

## 4. The Scope Expansion Problem

Human–AI systems can encounter situations in which the original instruction is incomplete, ambiguous, or insufficient for the task being performed.

An AI participant may then infer additional objectives or actions.

This can produce an important failure mode:

```text
Human Intent
     ↓
AI Interpretation
     ↓
Additional Assumption
     ↓
Expanded Scope
     ↓
Action
```

The resulting action may be technically reasonable while still being unauthorized.

BAES therefore treats **uncontrolled autonomous scope expansion** as an important engineering concern.

The developing BAES principle is:

> **AI must not autonomously expand human-defined intent, scope, or objectives.**

The exact normative form and applicability of this principle remain subject to further specification and validation.

---

## 5. The Authority Problem

Traditional software systems generally operate according to explicitly designed control structures.

Human–AI systems introduce a more dynamic interaction.

An AI participant may:

* Interpret instructions
* Generate plans
* Select intermediate actions
* Produce new information
* Recommend decisions
* Request additional actions
* Adapt its behavior based on context

This creates an authority problem.

A system may need to distinguish between:

```text
What the human wants
        ↓
What the AI understands
        ↓
What the AI is authorized to do
        ↓
What the AI actually does
```

Without such distinctions, responsibility and control can become ambiguous.

BAES exists in part to provide an engineering vocabulary and structure for addressing these relationships.

---

## 6. The Delegation Problem

Human–AI collaboration often requires delegation.

A human cannot necessarily perform every intermediate operation manually.

Delegation may therefore be necessary for practical collaboration.

However:

> Delegation of an action does not necessarily imply delegation of all authority.

For example, a human may authorize an AI participant to perform a specific analytical task without authorizing it to redefine the objective of the overall project.

BAES therefore investigates controlled delegation as a fundamental component of Human–AI engineering.

---

## 7. The Traceability Problem

In complex Human–AI workflows, the final result may depend on many intermediate interactions.

Without adequate records, it can become difficult to determine:

* What was originally intended.
* What the AI was instructed to do.
* What authority was delegated.
* What assumptions were introduced.
* What decisions were made.
* What actions were performed.
* What evidence was considered.
* What changed during the process.
* Why the final result was accepted.

This creates a problem for:

* Review
* Debugging
* Accountability
* Reproducibility
* Quality assurance
* Scientific investigation
* Organizational governance

BAES therefore treats traceability as a central engineering concern.

---

## 8. The Evidence Problem

AI systems can produce highly plausible outputs without guaranteeing that those outputs are correct.

This creates an important distinction between:

```text
AI Output
    ≠
Evidence
```

An output may be:

* Correct
* Incorrect
* Incomplete
* Ambiguous
* Unsupported
* Based on unreliable information

BAES therefore does not treat AI-generated output as automatically valid evidence.

Instead, the standard seeks to establish mechanisms for distinguishing:

* Claims
* Observations
* Evidence
* Interpretations
* Decisions
* Conclusions

and for relating them appropriately.

---

## 9. The Evaluation Problem

Human–AI collaboration cannot be engineered effectively if its outcomes cannot be evaluated.

Evaluation may need to consider more than the final output.

Relevant dimensions may include:

* Correctness
* Completeness
* Relevance
* Evidence quality
* Scope adherence
* Authority adherence
* Traceability
* Reliability
* Human approval
* Process integrity
* Outcome quality

The appropriate evaluation dimensions will depend on the problem domain.

BAES therefore seeks to establish general engineering principles while allowing domain-specific evaluation criteria where necessary.

---

## 10. The Reviewability Problem

A Human–AI system should not become a black box merely because an AI system participates in it.

Important decisions and actions should, where appropriate, be sufficiently documented to allow later examination.

Reviewability matters because errors may only become visible after an outcome has been produced.

A reviewable system should make it possible to investigate questions such as:

```text
What happened?
      ↓
Why did it happen?
      ↓
Who or what authorized it?
      ↓
What information supported it?
      ↓
What alternatives existed?
      ↓
Was the action within scope?
      ↓
What should change?
```

BAES therefore considers independent reviewability an important engineering property.

---

## 11. Existing Tools Are Not the Same as an Engineering Standard

AI development already has many useful technologies and practices, including:

* Prompt engineering
* Agent frameworks
* Workflow systems
* AI safety mechanisms
* Evaluation frameworks
* Software development methodologies
* Governance frameworks
* Model specifications
* Organizational policies

These can be valuable.

BAES does not seek to replace them.

Instead, BAES addresses a different level of abstraction:

> **How should Human–AI collaboration itself be systematically engineered?**

A BAES implementation may use existing tools, methodologies, frameworks, and policies.

BAES is intended to provide an engineering structure that can remain meaningful across those implementations.

---

## 12. Why Domain Generality Matters

Human–AI collaboration is not confined to software development.

A research scientist, teacher, engineer, analyst, physician, designer, or business professional may all collaborate with AI systems in substantially different environments.

The domain-specific tasks differ, but some structural questions can remain similar:

* What is the intended outcome?
* Who establishes the intent?
* What authority is delegated?
* What is the permitted scope?
* What actions are performed?
* What evidence is available?
* How is the result evaluated?
* Who approves the outcome?

BAES therefore seeks to identify the common engineering structures underlying these different contexts.

Domain-specific requirements may then be layered on top of the common BAES foundation.

---

## 13. Why Vendor Neutrality Matters

AI technology is evolving rapidly.

Models, vendors, platforms, interfaces, and deployment architectures may change significantly over time.

A standard tied to one particular vendor or technology risks becoming obsolete as that technology changes.

BAES therefore seeks to define requirements and concepts at a level that remains meaningful across:

* Different AI providers
* Different model architectures
* Local systems
* Cloud systems
* Open systems
* Closed systems
* Agentic systems
* Future AI technologies

Vendor neutrality is therefore a mechanism for preserving the long-term applicability of the standard.

---

## 14. Why BAES Must Be Evidence-Aware

A standard can become harmful if assumptions are converted into requirements without sufficient examination.

BAES therefore distinguishes between:

```text
Idea
  ↓
Candidate
  ↓
Investigation
  ↓
Evidence
  ↓
Validation
  ↓
Normative Requirement
```

Not every candidate principle will necessarily become a requirement.

This distinction is important because BAES is intended to evolve through engineering investigation rather than through accumulation of unsupported assertions.

---

## 15. Why BAES Must Govern Its Own Development

BAES is intended to define mechanisms for structured Human–AI collaboration.

Its own development therefore provides an opportunity to apply those mechanisms to the development process itself.

The project should consequently maintain:

* Explicit decisions
* Documented assumptions
* Traceable changes
* Evidence-aware claims
* Controlled scope
* Human authority
* Reviewable development records

This creates a recursive engineering requirement:

> **A standard for engineering Human–AI collaboration should itself be developed through disciplined Human–AI engineering practices.**

The degree to which BAES can satisfy this requirement should itself remain open to evaluation.

---

## 16. The Fundamental Motivation

The fundamental motivation for BAES can be summarized as follows:

> **AI capability is advancing faster than the engineering structures used to manage complex Human–AI collaboration.**

BAES is an attempt to develop such a structure.

Its purpose is not to make AI appear more autonomous.

Its purpose is to make Human–AI collaboration more:

* Explicit
* Governable
* Traceable
* Reviewable
* Evaluatable
* Evidence-aware
* Controlled
* Adaptable

while preserving the role of humans in establishing intent and governance.

---

## 17. What BAES Ultimately Seeks to Enable

BAES seeks to enable a future in which a Human–AI collaboration can be described and evaluated systematically.

A mature BAES implementation should make it possible to answer questions such as:

```text
What problem are we solving?
        ↓
What is the intended outcome?
        ↓
Who established that intent?
        ↓
What authority exists?
        ↓
What authority was delegated?
        ↓
What may the AI do?
        ↓
What may the AI not do?
        ↓
What evidence is being used?
        ↓
How are decisions evaluated?
        ↓
What requires human approval?
        ↓
Can the process be reconstructed?
        ↓
Can the outcome be independently reviewed?
```

The exact mechanisms for answering these questions are the subject of continued BAES development.

---

## 18. Current Position

BAES is currently an actively developing engineering standard project.

The motivations described in this document represent the current rationale for the project's existence.

They are not intended to imply that all identified problems have already been empirically demonstrated to the same degree, nor that BAES has already solved them.

Claims requiring empirical validation remain subject to research and evaluation.

For the current project state, see:

`docs/current-status.md`

For the planned development path, see:

`docs/roadmap.md`

For the current working definition of BAES, see:

`docs/what-is-baes.md`

---

## 19. Summary

BAES exists because Human–AI collaboration is becoming capable of participating in increasingly complex real-world problem solving, while the engineering relationships governing **intent, authority, delegation, scope, action, evidence, evaluation, governance, and reviewability** require a more systematic treatment.

BAES seeks to provide that treatment through a vendor-neutral, domain-general engineering standard.

The objective is not to prescribe what every AI system must do.

The objective is to establish a rigorous way to engineer **how humans and AI systems work together**.

> **BAES exists to make Human–AI collaboration an explicit engineering discipline.**
