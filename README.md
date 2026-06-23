# CV Exploration

> Exploring how research information can be efficiently presented through CVs.

---

## Project Motivation

Traditional CV design often focuses on aesthetics and formatting.

This project instead treats a CV as an **information transmission medium**.

The core question is:

> How can research information be efficiently communicated through a CV?

The goal is not to design a prettier CV, but to understand the underlying principles behind research information presentation.

---

## Research Question

This project explores:

> Research information presentation in CVs.

Specifically:

* How should research information be organized?
* What design choices improve information transmission efficiency?
* How can maintainability and scalability be improved?
* What might be the future evolution of Research CVs?

---

## Workflow

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

## Current Template Corpus

### Core Objects

| ID  | Name           | Category                           |
| --- | -------------- | ---------------------------------- |
| T06 | Awesome-PhD-CV | Researcher-oriented Template       |
| T07 | MujiCV         | Content-first Platform             |
| T11 | RenderCV       | Data-driven System                 |
| T12 | JSON Resume    | Information Standardization System |

### Supplementary Objects

| ID  | Name            | Category                  |
| --- | --------------- | ------------------------- |
| T02 | ModernCV        | Classic Academic Baseline |
| T08 | AltaCV          | Modern Academic Baseline  |
| T09 | FortySecondsCV  | Minimal Academic Baseline |
| T13 | Reactive Resume | Interactive Platform      |

### Real-world Objects

| ID  | Name            | Category                              |
| --- | --------------- | ------------------------------------- |
| R01 | Jitendra Malik  | Senior Researcher CV / Homepage       |
| R02 | Fei-Fei Li      | Institutional Researcher Profile      |
| R03 | Peter Norvig    | Text-first Personal Resume            |
| R04 | Radford Neal    | Minimal Researcher Homepage           |

---

## Design Features

Each object is analyzed through five dimensions.

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

> (Currently under discussion)

---

## Evaluation Framework

Five dimensions are used.

* Overall
* Information Efficiency
* Academic Professionalism
* Visual Quality
* Maintainability

---

## Repository Structure

```text
docs/

├── working_notes/
├── template_corpus/
│   ├── T02_moderncv/
│   │   ├── README.md
│   │   └── CV.pdf
│   └── ...
├── methodology.md
└── design_guideline.md

evaluation/

templates/

assets/
```

Each corpus object uses one folder.

```text
docs/template_corpus/<ID_slug>/

README.md          # introduction and analysis
CV.pdf             # direct visual preview artifact
showcase/          # source display assets and provenance notes
```

For template objects, `CV.pdf` should use an official sample whenever one is available. If the source only provides images, `CV.pdf` may be generated from those official images. Each `showcase/SOURCE.md` records the exact source and any limitations.

---

## Current Status

### Completed

* [x] Research question definition
* [x] Workflow construction
* [x] Design feature framework
* [x] Initial evaluation framework
* [x] Initial template corpus
* [x] Initial real-world researcher corpus
* [x] Initial official showcase assets for template objects

### Ongoing

* [ ] Expand template corpus
* [ ] Broaden real-world researcher CV coverage
* [ ] Refine evaluation framework
* [ ] Build design guidelines

---

## Open Questions

### OQ-01

Communication vs Information boundaries.

### OQ-02

How can star ratings become more objective?

### OQ-03

Should real-world researcher CVs be introduced?

### OQ-04

Should Template and Platform be placed in the same corpus?

### OQ-05

What is the future evolution path of Research CVs?

```text
Template-driven

↓

Platform-driven

↓

Data-driven ?
```
