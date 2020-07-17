# Transcriptional differences among four Miscanthus species (M. sacchariflorus, M. sinensis, M. x giganteus, and a triploid M. sacchariflorus X M. sinensis) under three water regimes: control, waterlogging (saturated) and drought (low soil mousture).

This repository contains the code of the RNA-seq analysis from our paper, which is available in X.

**The R notebook (rnaseq_analysis.Rmd) is fully run here with all the figures:
https://joseja.github.io/miscanthus_drought_rnaseq/

# Repository contents
The R markdown raw file is complete_analysis.Rmd in the main folder, that is all you need together with the files in the INPUT folder: The counts are available in the text table, and the phenotypes (metadata) is also in a txt file. All the other files can be generated during the execution of the R notebook.

# Functional annotation of the Miscanthus sinensis genome
The folder 'input' contains a functional annotation of the M. sinensis genome v.7.1 available in phytozome using Blast2GO. The folder contains the GO terms in the format for topGO that the analysis uses.
