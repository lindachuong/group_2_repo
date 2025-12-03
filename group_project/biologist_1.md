PAPER 1:
Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC5770765/
GitHub link: https://github.com/BreenMS/PTSD-blood-transcriptome-mega-analysis?tab=readme-ov-file

Summary: The study performed a large cross-cohort mega-analysis of blood transcriptome data to identify reliable gene expression changes associated with PTSD. By pooling data from multiple independent studies, the authors overcame inconsistencies seen in smaller datasets and revealed robust immune-related signatures that distinguish individuals with PTSD from controls. The results show widespread dysregulation of immune and inflammatory pathways, supporting the idea that PTSD involves systemic biological changes beyond the brain. These reproducible transcriptomic patterns provide potential biomarkers for PTSD diagnosis, risk assessment, and treatment monitoring, and demonstrate how large-scale, integrated analyses can enhance reliability in psychiatric genomics research.
Highlighted genes:
IFI44L — over-expressed in PTSD cases in combat-trauma subgroups. 

GNG11 — under-expressed in PTSD cases (combat-related trauma). 

IFIT3 — significantly differentially expressed across all mega-analytic comparisons (all trauma types / sexes), though direction of change varied by subgroup.

How it connects to theme: This research exemplifies the growing integration of transcriptomics and machine learning in mental health research. By analyzing gene expression data across multiple independent cohorts and trauma types, the study demonstrates how genomic approaches can uncover shared biological pathways—particularly immune dysregulation—that may link PTSD to other conditions like cardiovascular disease and cognitive disorders. The multi-cohort design and focus on reproducible molecular signatures aligns with the broader trend of using computational methods to improve diagnostic accuracy and identify common biological mechanisms across seemingly distinct mental health and cognitive disorders. This convergent approach, identifying both shared immune pathways and context-specific responses, represents the kind of precision medicine framework that is advancing our understanding of PTSD alongside other complex neuropsychiatric conditions.

Reproducibility:

Data integration – Combined data from five studies to get a bigger, more reliable dataset.

Co-expression network analysis (WGCNA) – Grouped genes into modules that behave similarly, revealing coordinated biological pathways.

Differential expression analysis – Identified which genes are turned on or off in PTSD, and how this differs by sex or trauma type.

Pathway enrichment – Found which biological processes (like immune or inflammatory pathways) are affected in PTSD.

How this can be implemented/ difficulty level:
 Data Access: The repository contains processed data. If you require raw data or additional information, you may need to contact the corresponding author at michael.breen@mssm.edu

Reproducibility: Ensure Python environment has the necessary packages and dependencies installed. The analysis script assumes a specific data format and structure.

Computational Resources: Depending on the size of the dataset, the analysis may require significant computational resources.

PAPER 2:
Paper link: https://pmc.ncbi.nlm.nih.gov/articles/PMC11700205/?utm_source=chatgpt.com
Github link: https://github.com/evalukas/ptsd_cvd

Summary:
This study investigates the genetic relationship between Post-Traumatic Stress Disorder (PTSD) and cardiovascular diseases (CVD) using data from over 1.2 million individuals. The researchers found significant genetic correlations between PTSD and coronary artery disease, hypertension, and heart failure, though not with atrial fibrillation. Using Mendelian randomization—a method that uses genetic variants to infer causality—they demonstrated that PTSD causally increases the risk of developing cardiovascular disease, with the strongest evidence for coronary artery disease. Importantly, they identified several mediating factors that partially explain this relationship, including insomnia, smoking, alcohol dependence, waist-to-hip ratio, and inflammatory markers like C-reactive protein and IL-6. However, even after accounting for these mediators, independent causal effects of PTSD on CVD remained. These findings suggest that PTSD patients face elevated cardiovascular risk and that interventions targeting sleep quality, substance use, body fat distribution, and inflammation could help prevent CVD in this vulnerable population.

How it connects to theme: This study exemplifies the modern genomics-driven approach to mental health by using large-scale genetic data and Mendelian randomization to establish causal links between PTSD and cardiovascular disease. By identifying shared biological pathways involving inflammation, metabolism, and behavior, the research demonstrates how genomic methods can uncover mechanistic connections between mental and physical health conditions. This approach aligns with emerging trends that integrate genomics and machine learning across psychiatric disorders like schizophrenia, providing reproducible, biologically grounded insights that enable more precise diagnostics and targeted interventions for conditions that share common biological substrates.

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

PAPER 3:
Paper link: https://onlinelibrary.wiley.com/doi/epdf/10.1002/ajmg.b.32568
Github link: https://github.com/PGC-PTSD-EWAS/QC_Pipeline?tab=readme-ov-file

Summary:
This paper resolves the evolutionary paradox of schizophrenia—why genetic risk persists despite the disorder reducing fitness—and the problem of missing heritability by proposing that schizophrenia is a trade-off of human evolution. The authors argue that the common genetic variants contributing to schizophrenia are not defects but are integral to the development of advanced human cognition, sociality, and language. These same genes, which were under positive selection, create a biological framework that is inherently vulnerable; when perturbed by environmental factors or combined with rare mutations, they can lead to the disorder. Consequently, the heritability isn't missing but is instead distributed across the very genes that make us human, meaning we cannot eliminate the genetic risk for schizophrenia without undermining the foundations of our unique cognitive abilities.

