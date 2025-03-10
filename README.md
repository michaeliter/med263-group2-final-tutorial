# med263-group2-final-tutorial
- here is the dropbox link to all relevant data files: https://www.dropbox.com/scl/fi/gbag21acr1lk61ntycy2m/Final-Project.zip?rlkey=gtzbb9396b8bphimdusw529wq&st=fa49pfg1&dl=0 (files were too big to upload to github)

# Instructions:
- Download zip file from dropbox link (2.2 Gb)
- When unzipped, this contains a Data folder with all relevant methylation data, and a Scripts folder with the R script tutorial
- The first chunk of the R script tutorial will have the following installation commands, which should be sufficient to complete all subsequent analyses:
  ```{r}
  if (!require("BiocManager", quietly = TRUE))
      install.packages("BiocManager")
  
  BiocManager::install("minfi")
  BiocManager::install("limma")
  BiocManager::install("qvalue")
  BiocManager::install("IlluminaHumanMethylationEPICanno.ilm10b4.hg19")
  BiocManager::install("biomaRt")
  BiocManager::install("missMethyl")
  BiocManager::install("EnhancedVolcano")
  BiocManager::install("FlowSorted.Blood.EPIC")
  
  install.packages("ggpubr")
  install.packages("tidyr")
  ```
  
