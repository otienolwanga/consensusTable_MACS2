# consensusTable_MACS2
Generate a consensus table from MACS2 individual https://mariatsayo.github.io/consensusTable_MACS2/

## Introduction to the project:
[MACS2](https://github.com/taoliu/MACS) output includes individual peaks files which are not appropriate for the dowstream analysis e.g.
1. PCA analysis
1. differential region analysis with more than one groups of interest
1. heatmaps

## Code
Firstly, we have to combine all the detected peaks on the **same** *.bed file*

` bedtools ............. ` 
