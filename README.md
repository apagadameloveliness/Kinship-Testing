# kinship-analysis
1) Set up dir: one folder for all output files
2) Extract data from SimLR files using [this file](<1_Clean SimLRs_v2_batch.ipynb>)
3) Run ROC analysis with or without De Long Test using [this file](<2_ROC_analysis_with_Delong_alpha01_Holm_with_CI_v5.ipynb>)
4) Merge all AUC files from different relationships using [this file](<3_Merge AUC files.ipynb>)
5) Plot all AUCs with error bars at 95% CI using [this file](<4_AUCwithCI Plot_all_relationships_v2.ipynb>)