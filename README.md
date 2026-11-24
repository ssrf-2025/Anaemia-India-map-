# SAMPADA anaemia prevalence by state/UT: interactive map

Interactive choropleth of anaemia prevalence (%) by state/UT across eight population groups, from the ICMR-NIN SAMPADA national survey (2023-25).

**Live map:** https://ssrf-2025.github.io/sampada-anaemia-map/

## Data
- Source: ICMR-National Institute of Nutrition. *Anaemia and Micronutrient Deficiencies Across the Life Course in India: Evidence from the SAMPADA National Survey (2023-2025)*. Hyderabad: ICMR-NIN; 2026. Annexure table.
- Values were transcribed manually from the annexure; see `sampada_state_anaemia.csv`. Please verify against the original before reuse.
- Anaemia defined with WHO 2024 haemoglobin cut-offs (venous samples, automated analysers).
- 95% CIs are not shown here. Several state estimates have wide CIs, so colour differences between neighbouring states may not be statistically meaningful.
- Manipur has no estimate in the annexure.

## Limitations
- Cross-sectional data; no causal inference.
- Boundaries come from an open dataset (datameet-derived, simplified) and are illustrative, not an official depiction.

## Use
Open `index.html` in a browser. It is a single self-contained file with no dependencies.

## Licence
Code: MIT (add a LICENSE file). Survey data remain the property of ICMR-NIN; check their terms before redistribution.
