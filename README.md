# Arras-et-al-AJCR-2021_GSVA-BCAR3-correlation-calculations
 
This repository contains the code needed to calculate GSVA scores and Spearman rank correlations of those GSVA scores against BCAR3 mRNA expression data from the Cancer Cell Line Encyclopedia (CCLE) using data from all available triple-negative breast cancer (TNBC) cell lines in the CCLE, as shown in Figure 6 of Arras et al., *Breast Cancer Antiestrogen Resistance 3 (BCAR3) promotes tumor growth and progression in triple-negative breast cancer*. Am J Cancer Res 2021;11(10):4768-4787.

To perform these calculations, CCLE RNA-seq expression data must be downloaded from the Cancer Dependency Map (https://depmap.org/portal/download/) and added to the working directory while running the R notebook "BCAR3_CCLE_RNAseq_analysis_final.Rmd". For the analyses described here, data from DepMap Public 21Q2 release were used (file name: "CCLE_expression.csv").
