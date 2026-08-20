# BAES Research

**Document Status:** Public Research Index  
**Project Status:** Under Development  
**Last Updated:** 2026-08-20

---

## 1. Purpose

The `research/` area records the public research direction of the
**Babak AI Engineering Standard (BAES)**.

Its purpose is to document research questions, research areas,
methodological direction, and publicly releasable research artifacts
that contribute to the development and validation of BAES.

This directory is not intended to expose unreleased foundational
research or internal development material.

---

## 2. Role of Research in BAES

Research provides a bridge between:

```text
Engineering Question
        ↓
Research
        ↓
Evidence
        ↓
Evaluation
        ↓
Principle / Requirement
        ↓
Specification
````

Research therefore serves an important role in determining whether
candidate concepts should remain exploratory, become established
principles, or eventually contribute to normative requirements.

Research does not automatically produce normative requirements.

---

## 3. Research Principles

BAES research is guided by the following principles:

### 3.1 Question Before Conclusion

A research activity should begin with an explicit question or problem.

### 3.2 Evidence Before Assertion

Claims should not be treated as established merely because they are
plausible.

### 3.3 Separation of Observation and Interpretation

Observed results should be distinguished from interpretations,
hypotheses, and conclusions.

### 3.4 Explicit Uncertainty

Research should identify relevant uncertainty and limitations.

### 3.5 Traceability

Where practical, research findings should be traceable to the
questions, methods, evidence, and conclusions from which they arose.

### 3.6 Reproducibility Where Applicable

Research should be reproducible when the nature of the research permits
it.

### 3.7 Controlled Publication

Research material should be published according to its maturity and
the BAES publication policy.

---

## 4. Public Research Areas

The public research program may eventually cover areas such as:

* Human–AI collaboration
* Human engineering authority
* Delegated authority
* Scope control
* AI participation models
* Traceability
* Evidence evaluation
* Human approval
* Engineering inquiry
* Governance
* Reviewability
* Human–AI decision processes
* Evaluation methodologies
* Domain-general applicability
* Conformance and validation

The exact research program will evolve as BAES development progresses.

---

## 5. Research Questions

Research questions should address identifiable engineering uncertainties.

Examples include:

* How should authority be represented in Human–AI collaboration?
* How can delegated authority be bounded?
* How can unauthorized scope expansion be detected or prevented?
* What information is necessary for meaningful traceability?
* How should evidence associated with AI-generated claims be evaluated?
* Which Human–AI interactions require explicit human approval?
* How can Human–AI collaboration be evaluated across different domains?
* Which BAES mechanisms remain domain-general?
* Which mechanisms require domain-specific adaptation?

These are examples of research directions rather than claims that the
questions have already been answered.

---

## 6. Research and Evidence

BAES distinguishes between research activity and evidence validity.

The fact that a study, experiment, analysis, or observation exists does
not automatically establish the validity of its conclusions.

A research artifact may therefore have an independent status and
evidence assessment.

Conceptually:

```text
Research Artifact
       ↓
Finding
       ↓
Evidence Assessment
       ↓
Interpretation
       ↓
Potential Engineering Consequence
```

This relationship will become more formally defined as the BAES
evidence model matures.

---

## 7. Research Status

Research artifacts may use statuses such as:

* Proposed
* Planned
* In Progress
* Completed
* Under Review
* Published
* Superseded

The final research lifecycle will be established as the project
matures.

---

## 8. Research Artifacts

Future public research artifacts may include:

* Research questions
* Research plans
* Methodology documents
* Experimental designs
* Public datasets
* Evaluation results
* Analysis reports
* Research papers
* Evidence assessments
* Research summaries

Only artifacts approved for publication should become part of the
public research record.

---

## 9. Restricted Research

Some research may remain unpublished during development.

This may include:

* Unreleased foundational research
* Preliminary findings
* Internal experiments
* Unpublished conceptual models
* Research containing unfinished or strategically sensitive material
* Material requiring further validation before publication

The absence of such material from the public repository must not be
interpreted as evidence that the research does not exist.

Publication is governed separately by:

`docs/publication-policy.md`

---

## 10. Research Does Not Automatically Become Specification

A research result may inform BAES without becoming a normative
requirement.

The intended progression is:

```text
Research
   ↓
Finding
   ↓
Assessment
   ↓
Engineering Interpretation
   ↓
Candidate Principle
   ↓
Validation
   ↓
Potential Requirement
```

Each transition requires appropriate justification.

---

## 11. Negative and Contradictory Results

BAES research should not selectively preserve only results that support
existing assumptions.

Where appropriate, the research record should also preserve:

* Negative results
* Failed experiments
* Contradictory observations
* Unexpected outcomes
* Known limitations
* Alternative interpretations

Such results may be important for preventing unsupported conclusions and
for improving the standard.

---

## 12. Research Review

As BAES matures, research artifacts may undergo different forms of
review, including:

* Internal review
* Technical review
* Methodological review
* Evidence review
* Independent review
* Public review

The applicable review level should depend on the importance and
maturity of the research artifact.

---

## 13. Research Traceability

Where practical, public research artifacts should be traceable to the
BAES concepts, principles, or requirements they inform.

A future traceability relationship may resemble:

```text
Research Question
       ↓
Research Artifact
       ↓
Finding
       ↓
Evidence
       ↓
Principle
       ↓
Requirement
       ↓
Specification
```

The final traceability model remains under development.

---

## 14. Research Naming and Identification

A formal identifier scheme for BAES research artifacts has not yet
been finalized.

A future scheme may introduce identifiers such as:

```text
RES-001
EXP-001
EVD-001
```

The final naming convention will be established as the research
governance model matures.

---

## 15. Current Research Position

BAES is currently developing its research and evidence architecture.

The immediate objective is not to publish a large volume of research.

The immediate objective is to establish a disciplined structure in
which future research can be:

* Clearly identified
* Properly scoped
* Methodologically described
* Evaluated
* Traced
* Reviewed
* Published responsibly

---

## 16. Guiding Principle

The current working research principle is:

> **Research should reduce uncertainty before uncertainty is converted
> into normative engineering requirements.**

---

## 17. Related Documents

* `docs/current-status.md`
* `docs/roadmap.md`
* `docs/publication-policy.md`
* `governance/README.md`
* `records/README.md`

