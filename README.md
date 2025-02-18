# A Neuro-Spatial Discovery of ALS Biomarkers Using Graph Neural Networks With Applications to Multi-Target Drug Discovery
By Arnav Sharma, Samarth Dunakhe, and Aryav Das
PubChemPy code is not listed yet
## Overview
Amyotrophic Lateral Sclerosis (ALS) is a neurodegenerative disease that deteriorates motor neurons. Researchers have discovered the biomarkers C9orf72, Nfl, TDP43, etc. However, the 15\% false-positive and 40\% false-negative rate of ALS diagnosis shows that ALS is complex to diagnose. This is because of the biomarkers’ limited sensitivities and inconsistencies across populations. This paper proposes a discovery of sensitive ALS biomarkers with a therapeutic target. A transcriptome dataset with 7,038 gene expressions and a neuroproteomic dataset with 2,105 proteins were used. A Graph Neural Network was developed with enhanced feature aggregation achieving an accuracy of 98.2\% between ALS and controls and 80.85\% between ALS and mimics. Correspondingly, Captum Integrated Gradients identified the top 20 genes based on their attribution scores. Then, two-sample t-tests marked each omic significant if their p-value was below 0.05. Additionally, Log2FC identified the top 20 proteins by assessing differential expression. From this, KRT6A, KRT6B, and KRT4 were identified as biomarkers in the Pituitary Gland with tau-specificity of 86\%. With UniProt, their correlation with "cellular differentiation" and "cytoskeleton organization" was revealed. Pathway analysis revealed that Glucocorticoid Receptor Alpha (GRa) inhibits the activity of the AP-1 transcription factor, which functions in the pituitary gland as a promoter of keratin production. After molecular docking, it was shown that the PT150 ligand could inactivate Glucocorticoid Receptor Alpha and Cyclooxygenase 2, acting as a multi-target therapeutic for ALS.

## Data
https://pmc.ncbi.nlm.nih.gov/articles/PMC6016933/

## Model Weights
https://drive.google.com/file/d/1W5gIOmla4YBwRnLweEIjbjHxFMRz9otY/view?usp=sharing

## Paper/Poster/Slideshow
https://drive.google.com/drive/folders/1HgBIp6xx0IPQkQX9k5rKnBSkfzE9qeA4?usp=sharing
