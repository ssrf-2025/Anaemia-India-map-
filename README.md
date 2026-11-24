# SAMPADA anaemia prevalence by state/UT: interactive map

Interactive choropleth of anaemia prevalence (%) by state/UT across eight population groups, from the ICMR-NIN SAMPADA national survey (2023-25).

**Live map:** [https://ssrf-2025.github.io/Anaemia-India-map-/]

## Data
- Source: ICMR-National Institute of Nutrition. *Anaemia and Micronutrient Deficiencies Across the Life Course in India: Evidence from the SAMPADA National Survey (2023-2025)*. Hyderabad: ICMR-NIN; 2026. Annexure table.
- Values were transcribed manually from the annexure; see `sampada_state_anaemia.csv`. Please verify against the original before reuse.
- Anaemia defined with WHO 2024 haemoglobin cut-offs (venous samples, automated analysers).
- 95% CIs are not shown here. Several state estimates have wide CIs, so colour differences between neighbouring states may not be statistically meaningful.
- Manipur has no estimate in the annexure.

## NFHS-5 context
The info box and CSV also show NFHS-5 (2019-21) state values (IIPS/MoHFW fact sheets, via MoSPI) for the nearest age groups. These are not directly comparable (different age bands, capillary Hb, WHO 2011 cut-offs). NFHS-6 (2023-24) fact sheets, released May 2026, contain no anaemia indicators.

## Limitations
- Cross-sectional data; no causal inference.
- Boundaries come from an open dataset (datameet-derived, simplified) and are illustrative, not an official depiction.

## Use
Open `index.html` in a browser. It is a single self-contained file with no dependencies.

## Licence and credits

**Code:** MIT Licence (see the `LICENSE` file). Copyright (c) 2026 [Your Name].

**Data:** The anaemia estimates belong to their original sources and are not covered by the MIT Licence:
- SAMPADA 2023-25 estimates: ICMR-National Institute of Nutrition, *Anaemia and Micronutrient Deficiencies Across the Life Course in India* (Hyderabad: ICMR-NIN; 2026).
- NFHS-5 (2019-21) values: IIPS and Ministry of Health and Family Welfare, state fact sheets, accessed via MoSPI.
- Please check the original publishers' terms before redistributing the data.

**Boundaries:** State outlines are derived from an open India districts dataset ([source name and link]) and simplified. They are illustrative and not an official depiction of India's boundaries. Check that dataset's licence for attribution requirements.

**Disclaimer:** Values were transcribed manually and have not been independently verified. This map is provided as is, without warranty. Use the original publications for any official or published work.## Licence
Code: MIT 
