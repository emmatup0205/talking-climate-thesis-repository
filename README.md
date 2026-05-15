# Talking Climate: Does Peer Anxiety Amplify or Alleviate Climate Change Worries?

## Author
Emma Valentina Tupone  
M.S. Psychological Research, Brooklyn College (CUNY)

---

## Project Overview
This project examines how peer conversations about climate change influence daily emotional responses and pro-environmental behavior (PEB).

Using an 8-day daily diary design, this study investigates:
- Whether climate conversations are associated with changes in climate change anxiety (CCA) and optimism (CCO)
- How emotional responses relate to private and public pro-environmental behaviors
- Whether optimism strengthens the link between climate anxiety and behavior
- Whether climate anxiety explains (mediates) the relationship between conversations and behavior

This research contributes to understanding how interpersonal communication shapes emotional and behavioral engagement with climate change.

---

## Repository Structure

- `data/` → Data documentation and access information (restricted)
- `code/` → R scripts used for data cleaning and analysis
- `output/` → Figures and tables generated from analyses
- `docs/` → Thesis PDF and supporting materials

---

## Code / Analysis

All analyses for this project were conducted in **R**.

The primary script (`thesis_analysis.R`) includes:
- Data import and cleaning (SPSS → R)
- Descriptive statistics
- Multilevel modeling using linear mixed-effects models (`lme4`, `lmerTest`)
- Mediation analysis using bootstrapping (`mediation` package)
- Moderation (interaction) analyses
- Generation of summary statistics and outputs

Additional packages used include:
- `dplyr` for data manipulation
- `psych` for descriptive statistics
- `emmeans` for estimated marginal means

To reproduce the analysis:
1. Obtain access to the dataset by contacting the Principal Investigator
2. Place the dataset in the appropriate directory
3. Run the script `thesis_analysis.R` in R

Note: Because the dataset is not publicly available, full reproducibility is contingent on obtaining approved access to the data.

---

## Code / Analysis

All analyses for this project were conducted in **R**.

The primary script (`thesis_analysis.R`) includes:
- Data import and cleaning (SPSS → R)
- Descriptive statistics
- Multilevel modeling using linear mixed-effects models (`lme4`, `lmerTest`)
- Mediation analysis using bootstrapping (`mediation` package)
- Moderation (interaction) analyses
- Generation of summary statistics and outputs

Additional packages used include:
- `dplyr` for data manipulation
- `psych` for descriptive statistics
- `emmeans` for estimated marginal means

To reproduce the analysis:
1. Obtain access to the dataset by contacting the Principal Investigator
2. Place the dataset in the appropriate directory
3. Run the script `thesis_analysis.R` in R

Note: Because the dataset is not publicly available, full reproducibility is contingent on obtaining approved access to the data.

---

## Thesis

The full thesis can be found here:

[View Thesis PDF](docs/talking climate thesis tupone.pdf)

---

## Citation

This repository will be assigned a DOI via Zenodo.  
Citation information will be updated upon DOI generation.

---

## License

This repository is licensed under the MIT License.  
Code may be reused with attribution.  

Note: Data are not publicly available due to ethical and confidentiality restrictions.
