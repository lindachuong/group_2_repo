Biologist 2 - Linda Chuong

++ Lab Report #1: 
Zimmerman, C.A., Bolkan, S.S., Pan-Vazquez, A. et al. A neural mechanism for learning from delayed postingestive feedback. 
Nature 642, 700–709 (2025). https://doi.org/10.1038/s41586-025-08828-z

Website Link: https://www.nature.com/articles/s41586-025-08828-z#citeas

Github Link: https://github.com/cazimmerman/cta and https://github.com/bichanw/CTA

Summary: The paper was found on Nature. The paper explores the mechanism how the brain learns to like or dislike the taste of soemthing after eating it. Through mice
experimentation, they induces food poisinong on the mice associated with a food and observed the gut-brain signaling mechanism that induces a learning memory for the gut to
reactivate that memory. The github generates the compuational data with figures, tables, and brain-wide cell detection pipeline. 


Connection to Theme: This study leverages computational and data-driven approaches to understand factors influencing mental health. By mapping biochemical and nutritional associations, it aligns with the theme’s emphasis on multimodal, reproducible analyses to explore biological mechanisms behind psychiatric and cognitive disorders.

++ Lab Report #2: 
Lanka, P., Rangaprakash, D., Dretsch, M.N., Katz, J.S., Denney, T.S. Jr., & Deshpande, G. Supervised machine learning for diagnostic classification from large-scale neuroimaging datasets. 
Scientific Reports (2019). https://doi.org/10.1007/s11682-019-00191-8 --> pdf avaliable via fordham library 

Website Link: https://www.nature.com/articles/s41586-025-08828-z 

Github Link: https://github.com/pradlanka/malini

Summary: This paper evaluates the generalizability of machine learning classifiers on resting-state fMRI data for Autism (N=988), ADHD (N=930), PTSD (N=87), and Alzheimer’s disease (N=132). The authors applied 18 classifiers and showed that overfitting is a major problem in heterogeneous datasets. To improve robustness, they proposed a consensus classifier that combines all 18 models, reducing sensitivity to age or site differences. Feature importance scores from all classifiers were aggregated to identify discriminative and robust functional connectivity patterns. The MALINI MATLAB toolbox implements these classifiers and the consensus model, enabling reproducible analyses and visualization of neuroimaging-based diagnostic predictions.

Connection to Theme: This work directly addresses mental health disorders using neuroimaging combined with machine learning, showing how multimodal computational methods can improve diagnostic accuracy and uncover shared biological pathways across psychiatric conditions.

++ Lab Report #3:
Dang, L. D., Phan, U. T. P., & Nguyen, N. T. H. GENA: A knowledge graph for nutrition and mental health. 
Journal of Biomedical Informatics 145 (2023). https://doi.org/10.1016/j.jbi.2023.104460


Website Link: https://www.sciencedirect.com/science/article/pii/S1532046423001818?via%3Dihub 

Github Link: https://github.com/ddlinh/gena-db

Summary: Summary: This paper introduces the knowledge graph named GENA (Graph of mEntal‑health and Nutrition Association) which encodes relationships between nutrition (foods, biochemicals) and mental health disorders, by mining PubMed abstracts. The authors applied a hybrid named‑entity recognition (NER) model followed by a deep syntax‑based relation‑extraction model to identify entities and binary relations from abstracts. 
 The resulting graph contains 43,367 relations, about 94.04 % of which are novel (i.e., not present in existing food‑disease ontologies).
 GENA is implemented using the Neo4j database to allow intuitive querying and exploration of how nutritional factors may relate to mental‑health conditions. The publicly released GitHub repository enables access to both code and data, supporting reproducibility and reuse of this resource.

Connection to Theme: This study leverages computational and data-driven approaches to understand factors influencing mental health. By mapping biochemical and nutritional associations, it aligns with the theme’s emphasis on multimodal, reproducible analyses to explore biological mechanisms behind psychiatric and cognitive disorders.

