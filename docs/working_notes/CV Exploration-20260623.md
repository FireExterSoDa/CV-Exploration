# Working Notes

Date: 2026-06-23

Checkpoint: C1 (Foundation Established)

---

## One-sentence Summary

> Today we transformed an abstract Research CV idea into a structured, reproducible, and GitHub-based research project.

---

# New Decisions

## D-01 Workflow Established

The project workflow was fixed.

```text
Template Corpus
       ↓
Design Features
       ↓
Evaluation Framework
       ↓
Design Guideline
```

---

## D-02 Design Features Established

Five analysis dimensions were established.

### Layout

Spatial organization.

### Visual

Visual presentation.

### Information

Information organization.

### Technical

Long-term maintainability.

### Communication

Information transmission ability.

---

## D-03 Core Template Set Established

Three initial objects were selected.

* T02 ModernCV
* T06 Awesome-PhD-CV
* T07 MujiCV

---

## D-04 Evaluation System Updated

Numerical scoring was abandoned.

A star rating system was adopted.

Evaluation dimensions:

* Overall
* Information Efficiency
* Academic Professionalism
* Visual Quality
* Maintainability

---

## D-05 Repository Architecture Established

The final output will be a GitHub repository.

Current structure:

```text
research-cv-project/

README.md

docs/

evaluation/

templates/

assets/
```

---

## D-06 Working Notes Strategy Updated

Working notes will be organized chronologically.

Principles:

* One file per day
* Record decisions instead of conversations
* Record changes instead of repeated conclusions

---

## D-07 Template Corpus Refactored

Changed from:

```text
template_catalog.md
```

to:

```text
docs/template_corpus/

README.md

T02_moderncv.md

T06_awesome_phd_cv.md

T07_mujicv.md
```

Each template corresponds to one markdown file.

---

## D-08 Template File Structure Frozen (V1.0)

The following structure was fixed.

```text
Basic Information

↓

Star Rating

↓

Design Features

↓

ICP

↓

Notes
```

---

# Modified Decisions

## MD-01

Previous:

Use a single `template_catalog.md`.

Updated:

Use one markdown file per template.

Reason:

Improve scalability and long-term maintainability.

---

## MD-02

Previous:

Use numerical scores.

Updated:

Use star ratings.

Reason:

Avoid premature quantification and improve interpretability.

---

# New Open Questions

## OQ-01

Communication vs Information boundaries.

Status:

Frozen

---

## OQ-02

How can star ratings become more objective?

Status:

Pending

---

## OQ-03

Should real-world researcher CVs be introduced?

Status:

Pending

---

## OQ-04

Should Template and Platform be placed in the same corpus?

Status:

Pending

---

# Current Project Status

## Completed

* [x] Workflow
* [x] Design Features
* [x] Initial Evaluation Framework
* [x] Repository Architecture
* [x] Core Template Set
* [x] Working Notes Strategy

## Ongoing

* [ ] Template Corpus Expansion
* [ ] Evaluation Framework Improvement
* [ ] Design Guideline Construction

---

# Next Actions

1. Expand Template Corpus to 10~15 representative examples.

2. Continuously refine Design Features.

3. Introduce real-world researcher CVs.

4. Build Research CV Design Guideline.
