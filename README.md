# BrainTumor-segmentation

## Overview

The Brain Tumor Segmentation (BraTS) focuses on the evaluation of state-of-the-art methods for the segmentation of brain tumors in multimodal magnetic resonance imaging (MRI) scans. This dataset, BraTS 2020, consists of multi-institutional pre-operative MRI scans primarily focused on the segmentation of intrinsically heterogeneous brain tumors, namely gliomas. Additionally, the dataset includes tasks related to patient overall survival prediction, distinguishing between pseudoprogression and true tumor recurrence, and evaluating algorithmic uncertainty in tumor segmentation.

## Tasks Description

### Task 1: Tumor Sub-region Segmentation
### Task 2: Patient Overall Survival Prediction
### Task 3: Progression Status Evaluation
### Task 4: Uncertainty Estimation

## Imaging Data Description

- **File Format**: NIfTI files (.nii.gz)
- **Modalities**:
  - Native (T1)
  - Post-contrast T1-weighted (T1Gd)
  - T2-weighted (T2)
  - T2 Fluid Attenuated Inversion Recovery (T2-FLAIR)


## Dataset Origin

The data was acquired from different clinical protocols and various scanners from multiple (n=19) institutions. All imaging datasets have been manually segmented by one to four raters following the same annotation protocol, and their annotations were approved by experienced neuro-radiologists.


## Usage

You can download the BraTS 2020 dataset from [Kaggle](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation). Please refer to the official BraTS documentation for detailed information on the dataset and evaluation metrics.
