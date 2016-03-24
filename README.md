# Scripts
A collection of basic scripts used in bioinformatic analysis


## SGE scripts

Our cloud computing facility uses SGE.
One of the ways to intereact with this system is by submitting scripts as jobs using `qsub`.
Some examples of these scripts are here:

[SGE scripts](https://github.com/knausb/SGE_scripts)


## Read alignment

Reads can be aligned to a reference using bwa, bowtie2 or other aligners.
An example of using bowtie2 can be found in the file 'bt2b.sh' here:

[Read alignment](https://github.com/knausb/SGE_scripts)


## BAM improvement

Once reads have been aligned to a reference (e.g., using bwa or bowtie2) and converted to a bam, sorted and indexed (using SAMtools) we recommend a bam improvement step.
This is our attempt at implementing the 1k genomes project on our SGE cloud.

[BAM improvement](https://github.com/knausb/bam_processing)


## Variant calling

Once you have production BAM files, you can call variants.
This can be done with SAMtools, FreeBayes, the GATK or other variant callers.
We have examples of using bwa (bwa_mem_pe.sh) and SAMtools.

[Variant calling](https://github.com/knausb/SGE_scripts)


