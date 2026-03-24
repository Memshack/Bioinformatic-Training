# Bioinformatic-Training
Bioinformatics Whole-Genome Alignment Training – January Workshop

This repository contains the training workflow and materials used during the January Bioinformatics Seminar, where 30+ undergraduate and postgraduate participants were introduced to practical bioinformatics and whole-genome sequencing data analysis using a hands-on Linux-based workflow.

The training focused on whole-genome read alignment, starting from raw sequencing data in the NCBI Sequence Read Archive (SRA) to aligned, sorted, and indexed BAM files ready for genome visualization in IGV.

Training Overview

Participants were guided through a complete bioinformatics pipeline including:

Downloading sequencing data from NCBI SRA
Converting SRA files to FASTQ
Performing quality control using FastQC
Downloading and preparing reference genomes
Indexing genomes using BWA
Aligning sequencing reads to reference genomes
Converting SAM → BAM
Sorting and indexing BAM files using SAMtools
Generating alignment statistics
Visualizing alignments in IGV (Integrative Genomics Viewer)
Organism and Dataset Used
Organism: Escherichia coli
Sample: SRR36879872
Reference Genomes:
E. coli K-12 MG1655 (laboratory strain)
E. coli O157:H7 Sakai (pathogenic strain)
Learning Objectives

By the end of the seminar, participants were able to:

Navigate a Linux environment for bioinformatics
Retrieve sequencing data from public databases
Perform FASTQ quality control
Index reference genomes
Align sequencing reads to a genome
Process alignment files (SAM/BAM)
Generate alignment statistics
Visualize genome alignments in IGV
Understand the complete workflow of whole-genome read alignment
Tools Used
NCBI Entrez Direct
SRA Toolkit
FastQC
BWA
SAMtools
IGV
Workflow Endpoint

The final output of the workflow includes:

Sorted BAM file
BAM index file
Alignment statistics
Files ready for visualization in IGV
