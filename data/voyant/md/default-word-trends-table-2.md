# Default Word Trends Analysis - Part 2

## Relative Frequency of Terms Across Documents

| ID | Title | Voyant Name | machine* | analysis | dimensional | efficiency | parameters |
|-----|---------|-------------|----------|----------|-------------|------------|------------|
| PS-01 | Implementation of Buckingham's Pi theorem using Python | Implementation of Buckingham's Pi theorem using Python | 0.0010384 | 0.0032883 | 0.0069228 | 0.0000000 | 0.0005192 |
| PS-03 | Computer performance analysis and the Pi Theorem | PS-03 - Numrich - 2014 | 0.0031303 | 0.0044787 | 0.0022634 | 0.0016855 | 0.0022634 |
| PS-04 | Computational forces in the SAGE benchmark | PS-04 - Numrich - 2009 | 0.0081301 | 0.0037441 | 0.0024604 | 0.0050278 | 0.0025674 |
| PS-02 | Self-similarity of parallel machines | Self-similarity of parallel machines | 0.0097396 | 0.0033751 | 0.0022179 | 0.0008679 | 0.0039537 |
| PS-05 | Computational forces in the Linpack benchmark | doi:10.1016/j.jpdc.2008.02.008 | 0.0075122 | 0.0026513 | 0.0017676 | 0.0047135 | 0.0023568 |
| PS-06 | Dimensional Analysis Applied to a Parallel QR Algorithm | Title | 0.0070856 | 0.0064695 | 0.0043130 | 0.0067776 | 0.0033888 |

## Key Observations

### Highest Frequency Terms by Document:

- **PS-01**: Highest **dimensional** frequency (0.0069228), lowest **machine*** and **efficiency**
- **PS-02**: Highest **machine*** frequency (0.0097396), focused on parallel machine concepts
- **PS-03**: Highest **analysis** frequency (0.0044787), balanced parameter usage
- **PS-04**: Strong **machine*** (0.0081301) and **efficiency** (0.0050278) focus
- **PS-05**: Balanced **machine*** (0.0075122) and **efficiency** (0.0047135)
- **PS-06**: High **analysis** (0.0064695) and **efficiency** (0.0067776) frequencies

### Term Usage Patterns:

1. **machine***: 
   - Highest in PS-02 (0.0097396)
   - Strong presence in PS-04 (0.0081301)
   - Lowest in PS-01 (0.0010384)

2. **analysis**:
   - Most consistent across documents
   - Peak in PS-06 (0.0064695)
   - Lowest in PS-05 (0.0026513)

3. **dimensional**:
   - Highest in PS-01 (0.0069228)
   - Moderate in PS-06 (0.0043130)
   - Low in other documents

4. **efficiency**:
   - Zero in PS-01 (0.0000000)
   - Highest in PS-06 (0.0067776)
   - Strong in PS-04 (0.0050278)

5. **parameters**:
   - Most consistent term across documents
   - Peak in PS-02 (0.0039537)
   - Lowest in PS-01 (0.0005192)

### Document Characteristics:

- **PS-01**: Strong dimensional analysis focus, minimal machine/efficiency content
- **PS-02**: Machine-centric with balanced parameter analysis
- **PS-03**: Balanced analysis approach across all terms
- **PS-04**: Performance and machine-focused
- **PS-05**: Balanced machine and efficiency analysis
- **PS-06**: Strong analytical and efficiency focus

*Note: Values represent relative frequencies (term occurrences per total words). The asterisk (*) indicates wildcard matching for word variants.*
