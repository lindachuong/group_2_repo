Group 2 - Engineer 2 - Mohammed Uddin engineer_2.md — Reproducibility Report (Biologist 2 Papers)

This report evaluates the reproducibility of six papers selected by Biologist 2, based solely on their publicly available GitHub repositories. For each paper, I attempted to run the code using Google Colab and standard Python tooling. Below are the implementation results, what did or didn’t run, and why.

1. Zimmerman et al. (2025) — Gut–Brain Learning Mechanism

GitHub: https://github.com/cazimmerman/cta

Paper: https://www.nature.com/articles/s41586-025-08828-z

Goal of the code

The repository contains scripts for generating the figures and tables from the paper plus a brain-wide cell-detection pipeline.

Reproducibility Attempt

Colab Steps:

!git clone https://github.com/cazimmerman/cta.git %cd cta !pip install -r requirements.txt

Outcome

The repository installs correctly.

Many scripts depend on large proprietary raw imaging datasets that the repository does NOT include.

Figure-generation scripts run, but core analysis fails due to missing data files.

Conclusion

Partially reproducible. Code structure is transparent, but the main experiments cannot be run because the required raw data are unavailable.

2.Lanka et al. (2019) — Machine Learning on Neuroimaging Data

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

Not reproducible in a Python environment. Requires MATLAB and cannot be executed in Colab.


