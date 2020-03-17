## Readme for notebooks align_and_count and HISEQ_analysis
These notebooks perform the first steps of data analysis for the large-scale competition assay, by taking in the raw fastq files of the HISEQ run, performing qc, trimming reads, and then aligning them to reference indexes using bowtie. Index files are provided in this repository, but the raw sequencing data should be downloaded from the NCBI at accession number PRJNA552472.

The important output of these two notebooks is a table associating each gRNA to a z-score (if detected in the screen)
