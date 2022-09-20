---
title: RNASeq pipeline
subtitle: Automated workflow in Snakemake for analysing batch RNASeq data
image: assets/img/portfolio/rnaseq_workflow_programming_thumb.png
alt: RNSeq data visualisation

caption:
  title: RNASeq Analysis
  subtitle: Automated workflow for RNASeq Analysis and Visualisation
  thumbnail: assets/img/portfolio/rnaseq_workflow_programming_thumb.png
---

This Snakemake pipeline will analyze RNAseq data starting from fastq files to producing interactive visual reports for differential gene expression. Several of the most common aligners, read counters and packages for differential expression are included as well as the utility to specify SRA accession numbers and the pipeline will download the corresponding files. I always wanted to have a solution in which I can mix and match different aligners, counters etc. as well as easy way to handle custom parameters to different programs, so the pipeline is designed in a way that you can swap them in and out. Some of the most common workflows are predifined, but you can supply your own. This is a long running project that I started when I took over the bioinformatician duties in the laboratory and work started to pile up and I needed a easy-to-use scalable solution. It's also a work in progress, I try to keep up with the developments in the field and add them as time permits. For code see my [Github](https://github.com/icervenka/rnaseq_pipeline_snakemake), previous simple solution with python and bash-scripts is for posteriority archived [here](https://github.com/icervenka/rnaseq_pipeline_legacy)

{:.list-inline}
- Date: 2018
- Category: Workflow Automation