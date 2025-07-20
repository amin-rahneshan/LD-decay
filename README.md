This analysis began with the "LD for genome D.csv" dataset.
Using TASSEL, I split the genome-wide data by individual chromosomes and subgenomes, exporting each segment as separate CSV files for targeted analysis.
These files were then processed through a Python script that automatically generates LD decay plots (R² vs. genetic distance) and 
calculates key statistics including mean R² values and decay point estimates.
The workflow produces both graphical outputs and textual summaries for each chromosomal and subgenomic segment,
enabling direct comparison of LD patterns across different genomic regions while maintaining consistent analysis parameters throughout.
The results provide detailed insights into recombination characteristics across the genome,
with high-resolution decay plots and comprehensive statistical outputs for each analyzed segment.
