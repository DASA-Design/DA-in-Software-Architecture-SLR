# Dimensional Analysis in Software Architecture: A Systematic Literature Review

Supporting materials for a systematic literature review (SLR) on Dimensional Analysis (DA) applications in software architecture and development, following Kitchenham & Charters (2007) guidelines.

## 📊 Overview

This repository documents a rigorous three-stage SLR (Plan → Execute → Report) investigating how Dimensional Analysis traditionally used in physics and engineering and applies to software performance modeling, benchmarking, and system analysis.

**Review Scope:**
- **Time Windows:** 2010–2020 (initial) and 2010–2024 (update)
- **Sources:** ACM Digital Library, ASME, IEEE Xplore, ScienceDirect, SpringerLink
- **Primary Studies:** 6 studies from 462 candidate documents
- **Methodology:** PICO strategy, BPMN 2.0 process modeling, NLP-assisted analysis (Voyant Tools)

## 🎯 Research Questions

| ID | Question | Key Findings |
|:---:|:---|:---|
| **RQ-01** | What are the current applications of DA in software development? | Performance modeling, benchmarking, algorithm analysis, system equivalence classification |
| **RQ-02** | How do engineers use DA in software development? | Model execution behavior, derive dimensionless metrics, enable cross-platform comparison |
| **RQ-03** | What software tools are associated with DA? | SymPy, NumPy, LINPACK, SAGE; **gap identified:** no dedicated DA toolchains for software architecture |

## 📁 Repository Structure

```
├── protocol/           # SLR methodology and process documentation
│   ├── md/            # Research questions, PICO strategy, IC/EC criteria, search strings
│   ├── img/           # BPMN 2.0 workflow diagrams (PNG/SVG)
│   └── process.md     # Complete protocol profile
│
├── data/              # Search results, curated studies, and analytics
│   ├── bibliography/  # Raw search results (BibTeX, RIS, CSV)
│   ├── zotero/        # Primary studies (6 curated documents)
│   ├── voyant/        # NLP analysis (56,296 words, 7,322 unique terms)
│   └── profile.md     # Complete data profile
│
├── analysis/          # Research findings and synthesis
│   ├── notebook/      # RQ answers, related work reviews, document classification
│   └── insigths.md    # Complete analysis profile
│
└── README.md          # This file
```

## 🔬 Key Findings

**Applications:** DA enables cross-platform performance comparison through dimensionless metrics, identifies computational bottlenecks, and constructs self-similarity surfaces for system classification.

**Engineering Practices:** Engineers embed DA into Python tooling (SymPy/NumPy) to automate Buckingham Pi Theorem application, decompose execution behavior, and simplify multi-variable performance models.

**Research Gap:** Despite proven utility in 6 primary studies (2008-2022), software architecture lacks dedicated DA toolchains; current approaches repurpose symbolic computation libraries from physical sciences.

**Contextual Positioning:** Related work analysis (Mahdavi et al., Wong et al.) reveals software architecture's reliance on informal, heuristic methods for quality attribute trade-offs, reinforcing DA's potential as a formal analytical framework.

## 📖 Primary Studies

6 studies explicitly applying Buckingham Pi Theorem and dimensional analysis principles:

- **PS-01:** Buckingham's Pi Theorem implementation in Python (Dumka et al., 2022)
- **PS-02:** Self-similarity of parallel machines (Numrich, 2020)
- **PS-03:** Computer performance analysis via Pi Theorem (Numrich, 2014)
- **PS-04:** Computational forces in SAGE benchmark (Numrich, 2009)
- **PS-05:** Computational forces in LINPACK benchmark (Numrich, 2008)
- **PS-06:** Dimensional analysis for parallel QR algorithm (Numrich, 2008)

Full metadata available in [data/zotero/primary-studies.csv](data/zotero/primary-studies.csv).

## 🔍 Methodology Highlights

- **Protocol Quality:** Peer-reviewed protocol with PICO strategy alignment
- **Selection Rigor:** Dual screening (title/abstract → full text), quality scoring (threshold ≥ 0.75)
- **Data Extraction:** 16 standardized fields (10 data + 6 metadata)
- **Thematic Analysis:** Voyant Tools validation, 4-category classification scheme
- **Transparency:** BPMN 2.0 process diagrams, version-controlled protocol components

## 📚 Documentation

- **Protocol:** [protocol/process.md](protocol/process.md) - Complete SLR methodology
- **Data Profile:** [data/profile.md](data/profile.md) - Data collection and processing
- **Analysis Insights:** [analysis/insigths.md](analysis/insigths.md) - Research findings and synthesis

## 📜 License

This repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## 📌 Citation

*Publication details will be added upon article acceptance.*

---

**Repository Purpose:** Ensure transparency, reproducibility, and open access to all SLR supporting materials, enabling validation and extension by the research community.
