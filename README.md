# Hi-C Enhancement Analysis and Biological Benchmarking Framework

This repository provides a downstream analysis and benchmarking framework to evaluate whether Hi-C contact maps reconstructed by deep learning–based Hi-C enhancement models are biologically meaningful. Rather than proposing or training new enhancement models, this work focuses on systematic, quantitative, and biologically grounded evaluation of model-enhanced Hi-C data across multiple cell lines, resolutions, and downsampling levels.

## Overview
Deep learning–based Hi-C enhancement models aim to recover high-resolution chromatin contact maps from downsampled bulk Hi-C data. While many studies demonstrate visual improvements in enhanced Hi-C maps, comprehensive and quantitative assessments of their biological validity remain limited.

In this study, we evaluate whether enhanced Hi-C contact maps preserve biologically meaningful chromatin features by comparing original, downsampled, and model-enhanced Hi-C data using loop- and domain-level metrics.

## Data provenance
This repository focuses on **downstream analysis, evaluation, and visualization*  of Hi-C data enhanced by deep learning–based Hi-C enhancement models.

- Data generation, preprocessing, and model training were performed using
  the HiHiC framework:
  https://github.com/jkrLab/HiHiC
- This repository does **not** reproduce data generation or model training.


## Analysis Design
For each experiment, we compared three types of Hi-C contact maps:

1. Original high-depth bulk Hi-C data
2. Downsampled low-depth bulk Hi-C data
3. Hi-C maps enhanced by deep learning–based super-resolution models

Analyses were conducted across:
- Multiple cell lines (e.g., GM12878, K562, CH12-LX)
- Multiple downsampling depths (e.g., 5M,4M,3M,2M)
- Multiple enhancement models ()


