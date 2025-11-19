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

Paper 2
Paper link: https://pmc.ncbi.nlm.nih.gov/articles/PMC11700205/?utm_source=chatgpt.com
Github link: https://github.com/evalukas/ptsd_cvd

Summary:
This study investigates the genetic relationship between Post-Traumatic Stress Disorder (PTSD) and cardiovascular diseases (CVD) using data from over 1.2 million individuals. The researchers found significant genetic correlations between PTSD and coronary artery disease, hypertension, and heart failure, though not with atrial fibrillation. Using Mendelian randomization—a method that uses genetic variants to infer causality—they demonstrated that PTSD causally increases the risk of developing cardiovascular disease, with the strongest evidence for coronary artery disease. Importantly, they identified several mediating factors that partially explain this relationship, including insomnia, smoking, alcohol dependence, waist-to-hip ratio, and inflammatory markers like C-reactive protein and IL-6. However, even after accounting for these mediators, independent causal effects of PTSD on CVD remained. These findings suggest that PTSD patients face elevated cardiovascular risk and that interventions targeting sleep quality, substance use, body fat distribution, and inflammation could help prevent CVD in this vulnerable population.

Reproducibility:

Limited Reproducibility - The repository has several concerning gaps:
What's Available:

The repository exists and is publicly accessible
It references that code is available for the published paper
According to the paper, GWAS summary statistics are described in the original publication

Major Concerns:

Minimal Documentation: The repository appears to have very limited content - just a brief description stating it contains code for the paper, with no visible README, analysis scripts, or detailed documentation.
No Visible Code Files: From what's accessible, there don't appear to be any R scripts, analysis pipelines, or configuration files publicly visible in the repository structure.
Data Accessibility: While the paper states that publicly available GWAS data was used and provides citations, the repository doesn't include:

Clear instructions for downloading the specific datasets
Data preprocessing scripts
File paths or organization structure


Missing Components:

No requirements file or environment specifications
No step-by-step workflow documentation
No example outputs or validation results
No information about software versions used