++ Lab Report #4:
Zhang, L., Li L., et al. MMASleepNet: A multimodal attention network based on electrophysiological signals for automatic sleep staging. 
Frontiers in Neuroscience 16 (2022). https://doi.org/10.3389/fnins.2022.973761


Website Link: https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.973761/full

Github Link: https://github.com/buptantEEG/MMASleepNet/

Summary: This paper introduces the deep-learning architecture MMASleepNet, which uses EEG, EOG, and EMG signals in a multi‐branch feature extraction module plus an attention‐based fusion module (modal-wise squeeze-and-excitation + Transformer encoder) to improve automatic sleep staging. The model was tested on publicly available datasets (Sleep-EDF, ISRUC-Sleep) and outperformed prior methods in accuracy, F1-score and κ metrics. The GitHub repository provides the implementation, enabling reproducibility of multimodal electrophysiological sleep staging.

Connection to theme: Sleep and electrophysiological dynamics are closely tied to cognitive function and mental health. This study exemplifies the use of multimodal neural data and machine learning for accurate, scalable, and reproducible assessment of brain function, aligning with the theme of data-driven neuropsychiatric research.
 
++ Lab report #5:
Spargo, T.P., Gilchrist, L., Hunt, G.P., Dobson, R.J.B., Proitsi, P., Al-Chalabi, A., Pain, O., & Iacoangeli, A. Statistical examination of shared loci in neuropsychiatric diseases using genome-wide association study summary statistics. eLife 12 (2023/24). https://doi.org/10.7554/eLife.88768.3


Website Link: https://elifesciences.org/articles/88768

Github Link: https://github.com/ThomasPSpargo/COLOC-reporter

Summary: This study introduces a publicly-available pipeline to analyze genetic pleiotropy between neuropsychiatric and neurodegenerative disorders (including Alzheimer’s disease, ALS, frontotemporal dementia, Parkinson’s disease, schizophrenia) via local genetic correlation, fine-mapping, and colocalisation of GWAS summary statistics. The authors identified specific loci (notably within the HLA region) that are jointly implicated across disease pairs, providing insights into shared genetic architecture and paving the way for multi-trait genomic analyses. 

Connection to theme: This paper applies genomics and computational analyses to uncover biological pathways shared across psychiatric and cognitive disorders, directly exemplifying the theme’s focus on multimodal, data-driven approaches to understanding mental health.

++ Lab Report #6:
Verdonk, F., Cambriel, A., Hédou, J., Ganio, E., Bellan, G., et al. An immune signature of postoperative cognitive decline. International Journal of Surgery 110(12) (2024). https://doi.org/10.1097/JS9.0000000000002118

Webiste LinK: https://journals.lww.com/international-journal-of-surgery/fulltext/2024/12000/an_immune_signature_of_postoperative_cognitive.32.aspx 

Github Link: https://github.com/gregbellan/POCD

Summary: Summary: This study investigated peripheral immune cell trajectories and proteomic changes in patients aged 60 and older undergoing major orthopedic surgery, to identify biomarkers predictive of Postoperative Cognitive Decline (POCD). Using serial blood draws at baseline, post-op day 1, day 7, and day 90, and applying single-cell mass cytometry and plasma proteomics, the authors identified cell-type and signaling-specific immune features differentiating those who developed POCD from those who did not. A predictive model built on preoperative immune features (one plasma protein + ten immune cell features) achieved AUC ≈ 0.80 in classification. The findings raise the prospect of personalized perioperative immune-monitoring to anticipate cognitive decline after surgery.

Connection to theme: This study links immune system profiling with cognitive outcomes, illustrating how multimodal biological data (proteomics + cell phenotyping) combined with predictive modeling can reveal mechanisms underlying cognitive disorders, supporting the theme’s emphasis on scalable, reproducible, and data-driven approaches to mental health research.
