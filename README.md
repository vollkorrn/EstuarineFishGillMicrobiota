A repository for the analysis of estuarine fish gill mucus microbiota composition over space and time. The dataset and analysis comprises 250 16S samples from two fish species and bacterioplankton samples as well as abiotic and physiological data. 

The Analysis splits into 6 parts: 

0: 16S Dataprocessing-Pipeline used on Linux-HPC: EstuarineFishGillMicrobiota_dada2_21.07.24.Rmd
1: Abundance filtering and abiotics visulization: EstuarineFishGillMicrobiota_part1_21.07.24.Rmd
2: Alpha Diversity analyses and fish physiology visualization: EstuarineFishGillMicrobiota_part2_21.07.24.Rmd
3: Beta Diversity analyses (PCA, CCA, PCOA, NMDS, PERMANOVA; dbRDA, Venn: EstuarineFishGillMicrobiota_part3_21.07.24.Rmd
4: Differential Abundance Testing/Indicator Species analyses: EstuarineFishGillMicrobiota_part4_21.07.24.Rmd
5: Co-Occurence network analyses (WGCNA) and Visualizaiton (Integrated heatmaps & Cytoscape handover): EstuarineFishGillMicrobiota_part5_21.07.24.Rmd

Additional files: Every .rmd is accompanied by a markdown .html that includes a subset of plots and results

Fish_Functions_19.07.24_Paper.Rmd is a Functions-File that has to be saved in the R-directory and loaded in section ## 1.2 Functions in every .rmd

All Input data needed (Metadata, processed and raw 16S Data, Abiotics etc are providid in the Folder Fish_Input_16S 
Additionally, analyses outputs are provided in the Folder Fish_Output_16S 

Sequence data are deposited in the ENA Sequence Read archive under study PRJEB77621
