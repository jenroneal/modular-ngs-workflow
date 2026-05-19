# Modular NGS Workflow Foundations

This repository documents a modular next-generation sequencing (NGS) workflow integrating sequence preprocessing, alignment-based genomic annotation, and variant-level biological interpretation using Python, samtools, and bedtools.

The workflow reflects common data transformations and analysis stages used in genomics pipelines and is intended for educational and demonstration purposes.

## Workflow Overview

### 1. Raw Read Preprocessing

Sequencing reads are parsed from FASTQ format and converted to FASTA format to support downstream sequence-based analyses and preprocessing workflows.

### 2. Alignment-Derived Feature Annotation

Alignment outputs in SAM format are converted to BED interval format and annotated based on overlapping genomic features using standard bioinformatics tools.

### 3. Variant-Level Biological Interpretation

Single-nucleotide variants are mapped to coding sequences and classified as synonymous, missense, or nonsense mutations with codon-level and protein-level interpretation.

## Tools and Technologies

- Python
- Bash shell scripting
- samtools
- bedtools

## Workflow Components

### FASTQ to FASTA Converter (Python)

Sequence preprocessing utility for converting FASTQ sequencing reads into FASTA format.

https://github.com/jenroneal/fastq-to-fasta-python

### SAM to BED Feature Annotation

Alignment-processing workflow using samtools and bedtools for genomic interval annotation.

https://github.com/jenroneal/sam-bed-feature-annotation

### TP53 Codon-Level Variant Annotation (Python)

Variant interpretation workflow for codon-level classification of TP53 sequence variants.

https://github.com/jenroneal/tp53-codon-variant-annotation

## Biological Relevance

This modular workflow demonstrates foundational concepts commonly used in genomics and transcriptomics analysis pipelines, including sequence preprocessing, genomic interval annotation, and biological interpretation of coding variants.

## Notes

- Each workflow component is implemented as a standalone and reusable module.
- No clinical or patient data are included.
- The repository is intended for educational and computational biology portfolio purposes.
