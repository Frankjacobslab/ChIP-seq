# ChIP-seq
#### *Elise van Bree* - **The Frank Jacobs Lab**

## Aim:
Map Illumina ChIP-seq data on the human genome, build hg19.

## Components:
- Snakemake file for running pipeline.
- File containing comments used for making the snakefile.

## Requirements:
- Work from a directory that contains the file hg19.chrom.sizes and the script bedGraphToBigWig.
- Two directories above the working directory there should be a directory called bowtie, containing the indexed h919 genome, or change path in script to this directory (../../bowtie/).

### Notes:

