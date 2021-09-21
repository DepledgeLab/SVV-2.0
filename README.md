# SVV-2.0 #
## Refined SVV transcriptome annotation (2.0) ##

This repository contains files related to our recent re-annotation of SVV reference genome described here - LinkToBeAdded .

All  Illumina and Nanopore dRNA-Seq datasets associated with this study are available from the ENA under project accession [ PRJEB42868 ](https://www.ebi.ac.uk/ena/browser/view/PRJEB42868).

### Description of files: ###

Annotation directory:

The major annotation files (GFF3 format) are found in the Annotation directory and comprise the following:

- SVV-Delta-Forward-2.0.gff3 - GFF3 file denoting all SVV RNAs annotated along the top strand of SVV reference genome
- SVV-Delta-Reverse-2.0.gff3 - GFF3 file denoting all SVV RNAs annotated along the bottom strand of SVV reference genome

Addtional files include the SVV reference genome sequence and SVV2.0 transcriptome file:

- SVV-Delta.fasta - original SVV reference genome sequence in FASTA format (Genbank accession NC_002686.2). This version is compatible with BED12 files in IGV.
- SVV-Delta-EMC1.fasta - the genome sequence (FASTA format) of our SVV Delta-EMC1 isolate (Genbank accession tbc).
- SVV_v2.0_complete.fasta - SVV 2.0 transcriptome file (multi-fasta) - contains all SVV transcripts present in the v2.0 annotation

*Note: Users should ensure the header line in the genome fasta file matches the text used in column #1 of the GFF3 files prior to perform alignment and any downstream analyses

### BED12 directory: ###

BED12 format files containing Nanopore and Illumina read alignments are found in the BED12 folder and comprise the following:

- SVV_BSC1-1.genome.sorted.forward.bed
- SVV_BSC1-1.genome.sorted.reverse.bed
- SVV_CM0053.genome.sorted.forward.bed
- SVV_CM0053.genome.sorted.reverse.bed
- SVV_RM-merged.genome.sorted.forward.bed
- SVV_RM-merged.genome.sorted.reverse.bed

*Note: these files were generated using nanopore dRNA-Seq datasets basecalled with Guppy v3.6.0

### CDS_Differences-Delta-vs-Delta-EMC1 directory: ###

These files contain nucleotide and amino acid sequences for coding domains (CDS) of named ORFs in which differences are observed between the SVV Delta and Delta-EMC1 variants (see Supplementary Table - Description of coding differences between Delta and Delta-EMC1.xlsx)

