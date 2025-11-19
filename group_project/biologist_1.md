PAPER 1:
Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC5770765/
GitHub link: https://github.com/BreenMS/PTSD-blood-transcriptome-mega-analysis?tab=readme-ov-file

Summary: This study analyzed peripheral blood transcriptomes from 229 individuals with PTSD and 311 controls across five independent studies covering seven types of trauma. Key findings include:
Trauma-Type Specific Signatures: Gene expression patterns differ depending on the type of trauma—interpersonal (IP) traumas show distinct profiles from combat-related traumas.
Sex-Specific Responses:
Men exposed to combat traumas showed downregulation of a wound-healing module.
Men exposed to IP traumas showed upregulation of IL-12-mediated signaling.
Women exposed to IP traumas showed upregulation of modules related to lipid metabolism and MAPK activity.
Shared Molecular Pathways: Across all sexes and trauma types, there is a convergence on common immune pathways, including cytokine signaling, innate immunity, and type I interferon pathways.
Overall, the study highlights both specificity (sex- and trauma-specific pathways) and convergence (shared immune dysregulation) in PTSD, suggesting potential targets for diagnostics and therapeutics.

Data integration – Combined data from five studies to get a bigger, more reliable dataset.

Co-expression network analysis (WGCNA) – Grouped genes into modules that behave similarly, revealing coordinated biological pathways.

Differential expression analysis – Identified which genes are turned on or off in PTSD, and how this differs by sex or trauma type.

Pathway enrichment – Found which biological processes (like immune or inflammatory pathways) are affected in PTSD.

How this can be implemented/ difficulty level:
 Data Access: The repository contains processed data. If you require raw data or additional information, you may need to contact the corresponding author at michael.breen@mssm.edu

Reproducibility: Ensure Python environment has the necessary packages and dependencies installed. The analysis script assumes a specific data format and structure.

Computational Resources: Depending on the size of the dataset, the analysis may require significant computational resources.

Paper 2:
Link to github: https://github.com/metapsy-project/data-ptsd-psyctr?tab=readme-ov-file

Link To Paper: https://onlinelibrary.wiley.com/doi/10.1002/jts.22520

Summary:
The article describes the development of the PTSD Trials Standardized Data Repository (PTSD-Repository), a publicly available and comprehensive database that compiles detailed information from 318 randomized controlled trials on treatments for posttraumatic stress disorder (PTSD). Because PTSD research is vast and inconsistent—with trials varying widely in interventions, populations, methods, and reporting—the authors created this repository to provide a centralized, standardized, and up-to-date source of data for researchers, clinicians, policymakers, and the public. Using systematic review methods, they searched eight major databases (1980–2018), screened over 17,000 records, and extracted 337 variables per study, covering study design, participant characteristics, trauma type, intervention details, PTSD outcomes, comorbidities, and harms. Expert panels guided decisions about what information to include and how to classify inconsistent reporting across studies. The repository aims to make evidence synthesis more efficient, support future systematic reviews and meta-analyses, highlight research gaps, improve clinical decision-making, and offer accessible information to patients and families. Although the database is extensive, limitations include missing risk-of-bias assessments, inconsistent reporting of certain variables, and the exclusion of non-RCTs, non-English studies, and preventive or combined-diagnosis interventions. The authors plan annual updates and a future interactive online interface to enhance usability.

Reproducible:
Search strategies are documented.
The databases, date ranges, and keywords are listed, meaning another team can repeat the literature search.

Inclusion and exclusion criteria are explicit.
Table 1 outlines the PICOTS criteria clearly.

Data dictionary exists.
They created detailed coding rules for each of the 337 variables, and this is publicly available.

The repository itself is public.
The finished dataset can be downloaded directly.

Methods follow AHRQ systematic review guidance, which is standardized and open.

Possible limitations:

Expert judgment was used, especially for:

Interpreting trauma categories

Classifying inconsistent outcome reporting

Determining primary PTSD outcomes

Incomplete reporting in primary studies.
Some trials simply do not report the same variables, so reproduction will still yield missing data.

No “gray literature” included.
A strict reproducibility attempt will replicate this limitation.

Search results may change over time
Databases update, index differently, or remove old entries.

Full data dictionary and appendices must be accessed
Without them, classification will vary.