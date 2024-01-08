# Leveraging Random Forest for Leukemia Typing

## Overview

This repository contains the code and analysis for a machine learning project focused on classifying leukemia subtypes (AML and ALL) based on gene expression data. The project explores the use of the random forest algorithm for classification and delves into feature importance using SHAP values.

## Table of Contents

- [Background](#background)
- [Dataset](#dataset)
- [Analysis Steps](#analysis-steps)
- [Results](#results)

## Background

The project is inspired by the seminal work of Golub et al. (1999) on molecular classification of cancer using gene expression monitoring. The goal is to leverage machine learning techniques to classify leukemia cases and uncover key genes contributing to the classification.

## Dataset

The dataset comprises gene expression measurements from patients with acute myeloid leukemia (AML) and acute lymphoblastic leukemia (ALL). The data were obtained from a proof-of-concept study published by Golub et al. in 1999.

## Analysis Steps

1. **Data Preprocessing**: Includes handling missing values, filtering based on call columns, and exploratory data analysis.
2. **Feature Selection**: Investigates the presence of genes across samples and explores percentiles for different call categories.
3. **Random Forest Classification**: Utilizes random forest for leukemia subtype classification.
4. **Evaluation Metrics**: Computes various metrics, including balanced accuracy, precision, recall, and F1-score.
5. **Feature Importance**: Analyzes feature importance using SHAP values.

## Results

The project achieves promising results in leukemia classification, with a focus on balancing precision and recall. Feature importance analysis provides insights into genes contributing to the classification.

![image](https://github.com/GiuliaPais/leukemia-typing-w-rf/assets/61320955/98aecda0-3166-4f78-9f38-a2be01f088d3)
![image](https://github.com/GiuliaPais/leukemia-typing-w-rf/assets/61320955/8657bbb9-c18e-4eab-abd4-c9b9de128c62)
![image](https://github.com/GiuliaPais/leukemia-typing-w-rf/assets/61320955/e25f931f-ea16-46ed-945c-e4b30d64e281)
![image](https://github.com/GiuliaPais/leukemia-typing-w-rf/assets/61320955/7b062e1e-c1e7-4a07-b4ec-7cef98ee7045)

