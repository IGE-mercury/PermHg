# A Comprehensive Mercury Database from Permafrost-Dominated Regions

This dataset is part of the **Permafrost Mercury Database (PermHg)** initiative, which compiles 117,802 Hg observations collected from 59 studies across permafrost-affected regions in the northern hemisphere. The database includes Hg concentration measurements in solid materials—such as soil, leaves, roots, wood, and litter—as well as in water samples from soil porewater, lakes, and rivers across the northern hemisphere permafrost domain.

The database enables cross-site synthesis, model calibration and evaluation, and environmental assessments by standardizing and harmonizing data from diverse sources. Data harmonization steps included unit conversion, categorization of observations by type, and quality control measures to ensure consistency across studies. 

## Contents
- `sediment_hg.csv` — Data file containing lake sediment Hg observations  
- `soil_hg_.csv` — Data file containing lake soil Hg observations 
- `vegetation_hg_.csv` — Data file containing vegetation Hg observations 
- `water_hg_.csv` — Data file containing aqueous Hg observations 
- `data_sources.csv` — List of data sources, citations, and DOIs  
- `METADATA.txt` — Column descriptions, units, and data conventions  
- `LICENSE.txt` — Data license information  

The data sources included in the Permafrost Mercury Database (PermHg) are listed in for groups:

  A.	Lake Sediment Mercury Observations\
  B.	Soil Mercury Observations\
  C.	Vegetation Mercury Observations\
  D.	Aquatic/Water Mercury Observations\
  
For each of which a  `.bib` file is available.


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

For users who do not use or are not familiar with GitHub, we also welcome data submissions by email using the provided template file.
