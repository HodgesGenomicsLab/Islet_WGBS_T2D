# Islet_WGBS_T2D
This is a repository of scripts used for the analyses within Miranda &amp; Hodges, 2025 ("Linking DNA methylation patterns in pancreatic islets to genetic risk for type-2 diabetes").

The first step for WGBS processing begins with trimming adapters and assessing quality of reads in raw fastq files. The resulting trimmed reads are used as input for a read mapping tool compatible with bisulfite-converted reads. We used WALT, which was developed by the Smith Lab at USC, but has since been deprecated and replaced with abismal by the same lab. The complexity of each genomic library is evalauted with preseq and then mapped reads are used as input to the methylation analysis pipeline, MethPipe (http://smithlabresearch.org/software/methpipe/), now called DNMTools, to determine methylation level summary statistics and, more relevant to our study - hypomethylated regions (HMRs). WGBS data in the form .hmr/.meth/.read files for cell types utilized in our manuscript (adipose, H1 ESC, B cell, and liver) are available publicly in the MethBase (legacy) track hub on the UCSC Genome Browser.

All scripts for processing WGBS data from our non-T2D donors (n=4) and creating figure panels are included in their respective folders.

## Scripts for Data Analysis

## Figure 1

## Figure 2

## Figure 3

## Figure 4

## Figure 5

## Figure 6 




