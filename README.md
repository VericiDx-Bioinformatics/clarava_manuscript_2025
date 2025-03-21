# 2025 Figures 
Code to generate visualizations for Clarava manuscript in 2025.

## DEGs_ABMRvTCMR.Rmd
Performs DEGs and GSEA between ABMR and TCMR only in deceased donors.
Required SharePoint Files:
- [Clarava_validation_122samples_annotations_pred_longterm_outcomes_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EYzEfseaylREsJKdrt82u7kB1kllosokEyomimVgv1urZg?e=3yBO5D)
-[Clarava_deceased_donor_training_5_Annotations_Allinclusive_ar_WithBinaryReject_ar_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/ERyzCcJcC0hNmWTTGF1huzYB0dkEzcMf9FJlBGBTF23WJQ?e=tGKbm1)
- [CT1_Stratified_Validation_TPM_122samples.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/Eb6udeV231dAkDLwYhwVKIoBSdpwB_QaC2ZGUZiEZ8-DXA?e=Nc9bN1)
- [CT1_Stratified_Training_deceased_donor_TPM_11K.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EXsWrhdRRHJKpLyC_v4ApMQBR7gz6YAxpB2Z0nEcDnuLHQ?e=N5rCZa)

## iSort Folder
Contains all code for generating iSort plots and the tables used for input to iSort

### iSort_Plots Folder
Contains codes for generating iSort plots

#### iSort_Plots.Rmd
Looks at iSort results in deceased donors between A) Rejects and No Rejects and B) ABMR and TCMR within Clarava Rejects.

Required SharePoint Files:
- [Clarava_validation_122samples_annotations_pred_longterm_outcomes_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EYzEfseaylREsJKdrt82u7kB1kllosokEyomimVgv1urZg?e=3yBO5D)
- [Clarava_deceased_donor_training_5_Annotations_Allinclusive_ar_WithBinaryReject_ar_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/ERyzCcJcC0hNmWTTGF1huzYB0dkEzcMf9FJlBGBTF23WJQ?e=tGKbm1)
- [iSort_job63-121324-160003_Relative_AdjustedB.txt](https://verici.sharepoint.com/:t:/s/VericiAssaysDevelopment/EfWFr4Q2Xh9LiqoRmZVfnTUBQG6WyL0JnZkrOMTm0xpphw?e=XlCELG)

#### iSort_LDvDD.Rmd
Looks at iSort results between LD and DD.

Required SharePoint Files:
- [iSort_job63-121324-160003_Relative_AdjustedB.txt](https://verici.sharepoint.com/:t:/s/VericiAssaysDevelopment/EfWFr4Q2Xh9LiqoRmZVfnTUBQG6WyL0JnZkrOMTm0xpphw?e=XlCELG)
- [iSort_job76-031925-200003_Relative_AdjustedB.txt](https://verici.sharepoint.com/:t:/s/VericiAssaysDevelopment/ERZ8BWu5naBOgv6U3to8U7cBAIxM9_y9Ofo7JIYz8PW7Nw?e=wjYkDE)

### iSort_Prep Folder
Contains .Rmd files that get TPM into the correct form for running iSort.

### iSortPrep_LD.Rmd
Makes the TPM from LD into format for iSort run.

Required SharePoint Files:
- [Clarava_LD_n76_bxoutcome_sampleID.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EaGixfB7w0lNmmAw_Wj4edIBPYj2vjGPrBGjur6uTgbbUg?e=8jcwf1)
- [CT1_Stratified_Validation_TPM.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/Ea6_BbCQ7CNPrvmYRiYdfi8B8haq2jeDOS7aEJh08I5z6g?e=KAqPuV)
- [CT1_Stratified_Training_TPM.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EeeIUto1cG9CoIQ2D4UkzgIBfrrTy0FgX0-DKAmchem0Aw?e=LfqPu5)
- [Clarava_May_123Train_AllInclusive_Annotations_WithBinaryReject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EQ7l1OwH9gdFqOS4an4zo-8BEkcPqTF4bHX7aKTCE5PuBQ?e=hsUigA)

### WGNCA Folder
performs WGNCA on the Clarava data to compare with iSort results. Not completed

Required SharePoint Files:
- [Clarava_deceased_donor_Training_Annotations_AllInclusive_WithBinaryReject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EX2TF2XhK2xOmBxTeEqCbJ4BvJKI-wU3plQ3SMWEisZQQA?e=QhWVDf)
- [Clarava_May_123Train_AllInclusive_Annotations_WithBinaryReject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EQ7l1OwH9gdFqOS4an4zo-8BEkcPqTF4bHX7aKTCE5PuBQ?e=hsUigA)
- [Clarava_validation_122samples_annotations_pred_longterm_outcomes_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EYzEfseaylREsJKdrt82u7kB1kllosokEyomimVgv1urZg?e=3yBO5D)
- [Clarava_deceased_donor_training_5_Annotations_Allinclusive_ar_WithBinaryReject_ar_ryan_reject.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/ERyzCcJcC0hNmWTTGF1huzYB0dkEzcMf9FJlBGBTF23WJQ?e=tGKbm1)
- [CT1_Stratified_Validation_TPM.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/Ea6_BbCQ7CNPrvmYRiYdfi8B8haq2jeDOS7aEJh08I5z6g?e=KAqPuV)
- [CT1_Stratified_Training_TPM.csv](https://verici.sharepoint.com/:x:/s/VericiAssaysDevelopment/EeeIUto1cG9CoIQ2D4UkzgIBfrrTy0FgX0-DKAmchem0Aw?e=LfqPu5)
- [iSort_job63-121324-160003_Relative_AdjustedB.txt](https://verici.sharepoint.com/:t:/s/VericiAssaysDevelopment/EfWFr4Q2Xh9LiqoRmZVfnTUBQG6WyL0JnZkrOMTm0xpphw?e=XlCELG)

## SingleFiles.Rmd
- Combines TPM, iSort and Metadata used in the clarava plots herein into single files to reduce confusion.


