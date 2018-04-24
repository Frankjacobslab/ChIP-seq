# ChIP-seq
#### *Elise van Bree* - **The Frank Jacobs Lab**

## Aim:
Map paired-end Illumina ChIP-seq data on the human genome, build hg19.

## Components:
- Snakemake file for running pipeline.
- Config file with samples
- File containing commands used for making the snakefile.
- bedGraphToBigWig script

## Requirements:
- Work from a directory that contains the file hg19.chrom.sizes and the script bedGraphToBigWig from UCSC.
- Two directories above the working directory there should be a directory called bowtie, containing the indexed hg19 genome, or change path in script to this directory (../../bowtie/).

## Adjustments to do before running:
- rule bowtie2: check the use of -X and -I for munimum and maximum fragment length for valid paired-end allignments and change these in the script.

### Notes:

