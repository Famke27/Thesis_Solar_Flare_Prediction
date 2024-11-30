# Project Overview

Codes for the Solar Flare prediction with ViT and CNN. The dataset originates from [Dryad](https://datadryad.org/stash/dataset/doi:10.5061/dryad.jq2bvq898).

This repository contains various components of the project, organized as follows:

## Directory Structure

- **`models/`**  
  Contains model training scripts. Each model has its own dedicated notebook. Experimentation, including testing with different parameters, is primarily done in the notebooks for the CLAHE models. **`CNN on different train set`** and **`ViT on different train set`** are the models re-trained on a different split. Results for these models are also generated in these notebooks, and not in the **`results and error analysis/`**. 

- **`EDA_results_error_analysis/`**  
  Contains EDA results and error analysis scripts and notebooks.

  - **`EDA_colab/`**  
    Includes scripts for dataset splitting, undersampling, and exploratory data analysis (EDA). This directory also contains figures and graphs generated during the EDA process.

  - **`Testing the models/`**
    Creates the y_pred values used in the **`results and error analysis/`** by predicting the classes using the trained models and saves them to numpy files. 

  - **`overfitting/`**  
    Demonstrates the overfitting trends observed in CNN models. Includes plots of redundant images and analysis of overfitting behavior.

  - **`results and error analysis/`**  
    Contains the results notebook with outcome analysis and error evaluation.

  - **`inspecting_precision/`**  
    Focuses on inspecting false positives in greater detail. This notebook provides insights into the precision of the models.



   ** Note: in the models notebooks, the wrong test data was loaded in, leading to the wrong length when len(test) was printed. In the **`Testing the models`** notebook, all models have their final evalutation that is described in the results section of the thesis. The right test set is loaded in and its length is printed in this notebook. 
