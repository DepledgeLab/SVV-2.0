# SVV-2.0
## Refined SVV transcriptome annotation (2.0)

This repository contains files related to our recent re-annotation of SVV reference genome described here - LinkToBeAdded .

All  Illumina and Nanopore dRNA-Seq datasets associated with this study are available from the ENA under project accession [ PRJEB42868 ](https://www.ebi.ac.uk/ena/browser/view/PRJEB42868).

Description of files:

Annotation directory:

The major annotation files (GFF3 format) are found in the Annotation directory and comprise the following:

SVV-Forward-2.0.gff3 - GFF3 file denoting all SVV RNAs annotated along the top strand of SVV reference genome

SVV-Reverse-2.0.gff3 - GFF3 file denoting all SVV RNAs annotated along the bottom strand of SVV reference genome

SVV_v2.0_complete.fasta - SVV 2.0 transcriptome file (multi-fasta) - contains all SVV transcripts present in the v2.0 annotation

Note: Users should ensure the header line in the genome fasta file matches the text used in column #1 of the GFF3 files prior to perform alignment and any downstream analyses

BED12 directory:

BED12 format files containing Nanopore and Illumina read alignments are found in the BED12 folder and comprise the following:

XXX
XXX
XXX
XXX

SVV.fasta - original SVV reference genome sequence in FASTA format (Genbank accession NC_002686.2). This version is compatible with BED12 files in IGV.

Note: these files were generated using nanopore dRNA-Seq datasets basecalled with Guppy v3.6.0