How it connects to theme: This paper addresses the evolutionary paradox of schizophrenia by proposing that genetic risk variants are not defects but essential components of human cognitive evolution. The authors argue that genes underlying schizophrenia were positively selected for their roles in advanced cognition, sociality, and language, but create an inherent vulnerability when disrupted by environmental factors or rare mutations. This framework explains the "missing heritability" by showing that schizophrenia risk is distributed across genes fundamental to human nature, illustrating how genomic approaches reveal shared biological substrates between normal cognition and psychiatric disorders. By demonstrating that mental health conditions can emerge from the same genetic architecture that enables our unique capabilities, this evolutionary perspective provides a reproducible biological foundation for understanding why certain psychiatric vulnerabilities persist across populations.

Reproducibility:
Reproducibility: Good - This repository has detailed R scripts, clear documentation, and step-by-step procedures for replicating their methylation analyses.

PAPER 4:
Github link:https://github.com/Zhiyi-Chen-github/Classifier-PTSD-COVID-19
Paper link: https://www.sciencedirect.com/science/article/pii/S2352289521000862

Summary: This paper provides a genetic explanation for the well-established clinical link between Post-Traumatic Stress Disorder (PTSD) and Cardiovascular Disease (CVD), demonstrating that the two conditions share a significant common genetic basis. Through an analysis of large-scale genetic datasets, the researchers found that the same genetic factors that increase a person's risk for PTSD also increase their risk for various cardiovascular conditions, including coronary artery disease and heart attack, as well as risk factors like Type 2 Diabetes. Crucially, the study indicates that this relationship is not primarily a direct causal one where PTSD causes CVD or vice-versa, but is instead largely due to pleiotropy, where an overlapping set of genes independently influences both disorders. These shared genes are involved in key biological pathways such as immune system inflammation and central nervous system stress response, which are implicated in the biology of both PTSD and atherosclerosis. The findings suggest that the high rate of heart disease in individuals with PTSD is not just a consequence of lifestyle or psychological stress, but is also rooted in a shared genetic predisposition, highlighting the need for integrated clinical care that views PTSD as a risk marker for physical health conditions and prioritizes early cardiovascular screening for this patient population.

How it connects to theme: This paper uses large-scale genomic analysis to demonstrate that PTSD and cardiovascular disease share substantial common genetic architecture, revealing that the clinical association between these conditions has deep biological roots. The researchers found that overlapping genes influencing both disorders are involved in immune inflammation and stress response pathways, indicating pleiotropy rather than simple causation. This work exemplifies how genomic approaches can uncover shared biological substrates across mental and physical health conditions, moving beyond observational associations to identify reproducible genetic mechanisms. By establishing that PTSD and CVD emerge partly from the same genetic framework, the study provides a data-driven foundation for integrated care models and highlights how modern genomics enables us to map the interconnected biology underlying seemingly distinct disorders, ultimately supporting more precise risk stratification and intervention strategies.


Reproducibility: 
High Methodological Reproducibility: The repository provides the complete code for the entire machine learning pipeline, including data preprocessing, feature selection, model training (SVM, Random Forest, XGBoost), ensemble construction, and validation. This makes the methods fully transparent and reproducible.

Significant Data Access Barriers: A major limitation is access to the original data. While scripts are included to process data, the key validation datasets from the UK Biobank and ABCD study are not publicly available. They require separate, approved applications, making full independent validation impossible for most.

Substantial Computational Demand: Reproducing the analysis requires significant computational resources to process RNA-seq data and run the extensive, multi-step classifier training and bootstrapping procedures.

Requires Manual Execution: The reproduction is not a "one-click" process. It requires a user to manually run each sequential step of the pipeline, setting up correct file paths and directories, which introduces a potential for error.

Conclusion: In principle, the analysis is reproducible, but in practice, it is confined to researchers with both the necessary computational resources and approved access to the same controlled datasets.

PAPER 5:
Github link: https://github.com/TraumaML/annotation
Paper link: https://www.nature.com/articles/s41398-025-03487-0



Summary: 
This study created the first publicly available, clinician-validated “gold-standard” dataset for identifying trauma-related information in psychiatric electronic health records (EHRs). Using 200 detailed clinical notes from patients with psychotic disorders and PTSD, the authors developed a comprehensive annotation scheme to label traumatic events, symptoms, substance use, and contextual details. Expert clinicians annotated the records with strong inter-annotator reliability, showing the scheme is consistent and clinically meaningful. The team then trained baseline transformer models on the dataset, achieving solid performance and demonstrating that the resource is suitable for machine-learning development. Overall, the study fills a major gap in psychiatric NLP by providing a validated dataset that can support future research on trauma detection, symptom trajectories, and data-driven clinical insights in mental health.

