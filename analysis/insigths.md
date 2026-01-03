# ANALYSIS INSIGHTS

This is a comprehensive profile of the analytical insights, research findings, and related work synthesized during the Systematic Literature Review (SLR) on Dimensional Analysis (DA) in Software Architecture. The insights are organized across multiple analytical stages of the review process, from research question answers to related work analysis and primary study documentation.

[Back to top](#analysis-insights)

---

## Overview

The [analysis/notebook/](notebook/) folder contains all research insights, analytical results, and synthesized findings generated throughout the SLR analytical phase. The insights are organized into three main categories:

1. **[Research Questions](notebook/):** Direct answers to the three core research questions (RQ-01, RQ-02, RQ-03).
2. **[Related Work](notebook/):** Analysis of foundational and contextual studies (Ruzicka, Mahdavi et al., Wong et al., Hockney et al., Kredel et al.).
3. **[Primary Study Documentation](notebook/):** Classification and documentation of Numrich's work (included and excluded studies).

[Back to top](#analysis-insights)

---

## Directory Structure

### 1. Research Question Answers ([`notebook/`](notebook/))

Contains direct answers to the three research questions guiding this systematic literature review.

#### 1.1 Core Research Questions

| File                                                   | Research Question                                                                       | Focus Area                              |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------- | --------------------------------------- |
| **[`RQ-01-answer.md`](notebook/RQ-01-answer.md)** | What are the current applications of DA in modern software development or architecture? | Applications and use cases              |
| **[`RQ-02-answer.md`](notebook/RQ-02-answer.md)** | How do engineers use DA in software development or architecture?                        | Engineering practices and methodologies |
| **[`RQ-03-answer.md`](notebook/RQ-03-answer.md)** | What are the software tools associated with DA?                                         | Tooling and automation                  |

**Purpose:** These documents provide evidence-based answers synthesized from the 6 primary studies, organizing findings into structured tables with supporting evidence, patterns, and key insights.

#### 1.2 RQ-01: Applications of Dimensional Analysis

**Key Findings:**

- DA is applied in **performance modeling**, **benchmarking**, **algorithm analysis**, and **system equivalence classification**.
- Primary focus on generating **dimensionless performance metrics** for cross-platform comparison.
- Applications include identifying computational bottlenecks and optimizing parallel numerical algorithms.
- Most studies construct **performance models** and reduce system behavior into **dimensionless surfaces or metrics**.
- DA enables **cross-system comparison**, identification of **scaling limits**, and **algorithm-specific optimizations**.

**Evidence Sources:** All 6 primary studies (PS-01 through PS-06) contribute to answering RQ-01, with emphasis on:

- Buckingham Pi Theorem automation (PS-01).
- Machine self-similarity and equivalence classes (PS-02, PS-03).
- Benchmark analysis (PS-04, PS-05).
- Parallel algorithm optimization (PS-06).

#### 1.3 RQ-02: Engineering Usage Patterns

**Key Findings:**

- Engineers use DA to **model execution behavior**, **reduce complex performance formulas**, and **derive dimensionless metrics**.
- DA serves as a bridge between physical modeling concepts and computational performance optimization.
- DA is **used as a modeling and abstraction tool** to simplify complex performance metrics.
- Engineers **embed DA into tooling and code** (e.g., Python scripts) to compute dimensionless indicators.
- DA allows engineers to **design, classify, and compare system architectures** via a common mathematical language.

**Usage Patterns:**

- Decomposing program execution into dimensionless force ratios (PS-02).
- Defining systems of units for performance variables (PS-03).
- Mapping runtime behavior onto universal efficiency surfaces (PS-04).
- Simplifying multi-variable performance models (PS-05).
- Abstracting runtime complexity into geometric surfaces (PS-06).
#### 1.4 RQ-03: Software Tools and Automation

**Key Findings:**

- Primary tools include **symbolic computation libraries** (SymPy, NumPy), **numerical modeling environments**, and **benchmarking utilities**.
- Tools are used to compute π-groups, simulate runtime models, analyze performance metrics, and automate dimensional reduction.
- **No dedicated DA toolchains exist** in software architecture; most rely on repurposed symbolic or benchmarking tools.

**Tool Categories:**

- **Symbolic computation frameworks:** SymPy, NumPy for π-group automation.
- **Benchmarking platforms:** LINPACK, SAGE for structured performance data.
- **Algebraic modeling tools:** For performance decomposition and dimensional matrices.
- **Execution environment instrumentation:** For collecting runtime data for dimensional comparisons.

**Gap Identified:** Lack of specialized DA toolchains for software architecture domain; current tools are adapted from physical sciences or general-purpose symbolic computation.

[Back to top](#analysis-insights)

---

### 2. Related Work Analysis ([`notebook/`](notebook/))

Contains comprehensive analyses of foundational and contextual studies that inform the interpretation and positioning of DA in software architecture.

#### 2.1 Foundational Physics and Engineering Works

| File                                               | Author(s)      | Focus                                            | Contribution to SLR                                       |
| -------------------------------------------------- | -------------- | ------------------------------------------------ | --------------------------------------------------------- |
| **[`rw-Ruzicka.md`](notebook/rw-Ruzicka.md)** | Ruzicka (2008) | Dimensionless numbers in physics and engineering | Theoretical foundation for DA methodology                 |
| **[`rw-Hockney.md`](notebook/rw-Hockney.md)** | Hockney        | Performance modeling                             | Historical context for computational performance analysis |
| **[`rw-Kredel.md`](notebook/rw-Kredel.md)**   | Kredel         | Mathematical foundations                         | Theoretical underpinnings                                 |

**Ruzicka's Contribution:**

- Provides comprehensive overview of dimensionless numbers across transport phenomena (momentum, heat, mass).
- Clarifies two fundamental sources: Dimensional Analysis (DA) and Scaling of Equations (SE).
- Introduces concepts of **complete vs. incomplete similarity** and **intermediate asymptotics**.
- Demonstrates DA applications in microfluidics, biosystems, and multiscale modeling.
- Establishes theoretical backbone that parallels Numrich's application in software performance domain.

**Key Insight:** Ruzicka's emphasis on similarity theory and universal scaling laws directly parallels Numrich's identification of self-similarity surfaces in computational systems, demonstrating that DA transcends specific domains.

#### 2.2 Software Architecture and Self-Adaptive Systems

| File                                               | Author(s)               | Publication Year | Study Type                   | Contribution to SLR                         |
| -------------------------------------------------- | ----------------------- | ---------------- | ---------------------------- | ------------------------------------------- |
| **[`rw-Mahdavi.md`](notebook/rw-Mahdavi.md)** | Mahdavi-Hezavehi et al. | 2017             | SLR on Multiple QAs          | Gap analysis in formal methods              |
| **[`rw-Wong.md`](notebook/rw-Wong.md)**       | Wong et al.             | 2022             | SLR on Self-Adaptive Systems | Contextual landscape and research evolution |

**Mahdavi's Contribution:**

- Systematic review of architectural methods for handling multiple Quality Attributes (QAs) in self-adaptive systems.
- Identifies **performance (67%), reliability (28%), cost (31%)** as most addressed QAs.
- Reveals reliance on **utility functions, metrics, and ad hoc adaptation strategies**.
- Highlights **absence of dimensional analysis** as a formal tool for trade-off management.
- **Gap Identified:** While Mahdavi et al. report on other formal and informal modeling, they overlook DA as a viable formal tool.

**Wong's Contribution:**

- Comprehensive SLR of 293 studies on self-adaptive systems (1990-2020)
- Maps evolution through five temporal stages: foundational theory to domain-specific applications.
- Identifies **systematic underrepresentation of empirical methods** (8\% or less).
- Documents **limited formalism in trade-off mechanisms** and **ad hoc feedback loop strategies**.
- **Gap Identified:** Reveals absence of structured, physics-inspired modeling frameworks.

**Key Insight:** Both Mahdavi and Wong document the prevalence of informal, heuristic approaches in software architecture, reinforcing the need for formal analytical methods like DA.

[Back to top](#analysis-insights)

---

### 3. Primary Study Documentation ([`notebook/`](notebook/))

Contains classification and documentation of Numrich's work, distinguishing between studies included in the SLR and related works excluded for methodological reasons.

#### 3.1 Included Studies (Numrich's DA Work)

**6 Primary Studies (PS-01 through PS-06):**

- PS-01: Implementation of Buckingham's Pi Theorem Using Python (Dumka et al., 2022)
- PS-02: Self-Similarity of Parallel Machines (Numrich, 2020).
- PS-03: Computer Performance Analysis and the Pi Theorem (Numrich, 2014).
- PS-04: Computational Forces in the SAGE Benchmark (Numrich, 2009).
- PS-05: Computational Forces in the Linpack Benchmark (Numrich, 2008).
- PS-06: Dimensional Analysis Applied to a Parallel QR Algorithm (Numrich, 2008).

**Common Characteristics:**

- Explicit application of Buckingham Pi Theorem or dimensional analysis principles.
- Derivation of dimensionless groups from performance variables.
- Construction of self-similarity surfaces or equivalence classes.
- Validation through benchmark data or empirical measurements.
- Focus on cross-platform performance comparison.

#### 3.2 Excluded Numrich Works

| File                                                           | Content                                                               | Purpose                           |
| -------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------- |
| **[`Numrich-old-docs.md`](notebook/Numrich-old-docs.md)** | Documentation of 5 Numrich papers (RD-04, RD-08, RD-09, RD-10, RD-11) | Explain exclusion rationale       |
| **[`Numrich-rej-docs.md`](notebook/Numrich-rej-docs.md)** | Detailed analysis of rejected documents                               | Transparency in selection process |

**Excluded Works:**

- **RD-04:** *The Computational Energy Spectrum of a Program as It Executes* (2010).
- **RD-08:** *A Metric Space for Computer Programs and the Principle of Computational Least Action* (2008).
- **RD-09:** *A Performance Model with a Fixed Point for a Molecular Dynamics Kernel* (2009).
- **RD-10:** *A Metric Space for Productivity Measurement in Software Development* (2005).
- **RD-11:** *Performance Metrics Based on Computational Action* (2004).

**Exclusion Rationale:**

- Lack explicit dimensional analysis procedures or modeling via dimensionless numbers.
- Remain metaphorical and not empirically validated for DA.
- Do not apply or develop core DA techniques (Pi-Theorem, dimensional matrices).
- Focus on conceptual extensions (action principle, energy spectrum) rather than formal DA methodology.
- While conceptually innovative, these works fall outside the explicit DA focus of the SLR.

**Key Insight:** Numrich's broader work on computational action and physics-inspired metrics is distinguished from his explicit DA applications, ensuring SLR focus remains on validated DA methodologies.

[Back to top](#analysis-insights)

---

## Analytical Flow Summary

The analytical insights flow through the SLR synthesis phase as follows:

```
1. PRIMARY STUDY ANALYSIS
    └─> Extract DA applications, methods, and tools
    └─> Classify by research question relevance

2. EVIDENCE SYNTHESIS
    └─> Organize findings into RQ-01, RQ-02, RQ-03 answers
    └─> Identify patterns and commonalities

3. RELATED WORK CONTEXTUALIZATION
    └─> Position findings within broader literature
    └─> Identify gaps and opportunities (Mahdavi, Wong)
    └─> Establish theoretical foundations (Ruzicka)

4. DOCUMENTATION AND CLASSIFICATION
    └─> Document included primary studies
    └─> Explain exclusions with transparent rationale

5. INSIGHT GENERATION
    └─> Synthesize cross-cutting themes
    └─> Answer research questions
    └─> Identify future research directions
```

[Back to top](#analysis-insights)

---

## Quality \& Rigor

### Comprehensiveness

- ✅ All 6 primary studies analyzed and documented.
- ✅ Three research questions systematically addressed.
- ✅ 5 related works contextualized (Ruzicka, Mahdavi, Wong, Hockney, Kredel).
- ✅ 5 excluded Numrich works documented with rationale.

### Traceability

- Each insight linked to specific primary studies (PS-01 through PS-06).
- Evidence organized in structured tables with document IDs.
- Related work clearly distinguished from primary studies.
- Exclusion decisions transparently documented.

### Validation

- Findings triangulated across multiple primary studies.
- Patterns identified through cross-study comparison.
- Gaps confirmed through related work analysis.
- Tools and methods validated against actual implementations.

### Synthesis Process

To reproduce the analytical insights:

1. Review all primary studies in [data/zotero/primary-studies.csv](../data/zotero/primary-studies.csv).
2. Extract evidence for each research question systematically.
3. Organize findings into structured answer documents (RQ-01, RQ-02, RQ-03).
4. Analyze related works for positioning and gap identification.
5. Document classification decisions for transparency.
6. Synthesize cross-cutting themes and patterns.

[Back to top](#analysis-insights)

---

## Document Formats Reference

| Document Type             | File Pattern               | Purpose                     | Structure                                    |
| ------------------------- | -------------------------- | --------------------------- | -------------------------------------------- |
| Research Question Answers | `RQ-{nn}-answer.md`      | Synthesized findings per RQ | Summary, evidence table, patterns            |
| Related Work Analysis     | `rw-{Author}.md`         | Contextual study analysis   | Summary, relation to Numrich, evidence notes |
| Inclusion Documentation   | N/A (in primary studies)   | Selected study details      | Full bibliographic metadata                  |
| Exclusion Documentation   | `Numrich-{type}-docs.md` | Rejected study rationale    | Summary table, explanations                  |

[Back to top](#analysis-insights)

---

## Key Insights Summary

### Cross-Cutting Findings

1. **DA Application Pattern:** Dimensional Analysis in software architecture primarily focuses on **performance modeling through dimensionless metrics**, enabling cross-platform comparison and system equivalence classification.
2. **Methodological Gap:** While DA shows strong potential, the software architecture field lacks:
    - Dedicated DA toolchains (unlike physical sciences).
    - Systematic integration into architectural frameworks.
    - Widespread adoption beyond performance analysis.
3. **Theoretical Foundation:** Ruzicka's physics-based DA theory directly translates to software performance (Numrich's work), demonstrating universal applicability of similarity theory and scaling laws across domains.
4. **Practical Validation:** All 6 primary studies provide empirical validation through benchmarks (LINPACK, SAGE) or real systems, demonstrating DA's practical utility beyond theoretical interest.
5. **Research Opportunity:** Both Mahdavi and Wong identify the need for formal analytical methods in self-adaptive systems and quality attribute trade-off analysis, something DA can address.

### Future Research Directions

- Development of specialized DA tools for software architecture domain.
- Integration of DA into architectural decision-making frameworks.
- Expansion beyond performance to other quality attributes (reliability, security, maintainability).
- Empirical studies validating DA in industrial software development contexts.
- Cross-domain transfer of DA techniques from physics/engineering to software.

[Back to top](#analysis-insights)

---

## Notes

- **Primary Studies Count:** 6 studies explicitly applying DA in software/computational contexts.
- **Related Works Analyzed:** 5 studies providing context and positioning.
- **Excluded Numrich Works:** 5 papers on computational action (conceptually related but methodologically distinct).
- **Research Questions Addressed:** 3 core questions systematically answered with evidence.
- **Analysis Timeframe:** Primary studies spanning 2004-2022, with primary DA applications from 2008-2022.
[Back to top](#analysis-insights)

---

*Last Updated: December 29, 2025*
