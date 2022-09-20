---
title: Clusterprofiler report generator
subtitle: Automated workflow in Snakemake for running patways analysis data with clusterprofiler
image: assets/img/portfolio/clusterprofiler_programming_thumb.png
alt: Pathway analysis visualisation

caption:
  title: Clusterprofiler report generator
  subtitle: Automated Workflow for RNASeq Pathway Analysis and Visualisation 
  thumbnail: assets/img/portfolio/clusterprofiler_programming_thumb.png
---

This is an automated workflow solution for an amazing package [clusterprofiler](https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html) that offers an easy way to run batch pathway analysis of an RNASeq dataset over a parameter space of your choice. It also produces interactive HTML reports with network graphs. This project was started when my colleagues and collaborators kept asking to re-run pathway analysis for their RNASeq data while slighly varying the analysis parameters and gene set selection. I also was not happy with the default network graphs that are part of clusterprofiler. They tend to get quite messy with larger gene sets, so I opted for interactive HTML reporting that allows for zooming and panning. You can find the source code in my [Github](). There are two additional tools that I developed for batch pathway analysis. First one is a interactive HTML report generator for [Ingenuity Pathway Analysis](https://digitalinsights.qiagen.com/products-overview/discovery-insights-portfolio/analysis-and-visualization/qiagen-ipa/) from Qiagen that can be found [here](https://github.com/icervenka/ipa_reports_snakemake) and a tool for running batch [GSEA](https://www.gsea-msigdb.org/gsea/index.jsp) analysis with their commandline tools that can be found [here](https://github.com/icervenka/gsea_batch_snakemake)

{:.list-inline}
- Date: January 2020
- Category: Workflow Automation