Group 2 - Engineer 2 - Mohammed Uddin 
engineer_2.md — Reproducibility Report (Biologist 2 Papers)

This report evaluates the reproducibility of six papers selected by Biologist 2, based solely on their publicly available GitHub repositories. For each paper, I attempted to run the code using Google Colab and standard Python tooling. Below are the implementation results, what did or didn’t run, and why.

1. Zimmerman et al. (2025) — Gut–Brain Learning Mechanism

GitHub: https://github.com/cazimmerman/cta

Paper: https://www.nature.com/articles/s41586-025-08828-z

Goal of the code

The repository contains scripts for generating the figures and tables from the paper plus a brain-wide cell-detection pipeline.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/cazimmerman/cta.git
%cd cta
!pip install -r requirements.txt

Outcome

The repository installs correctly.

Many scripts depend on large proprietary raw imaging datasets that the repository does NOT include.

Figure-generation scripts run, but core analysis fails due to missing data files.

Conclusion

Partially reproducible.
Code structure is transparent, but the main experiments cannot be run because the required raw data are unavailable.

2. Lanka et al. (2019) — Machine Learning on Neuroimaging Data

GitHub: https://github.com/pradlanka/malini

Paper: https://doi.org/10.1007/s11682-019-00191-8

Goal of the code

MALINI is a MATLAB toolbox for applying 18 ML classifiers to fMRI data.

Reproducibility Attempt

Colab Steps Tried:

!git clone https://github.com/pradlanka/malini.git

Outcome

Repository cloned successfully.

All scripts are MATLAB (.m) files and require MATLAB + specific toolboxes.

Google Colab CANNOT run MATLAB without a paid connector.

No Python equivalent provided.

Conclusion

Not reproducible in a Python environment.
Requires MATLAB and cannot be executed in Colab.

3. Dang et al. (2023) — GENA Nutrition–Mental Health Knowledge Graph

GitHub: https://github.com/ddlinh/gena-db

Paper: https://www.sciencedirect.com/science/article/pii/S1532046423001818

Goal of the code

Build a knowledge graph by extracting nutritional–mental health relationships from PubMed abstracts.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/ddlinh/gena-db.git
%cd gena-db
!pip install -r requirements.txt
!python build_graph.py

Outcome

Repository cloned and installed successfully.

Most components execute correctly (NER, relation extraction).

Neo4j component requires a local database, not supported in Colab.

However, intermediate steps (entity extraction + relation extraction) do run.

Conclusion

Mostly reproducible.
Full graph exploration requires Neo4j locally, but the main NLP pipeline runs successfully in Colab.

4. Zhang et al. (2022) — MMASleepNet Multimodal EEG Sleep Staging

GitHub: https://github.com/buptantEEG/MMASleepNet

Paper: https://www.frontiersin.org/articles/10.3389/fnins.2022.973761/full

Goal of the code

Deep-learning multimodal EEG/EOG/EMG classifier.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/buptantEEG/MMASleepNet.git
%cd MMASleepNet
!pip install -r requirements.txt

Outcome

Installs correctly in Colab.

Training scripts require large EEG datasets (Sleep-EDF, ISRUC), which are not included.

Running the model without data fails.

Conclusion

Not fully reproducible, unless large datasets are downloaded manually.
Model code itself appears functional.

5. Spargo et al. (2023/24) — COLOC Reporter (GWAS Shared Loci)

GitHub: https://github.com/ThomasPSpargo/COLOC-reporter

Paper: https://elifesciences.org/articles/88768

Goal of the code

Pipeline for colocalization analysis across neurological GWAS datasets.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/ThomasPSpargo/COLOC-reporter.git
%cd COLOC-reporter
!pip install -r requirements.txt

Outcome

Code installs but requires:

large GWAS summary datasets,

LDSC-specific data formats,

HPC-level compute for fine-mapping.

Scripts fail without these datasets.

Conclusion

Partially reproducible, but core analyses require data that are not included.

6. Verdonk et al. (2024) — Immune Signature of Postoperative Cognitive Decline

GitHub: https://github.com/gregbellan/POCD

Paper: https://journals.lww.com/
...

Goal of the code

Predict POCD using mass cytometry and proteomics.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/gregbellan/POCD.git

Outcome

Code exists, but no data are included.

Raw immune data cannot be distributed publicly.

Scripts reference missing files → runs fail.

Conclusion

Not reproducible due to missing patient-level datasets.

FINAL SUMMARY (Biologist 2 Papers)
Paper	GitHub	Reproducible?	Reason
Zimmerman et al.	cta	Partial	Missing raw imaging data
Lanka et al.	malini	No	MATLAB-only repository
Dang et al.	gena-db	Mostly Yes	NLP pipeline runs, Neo4j requires desktop
Zhang et al.	MMASleepNet	No	Requires large datasets
Spargo et al.	COLOC-reporter	Partial	Requires external GWAS datasets
Verdonk et al.	POCD	No	Missing clinical datasets
Final Conclusion

Most repositories could not be fully reproduced due to data access barriers. The GENA knowledge graph (Dang et al.) was the only codebase that could be run meaningfully in Google Colab. All others were limited by missing data or software constraints.
