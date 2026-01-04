# modular-ngs-workflow
Modular NGS workflow demonstrating sequencing data preprocessing, alignment-based annotation, and variant-level biological interpretation using Python, samtools, and bedtools.
# Modular NGS Workflow Foundations

This repository documents a modular next-generation sequencing (NGS) workflow
built from individual preprocessing, alignment-based annotation, and variant
interpretation components. The workflow reflects common data transformations
used in NGS analysis pipelines and is intended for educational and demonstration
purposes.

## Workflow Overview

1. Raw read preprocessing  
Sequencing reads are parsed from FASTQ format and converted to FASTA format to
support downstream sequence-based analyses.

2. Alignment-derived feature annotation  
Alignment outputs in SAM format are converted to BED format and annotated based
on overlapping genomic features using standard bioinformatics tools.

3. Variant-level biological interpretation  
Single-nucleotide variants are mapped to coding sequences and classified as
synonymous, missense, or nonsense mutations, with protein-level comparison.

## Implementation Repositories

- FASTQ to FASTA Converter (Python)  
  https://github.com/jenroneal/fastq-to-fasta-python

- SAM to BED Feature Annotation (samtools, bedtools)  
  https://github.com/jenroneal/sam-bed-feature-annotation

- TP53 Codon-Level Variant Annotation (Python)  
  https://github.com/jenroneal/tp53-codon-variant-annotation

## Notes

- Each component is implemented as a standalone, reusable script.
- No clinical or patient data are included.
