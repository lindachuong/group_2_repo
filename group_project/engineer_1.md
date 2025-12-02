Engineer 1 - Samiha Chowdhury

PAPER 1
Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC5770765/
GitHub link: https://github.com/BreenMS/PTSD-blood-transcriptome-mega-analysis?tab=readme-ov-file
Reproducibility Status:
The GitHub repository provides the consensus expression matrix, metadata, differential expression results, and the primary WGCNA script used in the publication. However, the repository does not include the full set of output files generated during the original analysis (e.g., WGCNA module outputs, final figures, intermediate QC results). Because these output files are missing, it is not currently possible to directly compare newly generated results to the authors’ original outputs. While the code appears functional, full replication requires re-running all analyses and inferring missing steps, which may lead to differences from the published results.

PAPER 2
Paper link: https://pmc.ncbi.nlm.nih.gov/articles/PMC11700205/?utm_source=chatgpt.com 
Github link: https://github.com/evalukas/ptsd_cvd
Reproducibility Status:
The GitHub repository provides all analysis scripts used in the study, but does not include the underlying GWAS summary-statistic files or any of the authors’ processed output files. According to the associated paper, all GWAS datasets used in the analyses are publicly available, meaning the raw input data can be re-acquired; however, the paper does not provide a data-sharing link to the authors’ intermediate or final outputs (such as genetic-correlation matrices, genomic SEM results, MR outputs, or mediation tables). Because neither the repository nor the publication includes these processed results, it is not possible to directly compare newly generated results against the authors’ originals. Therefore, the project is reproducible in principle—since the required summary-level data and scripts can be obtained—but not immediately verifiable, as full replication requires manually downloading all GWAS inputs, re-running every analysis step, and reconstructing results without access to the authors’ original output files.

PAPER 3
Paper link: https://onlinelibrary.wiley.com/doi/epdf/10.1002/ajmg.b.32568 
Github link: https://github.com/PGC-PTSD-EWAS/QC_Pipeline
Reproducibility Status:
The QC_Pipeline repository provides the full code used for EWAS quality-control processing but does not include any raw methylation data, processed outputs, or example result files. Because the original cohort data are not publicly available, the pipeline is reproducible in principle, meaning the code can be run if the required iDAT files are obtained, but it is not immediately verifiable. Without access to the original datasets or the authors' QC-generated outputs, it is not possible to directly replicate or compare results.

PAPER 4
Paper link: https://www.sciencedirect.com/science/article/pii/S2352289521000862
Github link:https://github.com/Zhiyi-Chen-github/Classifier-PTSD-COVID-19
Reproducibility Status:
This repository provides the MATLAB code used for PTSD/COVID-19 classification and includes the processed predictor matrix and a saved model file. Because the input .mat data are included, the neural network functions can be run and the model can be reproduced at the processed-data level. However, the original raw clinical dataset and preprocessing steps are not provided, and no ground-truth outputs are included for comparison. As a result, the project is partially reproducible since the code runs, but the analysis is not fully verifiable without access to the original raw data and feature-generation pipeline.

PAPER 5
Paper link: https://www.nature.com/articles/s41398-025-03487-0
Github link: https://github.com/TraumaML/annotation
Reproducibility Status:
The TraumaML/annotation repository provides the code used for pre-annotation and baseline modeling of trauma-related linguistic features in psychiatric electronic health records (EHRs). According to the corresponding publication, de-identified annotated data (the “Trauma Enriched Psychiatric Corpus”) are only available via request through a controlled archive (not publicly included in the repository). As a result, while the pipeline is reproducible in terms of code, the lack of publicly included input data or processed output means it is not immediately verifiable or replicable without obtaining the data through the archive and re-running the full pipeline.

PAPER 6
Paper link: https://www.nature.com/articles/s41598-024-54242-2
Github link: https://github.com/bartala/ChatCBPTSD
Reproducibility Status:
The ChatCBPTSD repository provides the full analysis code and a requirements list, meaning the computational pipeline is transparent and could be rerun. However, because the actual dataset (childbirth narratives/de-identified text data) is not publicly included and requires contacting the corresponding author for access, the analysis is only partially reproducible. In practice, one cannot independently reproduce or verify the published results without obtaining the underlying data.
