# Project Overview

Codes for the Solar Flare prediction with ViT and CNN. The dataset originates from [Dryad](https://datadryad.org/stash/dataset/doi:10.5061/dryad.jq2bvq898).

This repository contains various components of the project, organized as follows:

## Directory Structure

- **`models/`**  
  Contains model training scripts. Each model has its own dedicated notebook. Experimentation, including testing with different parameters, is primarily done in the notebooks for the CLAHE models.

- **`EDA_results_error_analysis/`**  
  Contains EDA results and error analysis scripts and notebooks.

- **`EDA_colab/`**  
  Includes scripts for dataset splitting, undersampling, and exploratory data analysis (EDA). This directory also contains figures and graphs generated during the EDA process.

- **`overfitting/`**  
  Demonstrates the overfitting trends observed in CNN models. Includes plots of redundant images and analysis of overfitting behavior.

- **`results and error analysis/`**  
  Contains the results notebook with outcome analysis and error evaluation.

- **`inspecting_precision/`**  
  Focuses on inspecting false positives in greater detail. This notebook provides insights into the precision of the models.
