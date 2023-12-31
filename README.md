# Cachexia Single Cell Omics
scRNAseq Data Analysis Code
Muscle Inflammation is Regulated by NF-kB From Multiple Cells to
Control Distinct States of Wasting in Cancer Cachexia
==========================
This repository contains analysis code for the single cell RNA-seq project carried out by researchers at the [Guttridge lab, MUSC](https://medicine.musc.edu/departments/pediatrics/clinical-divisions/dcri/faculty/denis-guttridge) and [Berto Lab, MUSC](https://bertolab.org/)

## Cite this

If you use anything in this repository please cite the following publication:

Pre-print URL: 

## Access the data with an app:

Here a webapp to analyze the data:

[Pryce etal SingleCell Mouse KPP Negative](https://bioinformatics-musc.shinyapps.io/Pryce-et-al_SingleCell_Mouse_KPP_Negative/)

[Pryce etal SingleCell Mouse KPP Positive](https://bioinformatics-musc.shinyapps.io/Pryce-et-al_SingleCell_Mouse_KPP_Positive/)

[Pryce etal SingleCell Human Cachexia Negative](https://bioinformatics-musc.shinyapps.io/Pryce-et-al_SingleCell_Human_Cachexia_Negative/)

[Pryce etal SingleCell Human_Cachexia Positive](https://bioinformatics-musc.shinyapps.io/Pryce-et-al_SingleCell_Human_Cachexia_Positive/)

## Files

| directory | contents | code |
| --------- | -------- | -------- |
| [`KPP_MouseData_Analysis`](KPP_MouseData_Analysis/) | Code and Figuers for Mouse KPP Data | |
| [`KPP-output_Positive`](KPP_MouseData_Analysis/output_sct_Integrated_Positive) | Output data of the initial clustering and integration of Positive Dataset - CtrlPos and KppPos | 01_Seurat_Clustering_Positive.R \ 03_Doubletting_Positive.R \ 05_FindMarkers_Positive.R \ 07_CellCycleScoring.R|
| [`KPP-output_relabel_Positive`](KPP_MouseData_Analysis/output_Relabel_Positive/) | Output data of Cell annotation | 08_Relable_Positive.R| 
| [`KPP-output_Negative`](KPP_MouseData_Analysis/output_sct_Integrated_Negative) | Output data of the initial clustering and integration of Negative Dataset - CtrlNeg and KppNeg | 02_Seurat_Clustering_Negative.R \ 04_Doubletting_Negative.R \ 06_FindMarkers_Negative.R \ 07_CellCycleScoring.R|
| [`KPP-output_relabel_Negative`](KPP_MouseData_Analysis/output_Relabel_Negative/) | Output data of Cell annotation | 09_Relable_Negative.R|
| [`KPP-output_DGE`](KPP_MouseData_Analysis/output_DGE/) | Output of Differential gene expression for Positive and Negative data | 10_DGE.R |
| [`KPP-output_Figure_Positive`](KPP_MouseData_Analysis/output_Figure_Positive/) | Output data of final figures and FAPs subset analysis. | 11_Final_Figuers_Positive.R|
| [`KPP-output_Figure_Negative`](KPP_MouseData_Analysis/output_Figure_Negative/) | Output data of final figures and Macrophage subset analysis. | 11_Final_Figuers_Negative.R|
| [`KPP-shinyApp`](KPP_MouseData_Analysis/ShinyApp/) | Output of the ShinyApp. | 13_PreprocessForShiny_Positive.R\ 14_ShinyApp_Positive.R\ 15_PreprocessForShiny_Negative.R \ 16_ShinyApp_Negative.R |

| directory | contents | code |
| --------- | -------- | -------- |
| [`Cachexia_Human`](Cachexia_Human/) | Code and Figuers for Cachexia Human Data | |
| [`Cachexia_Human-output_Negative`](Cachexia_Human/output_sct_Integrated_Negative) | Output data of the initial clustering and integration of Negative Dataset - Neg_WS_PDAC, Neg_Control, Neg_C_PDAC | 01_Seurat_Clustering_Negative.R \ 03_Doubletting_Negative.R \ 05_CellCycleScoring.R \ 07_FindMarkers_Negative.R|
| [`Cachexia_Human-output_relabel_Negative`](Cachexia_Human/output_Relabel_Negative/) | Output data of Cell annotation | 09_Relable_Negative.R|
| [`Cachexia_Human-output_Positive`](Cachexia_Human/output_sct_Integrated_Positive) | Output data of the initial clustering and integration of Positive Dataset - Pos_WS_PDAC, Pos_Control, Pos_C_PDAC | 02_Seurat_Clustering_Positive.R \ 04_Doubletting_Positive.R \ 06_CellCycleScoring.R \ 08_FindMarkers_Negative.R|
| [`Cachexia_Human-output_relabel_Positive`](Cachexia_Human/output_Relabel_Positive/) | Output data of Cell annotation | 10_Relable_Positive.R| 
| [`Cachexia_Human-output_DGE`](Cachexia_Human/output_DGE/) | Output of Differential gene expression for Positive and Negative data | 11_DGE_Negative.R \ 12_DGE_Positive.R |
| [`Cachexia_Human-output_Figure_Negative`](Cachexia_Human/output_Figure_Negative/) | Output data of final figures and Macrophage subset analysis. | 13_Negative_FinalPlots.R|
| [`Cachexia_Human-output_Figure_Positive`](Cachexia_Human/output_Figure_Positive/) | Output data of final figures and FAPs subset analysis. | 14_Positive_FinalPlots.R|
| [`Cachexia_Human-shinyApp`](Cachexia_Human/output_Shiny/) | Output of the ShinyApp. | 15_PreprocessForShiny_Negative.R\ 15_ShinyApp_Negative.R\ 16_PreprocessForShiny_Positive.R \ 16_ShinyApp_Positive.R |

