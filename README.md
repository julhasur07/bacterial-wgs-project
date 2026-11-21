# Bacterial Whole-Genome Sequencing Analysis

## Project Overview

This project demonstrates a reproducible bacterial whole-genome
sequencing (WGS) analysis workflow using paired-end Illumina reads.

## Research Question

How do sequencing reads from a bacterial mutant compare with
a reference genome, and what candidate SNPs and indels are present?

## Dataset

Source: Galaxy Training Network / Zenodo Record 582600

The dataset contains an imaginary, miniature Staphylococcus aureus
reference genome and corresponding mutant sequencing reads.

This dataset is intended for bioinformatics training and does not
represent a real clinical or environmental bacterial isolate.

## Analysis Workflow

1. Raw sequencing data inspection
2. Quality control using FastQC and MultiQC
3. Read trimming using fastp
4. Reference alignment using BWA-MEM
5. BAM processing and coverage analysis using SAMtools
6. Variant calling and filtering using bcftools
7. Coverage visualization using Python, Pandas, and Matplotlib

## Results

Results will be summarized using the verified analysis outputs.

## Limitations

This project uses a synthetic training dataset. Candidate variants
and coverage patterns should not be interpreted as biological
discoveries from a real bacterial isolate.
