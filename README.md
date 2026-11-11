# Guyana Rainfall Validation Dashboard

**Assessment of NASA GPM IMERG V07 Precipitation Against Ground-Based Rainfall Observations**

**Research project:** Collaboratively Designed and Managed Flood Resilience Framework for Affected Communities in the Caribbean Region  
**Institution:** University of Louisiana at Lafayette · Louisiana Watershed Flood Center  
**Funding:** U.S. National Science Foundation, Award No. 2426270

## Research Team

| Role | Name | Contact |
|---|---|---|
| Principal Investigator | Dr. Emad Habib | [emad.habib@louisiana.edu](mailto:emad.habib@louisiana.edu) |
| Research Engineer | Dr. Mohamed Morsy | [mohamed.morsy@louisiana.edu](mailto:mohamed.morsy@louisiana.edu) |
| PhD Candidate | Gregory Williams | [gregory.williams2@louisiana.edu](mailto:gregory.williams2@louisiana.edu) |

**Explore the interactive dashboard:** https://ulfloodcenter.github.io/guyana-rainfall-validation/

## Overview

This dashboard evaluates NASA Global Precipitation Measurement (GPM) IMERG Version 07 precipitation estimates against ground-based rainfall observations in Guyana. The assessment examines the suitability of the processed IMERG rainfall field as input to a HEC-RAS 2D flood model, focusing on rainfall magnitude, timing, spatial differences, occurrence, and intense rainfall.

## Data and Approach

The primary assessment covers **2020–2021**, using **nine stations** with sufficiently complete daily observations and **6,517 paired station-days**. Daily gauge observations were compared with rainfall extracted from the nearest valid cell of the processed IMERG V07 grid. A **3 × 3 grid-cell neighborhood mean** was also examined to assess point-to-grid representativeness.

Diagnostics include cumulative percentage bias (PBIAS), daily correlation, mean absolute error (MAE), root mean square error (RMSE), wet-day detection statistics (using a 1 mm/day threshold), station-to-station variability, rainfall-intensity and monthly biases, selected storm events, and sensitivity to the daily accumulation boundary.

## Key Findings

- **Overall volume:** Pooled PBIAS was approximately **−2.0%** over 2020–2021, but station-level PBIAS ranged from approximately **−18.6% to +19.4%**.
- **Daily agreement:** Pooled daily Pearson correlation was approximately **0.66** after the best-performing daily accumulation alignment.
- **High rainfall:** IMERG tended to overrepresent light rainfall and underestimate heavier rainfall; the observed **≥100 mm/day** class was underestimated by approximately **52%** in the available sample.
- **Uniform correction:** A correction factor estimated from 2020 improved 2021 cumulative bias but slightly worsened daily RMSE, indicating that a single multiplier does not necessarily improve rainfall timing or event magnitudes.

These findings underscore why near-neutral long-period volume bias should not be interpreted as evidence of accurate rainfall forcing for individual flood events.

## Dashboard Features

The dashboard includes an interactive station map; station-level time series, scatterplots, annual totals, and performance metrics; rainfall-intensity and seasonal diagnostics; selected-event comparisons; daily accumulation-boundary sensitivity; and a summary of the methodology and correction considerations.

## Limitations

Only stations with usable daily observations were included in the primary quantitative comparison; the results do not represent complete coverage of Guyana. The best-performing accumulation boundary near **12:00 UTC** is an empirical alignment result, **not** a confirmed gauge observation time. Point-gauge and gridded-rainfall estimates differ in spatial support, and daily comparisons do not establish the accuracy of subdaily rainfall intensities.

## Access and Citation

- **Live dashboard:** https://ulfloodcenter.github.io/guyana-rainfall-validation/
- **HydroShare archival resource and DOI:** http://www.hydroshare.org/resource/c973664457db4e5a9069f99d91385b7a
- **Citation:** Morsy, M., Williams, G., Habib, E. H. (2026). Guyana Rainfall Validation Dashboard: Evaluation of NASA GPM IMERG V07 Against Ground-Based Rainfall Observations, HydroShare, http://www.hydroshare.org/resource/c973664457db4e5a9069f99d91385b7a

## Acknowledgment

This work was supported by the U.S. National Science Foundation under **Award No. 2426270**, *Collaboratively Designed and Managed Flood Resilience Framework for Affected Communities in the Caribbean Region*.
