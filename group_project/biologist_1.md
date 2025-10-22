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