How it connects to theme: This study addresses a critical gap in psychiatric research by creating the first clinician-validated dataset for extracting trauma-related information from electronic health records using natural language processing. By developing a comprehensive annotation scheme with high inter-annotator reliability and training baseline transformer models that achieved strong performance, the work demonstrates how machine learning can be applied to unstructured clinical data to identify patterns in trauma, symptoms, and contextual factors. This approach exemplifies the integration of machine learning with real-world clinical data to enable reproducible, data-driven insights into mental health disorders like PTSD and psychosis. The publicly available dataset provides a foundation for future research using NLP and genomics to uncover symptom trajectories and biological correlations, supporting the broader goal of precision psychiatry through computational methods that can scale across large patient populations.

Reproducibility:
This study demonstrates a moderate to high level of reproducibility, supported by the availability of an open GitHub repository containing code for pre-annotation and baseline modeling, as well as detailed annotation guidelines provided in the supplementary materials. The authors thoroughly describe how the gold-standard dataset was created and report clear performance metrics such as inter-annotator agreement and model F1 scores, which allows other researchers to follow the methodological workflow. However, full reproducibility is limited by restricted access to the raw clinical text, which cannot be publicly released due to patient privacy regulations; as a result, researchers cannot reproduce the work on the exact same data without institutional approval. The dataset is also relatively small and sourced from a single healthcare system, which reduces generalizability and may make outcomes sensitive to sample characteristics. Furthermore, only a subset of clinical notes received dual annotation, introducing some uncertainty in annotation reliability. Overall, the study is transparent and methodologically well-documented, but constraints related to data access and dataset specificity make exact replication challenging.


Strengths that support reproducibility:

- Open GitHub repository with code for pre-annotation and baseline models

- Detailed annotation guidelines provided in supplementary materials

- Clear description of dataset creation and annotation procedures

- Reported performance metrics (IAA, F1 scores) allow benchmarking

- Transparent methodological workflow


Limitations that reduce reproducibility:

- Raw clinical text data are not publicly accessible due to privacy restrictions

- Requires institutional approval to access the same dataset

- Small dataset (200 notes) may lead to sensitivity to sample bias

- Data sourced from a single hospital network, limiting generalizability

- Only part of the dataset was annotated by multiple annotators, reducing reliability checks


PAPER #6:
Github link: https://github.com/bartala/ChatCBPTSD
Paper link: https://www.nature.com/articles/s41598-024-54242-2

Summary:
This study tested whether women’s written childbirth stories can be used to identify those at risk for childbirth-related PTSD. Using 1,295 narratives, the authors compared several AI methods, including ChatGPT and an embedding-based machine-learning model. The embedding model performed best, accurately distinguishing probable PTSD cases based on the language used in the narratives. The findings suggest that analyzing free-text birth stories could offer a scalable and low-effort tool for early PTSD screening, though the authors note that clinical validation and more diverse samples are still needed.

how it connects to theme: This paper fits into the broader theme of emerging mental-health research that uses advanced computational tools to improve diagnosis and reproducibility. Although this study does not use genomics or neuroimaging, it aligns with that trajectory by applying machine learning to extract clinically meaningful signals from unstructured behavioral data—in this case, childbirth narratives—to detect PTSD risk. Like transcriptomic or imaging models that identify shared biological pathways across disorders such as PTSD, CVD, or schizophrenia, this study demonstrates how AI-based approaches can reveal latent patterns that traditional clinical assessments might miss. Its use of open, reproducible machine-learning pipelines also parallels the push in modern mental-health research toward transparent, scalable methods that enhance diagnostic accuracy and support early detection.

Reproducibility: 

The reproducibility of this study is fairly strong, especially because the authors provide a public GitHub repository (ChatCB-PTSD) containing the core code used for their analyses, including model scripts, example prompts, and environment setup files. This level of code transparency makes it much easier for other researchers to follow the computational workflow and rerun the modeling steps. The paper also clearly describes the methods, models used, and performance metrics, which further supports replication. However, full reproducibility is still limited by the lack of access to the raw childbirth narratives, which cannot be publicly released due to privacy concerns. The study also relies on proprietary OpenAI models (GPT-3.5-turbo and text-embedding-ada-002), meaning that exact replication depends on having API access and potentially matching model versions, which can change over time. Additionally, the dataset originates from a specific population and context, which limits generalizability. Overall, the study is quite transparent and methodologically accessible—especially with the released code—but constraints around data access and proprietary tools still prevent complete one-to-one replication.

Strengths Supporting Reproducibility

- Public GitHub repository with core code, scripts, prompts, and setup files

- Clear descriptions of modeling approaches (zero-shot, few-shot, and embedding-based classifier)

- Standard performance metrics (e.g., F1 score) for benchmarking

- Open-access publication with detailed methods

- Code allows others to recreate the pipeline with their own data

Limitations

- Raw childbirth narratives are not publicly available, limiting exact replication

- Proprietary OpenAI models may change or require paid API access

- Results depend on model versions that may not behave identically in the future

- Dataset comes from a specific, self-selected population, limiting generalizability

- Some preprocessing or annotation details may still require interpretation
