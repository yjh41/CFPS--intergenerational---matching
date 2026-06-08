# CFPS--intergenerational---matching
This project showcases the research methodology and data cleaning pipeline for intergenerational identification using the China Family Panel Studies (CFPS). The core motivation of this work is to address the technical challenges in tracking family lineages across time, providing a standardized, reproducible data structure to analyze social mobility and family development in contemporary China.

As a nationally representative, biennial longitudinal survey launched in 2010 by Peking University, the CFPS offers an unparalleled resource for lineage analysis due to its meticulous tracking of baseline family members and their descendants. This project specifically focuses on the technology part of how to precisely match and link these intergenerational relationships from the 2010 baseline wave up to the latest 2022 wave.

### Main Working Modules:

* 📑 **Data Preprocessing & Alignment:** Extracting primary household relationship matrices, cleaning unique personal identifiers (`pid`, `fid`), and aligning variable definitions across multiple tracking waves.
* 💻 **Intergenerational Identification Logic:** Developing robust loops and tracking rules (using Stata) to identify cross-generational pairs and handle complex family status changes (e.g., family splitting, marriage, moving out).
* 📊 **Harmonization & Validation:** Handling cross-wave missing data and sample attrition, calculating proper weight adjustments, and generating descriptive statistics to verify the quality of the matched dataset.
* 📝 **Technical Documentation:** Providing ready-to-run data cleaning scripts and step-by-step explanatory logs to ensure the full reproducibility of this master's thesis.
