# Corpus Documents and Summary Analysis

## Overview Statistics

- **Total Documents**: 6
- **Total Words**: 56 296
- **Total Types**: 12 334
- **Average Ratio**: 0.237
- **Average Words/Sentence**: 26.06

## Document Statistics

| ID    | Title                                                   | Voyant Name                                            | Words | Types | Ratio | Words/Sentence | Readability Index | Comment                                                                                |
| ----- | ------------------------------------------------------- | ------------------------------------------------------ | ----: | ----: | ----: | -------------: | ----------------: | -------------------------------------------------------------------------------------- |
| PS-01 | Implementation of Buckingham's Pi theorem using Python  | Implementation of Buckingham's Pi theorem using Python |  5778 |  1376 | 0.238 |          25.45 |            23.052 | Highest readability score, distinctive use of Python and mathematical symbols (π, ρ) |
| PS-02 | Self-similarity of parallel machines                    | Self-similarity of parallel machines                   | 10370 |  2230 | 0.215 |          22.35 |            12.413 | Notable for parallel computing terms and unique coefficient analysis                   |
| PS-03 | Computer performance analysis and the Pi Theorem        | PS-03 - Numrich - 2014                                 | 20765 |  3996 | 0.192 |          26.90 |            15.583 | Longest document, extensive use of cache analysis terms                                |
| PS-04 | Computational forces in the SAGE benchmark              | PS-04 - Numrich - 2009                                 |  9348 |  2106 | 0.225 |          26.41 |            12.651 | Focus on computational forces with unique mathematical notation                        |
| PS-05 | Computational forces in the Linpack benchmark           | doi:10.1016/j.jpdc.2008.02.008                         |  3246 |  1020 | 0.314 |          29.24 |            12.619 | Shortest document but highest vocabulary diversity                                     |
| PS-06 | Dimensional Analysis Applied to a Parallel QR Algorithm | Title                                                  |  6789 |  1606 | 0.237 |          26.11 |            14.256 | Focus on dimensional analysis with QR-specific terminology                             |

## Column Descriptions

- **ID**: Primary Study identifier (PS-XX format)
- **Title**: Standardized document title
- **Voyant Name**: Original name used in Voyant Tools analysis
- **Words**: Total number of words in the document
- **Types**: Number of unique word types (vocabulary size)
- **Ratio**: Type-to-token ratio (vocabulary diversity)
- **Words/Sentence**: Average number of words per sentence
- **Readability Index**: Measure of text complexity
- **Comment**: Key characteristics and distinctive features

## Corpus-wide Analysis

### Most Frequent Words

- analysis (221)
- dimensional (159)
- machines (152)
- machine (147)
- efficiency (145)

### Key Insights

1. **Document Size Distribution**:

   - Largest: PS-03 (20765 words)
   - Smallest: PS-05 (3246 words)
   - Significant size variation (6.4x difference)
2. **Vocabulary Characteristics**:

   - Highest diversity: PS-05 (ratio: 0.314)
   - Lowest diversity: PS-03 (ratio: 0.192)
   - Average ratio across corpus: 0.237
3. **Readability Patterns**:

   - Most complex: PS-01 (23.052)
   - Most accessible: PS-02 (12.413)
   - Average readability: 15.096
4. **Document-Specific Features**:

   **PS-01**:

   - Focus: Python implementation
   - Key symbols: repeating (36), rv (35), python (34), ρ (42), π (39)

   **PS-02**:

   - Focus: Parallel computing
   - Key terms: ub (24), mixing (23), þ (20), coefficient (20), sgi (18)

   **PS-03**:

   - Focus: Performance analysis
   - Key elements: λ (67), b1 (53), θ (45), b2 (37), cache (93)

   **PS-04**:

   - Focus: SAGE benchmark
   - Distinctive: τ (40), u0 (38), l1,2x (23), cells (18), ε (17)

   **PS-05**:

   - Focus: Linpack benchmark
   - Notable: λ2 (18), λ1 (18), fs (14), fb (13), kn2 (12)

   **PS-06**:

   - Focus: QR Algorithm
   - Specific: γ (23), henry (10), word (13), 256 (8)
5. **Corpus Themes**:

   - Strong focus on mathematical and technical content
   - Consistent use of mathematical symbols across documents
   - Emphasis on performance analysis and computational benchmarking
   - Significant parallel computing and dimensional analysis components

## Other Notes

1. **Document Size Variation**: There's significant variation in document length, with the longest document (PS-03) being 6.4x longer than the shortest (PS-05).
2. **Vocabulary Diversity**: PS-05 has the highest vocabulary density (ratio: 0.314), suggesting more diverse vocabulary relative to its length.
3. **Readability**: PS-01 has the highest readability score (23.052), making it potentially the most complex to read.
4. **Mathematical Content**: Many distinctive words are mathematical symbols (π, ρ, λ, θ, τ, ε, γ, þ), indicating the mathematical nature of the corpus.
5. **Technical Focus**: The most frequent words (analysis, dimensional, machines, machine, efficiency) reflect the technical computing and performance analysis focus of the corpus.
