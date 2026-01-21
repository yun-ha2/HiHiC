# Hi-C Enhancement Analysis and Biological Benchmarking Framework

This repository provides a downstream analysis and benchmarking framework to evaluate whether Hi-C contact maps reconstructed by deep learning–based Hi-C enhancement models are biologically meaningful. Rather than proposing or training new enhancement models, this work focuses on systematic, quantitative, and biologically grounded evaluation of model-enhanced Hi-C data across multiple cell lines, resolutions, and downsampling levels.

## Overview
Deep learning–based Hi-C enhancement models aim to recover high-resolution chromatin contact maps from downsampled bulk Hi-C data. While many studies demonstrate visual improvements in enhanced Hi-C maps, comprehensive and quantitative assessments of their biological validity remain limited.

In this study, we evaluate whether enhanced Hi-C contact maps preserve biologically meaningful chromatin features by comparing original, downsampled, and model-enhanced Hi-C data using loop- and domain-level metrics.

## Data provenance

All Hi-C datasets analyzed in this repository were generated using
the HiHiC framework (https://github.com/jkrLab/HiHiC).

This repository does not reproduce data generation or model training,
and focuses exclusively on downstream analysis and evaluation.


## Analysis Design



