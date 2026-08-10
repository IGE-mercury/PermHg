# A Comprehensive Mercury Database from Permafrost-Dominated Regions

This dataset is part of the **Permafrost Mercury Database (PermHg)** initiative, which compiles published and unpublished mercury (Hg) concentration measurements from permafrost-affected environments.  
This component includes vegetation, soil, lake sediment, and aqueous samples collected across Arctic, boreal, and alpine regions.

The dataset is provided for long-term archiving and open reuse through Zenodo.  

---

## Contents
- `sediment_hg.csv` — Data file containing lake sediment Hg observations  
- `soil_hg.csv` — Data file containing lake soil Hg observations 
- `vegetation_hg.csv` — Data file containing vegetation Hg observations 
- `water_hg.csv` — Data file containing aqueous Hg observations  
- `METADATA.txt` — Column descriptions, units, and data conventions  
- `LICENSE.txt` — Data license information

Files suffixed with `_template` are intended for future data submissions. The `.bib` files represent the source publications discussed in the Source Identification section.

---

## License

This dataset is distributed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
If you use or modify this dataset in your work, please refer to the `CITATION.cff` file for citation information.

---

## Data Provenance and Processing
All observations in the Permafrost Mercury Database (PermHg) originate from previously published studies and contributed datasets spanning permafrost-affected environments. Provenance is preserved at the individual observation level and at the dataset level to ensure transparency, traceability, and appropriate recognition of original data contributors.

**Source identification.**  
Each observation is linked to its original source publication through per-row author and citation fields within the data tables. Complete bibliographic information for all source studies, including citations and DOIs where available, is provided in `.bib` files.

**Data extraction and inclusion.**  
Data were compiled from peer-reviewed articles, supplementary materials, and archived datasets. Only data from identified source publications are included, and source information is retained alongside each observation.

**Harmonization and quality control.**  
To enable synthesis across studies, data were standardized using consistent units, variable names, and metadata conventions. Quality-control checks include validation of units, ranges, coordinates, sampling media, and dates, as well as flagging of missing or ambiguous values. These steps are documented to ensure traceability from the original source to the harmonized dataset.

**Dataset-level contributor recognition.**  
In addition to citation within the data tables and source documentation, first authors of source publications are formally credited as dataset contributors in the Zenodo metadata record. Dataset authorship is distinct from manuscript authorship.

---
## Contribution to this dataset

### Two branches are available: 
- **main** → Stable, published version of the dataset (matches the latest Zenodo release).  
- **dev** → Working branch for upcoming updates, additions, or documentation improvements.

All changes should be proposed as **pull requests (PRs)** targeting the `dev` branch.  
After review and validation, changes in `dev` are merged into `main`, and a new **release** is created on Zenodo.


---

###  Workflow for contributors 

1. Create your own copy of the repository ("fork"). This allows you to make changes without affecting the main repository.
2. Create a new branch from the `dev` in your fork. Use this branch to add your contributions (new data, corrections, or documentation updates).
3. Submit a pull request (PR) from your branch to the `dev` branch of this repository.  
4. The maintainers will review your PR and, once approved, merge it into `dev` in preparation for the next official release.

For users who do not use or are not familiar with GitHub, we also welcome data submissions by email to [support team](mailto:permhg@univ-grenoble-alpes.fr), using the provided template files.

