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

---

# Checkpoint C2 (Corpus Expanded)

## One-sentence Summary

> The corpus was expanded from template/platform/system examples into real-world researcher information artifacts.

---

## New Decisions

## D-09 Real Researcher Category Introduced

The corpus now includes real researcher CV, profile, resume, and homepage objects.

New objects:

* R01 Jitendra Malik
* R02 Fei-Fei Li
* R03 Peter Norvig
* R04 Radford Neal

Reason:

The project needs examples of how research information is actually communicated outside template-controlled environments.

---

## D-10 R-series IDs Introduced

Real-world researcher objects use `R` IDs instead of `T` IDs.

Reason:

Separate real-world researcher information artifacts from template, platform, and data-system objects.

---

## Modified Decisions

## MD-03

Previous:

Real-world researcher CVs were a missing category.

Updated:

Real-world researcher CVs are now included as an initial category, but coverage is not yet complete.

Reason:

The category should include multiple document types, including formal CVs, institutional profiles, personal resumes, and research homepages.

---

# Updated Project Status

## Completed

* [x] Initial real-world researcher corpus

## Ongoing

* [ ] Broaden real-world researcher coverage across career stages
* [ ] Compare template-controlled and real-world communication patterns
* [ ] Use corpus observations to refine the evaluation framework

---

# Checkpoint C3 (Corpus Object Folder Structure)

## One-sentence Summary

> Each corpus object was converted from a single markdown file into a folder containing both analysis and a visual PDF preview.

---

## New Decisions

## D-11 Corpus Object Folder Convention Established

Each object now uses the following structure.

```text
docs/template_corpus/<ID_slug>/

README.md
CV.pdf
```

`README.md` stores the introduction and analysis.

`CV.pdf` stores a direct visual preview artifact.

Current PDF previews are generated from the corpus notes. They may later be replaced by official samples or compiled template outputs.

---

## Modified Decisions

## MD-04

Previous:

Each template corresponded to one markdown file.

Updated:

Each corpus object corresponds to one folder containing one markdown analysis file and one PDF preview.

Reason:

The corpus should support both analytical reading and quick visual inspection.

---

# Checkpoint C4 (Official Showcase Assets Added)

## One-sentence Summary

> Template objects now include source-display assets from official links or official repositories.

---

## New Decisions

## D-12 Showcase Folder Established

Template objects now include a `showcase/` folder when official display assets are available.

```text
docs/template_corpus/<ID_slug>/

README.md
CV.pdf
showcase/
SOURCE.md
```

`showcase/` stores original or source-derived display artifacts such as PDFs, screenshots, and preview images.

`SOURCE.md` records where each artifact came from and notes any limitations.

---

## Modified Decisions

## MD-05

Previous:

`CV.pdf` could be a generated preview artifact based on corpus notes.

Updated:

For template objects, `CV.pdf` should prefer an official sample PDF. If no official PDF is available, it may be generated from official preview images or an official webpage screenshot.

Reason:

Direct visual inspection should reflect the original template source as much as possible.

---

## Notes

* T02 uses a concrete Overleaf preview and preserves CTAN package files because the CTAN moderncv package does not ship a rendered CV sample.
* T07 uses an official homepage screenshot because no public downloadable CV template sample was exposed on the official page.
* T09 and T12 use PDFs generated from official preview images because their sources provide images rather than a single canonical PDF.
