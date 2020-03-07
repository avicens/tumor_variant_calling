# Identification of short somatic variants in tumor samples

## Description
Here it is presented a pipeline to identify somatic short variants in tumor samples with respect to a matched normal sample. It spans all steps for proccessing whole exome sequencing (WES) data from tumor and paired normal sample and posterior detection of somatic variants.

## Environment
The different tasks were run in a high-performance computing cluster (*Finisterrae II*) managed by Slurm scheduling system.

## Sample data
The sample datasets used to test the pipeline are WES data from a colorectal tumor sample and its normal-paired sample.

## Reference genome
The reference human genome used for mapping reads is hg19 (aka b37).

## Input 
Paired-end sequencing reads from Illumina in Fastq format.

## Output
Set of somatic variants in VCF file

## Time and computing costs
Time and cost estimates can vary depending on the performance of computing cluster, the number of samples and their size.






