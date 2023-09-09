# Machine Learning Project README

This repository contains code and analysis for a machine learning project that explores three different datasets and applies various classification algorithms. The project aims to predict outcomes in different scenarios using different machine learning models.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Setup](#setup)
- [Gene Expression Dataset](#gene-expression-dataset)
- [Income Dataset](#income-dataset)
- [Heart Disease Dataset](#heart-disease-dataset)
- [Conclusion](#conclusion)

## Introduction

This project explores three distinct datasets and applies machine learning models to predict outcomes. The datasets used are:

1. **Gene Expression Dataset**: Predicting cancer presence based on gene expression data.
2. **Income Dataset**: Predicting income levels (>50K or <=50K) based on demographic and employment information.
3. **Heart Disease Dataset**: Predicting the presence of heart disease based on health indicators.

Different classification algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Machines (SVM) are applied to each dataset, and their performances are evaluated based on various metrics.

## Datasets

- [Gene Expression Dataset](gene_expression.csv): Contains gene expression data with a binary target variable indicating cancer presence.

- [Income Dataset](income/train.csv): Includes demographic and employment data with a binary target variable indicating income levels.

- [Heart Disease Dataset](heart_disease_health_indicators_BRFSS2015.csv): Consists of health indicator data with a binary target variable indicating heart disease presence.

## Setup

To run the code in this project, you need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using `pip` or `conda`. For example:
pip install pandas numpy matplotlib seaborn scikit-learn

## Gene Expression Dataset

This section of the project focuses on the Gene Expression Dataset. It includes data visualization, feature engineering, model selection, and evaluation. The chosen model is Logistic Regression.

## Income Dataset

The Income Dataset analysis is covered in this section. It involves handling missing values, feature engineering, model selection, and evaluation. Logistic Regression, KNN, and SVM models are applied.

## Heart Disease Dataset

This section explores the Heart Disease Dataset. It includes preprocessing, model selection (Logistic Regression, KNN, SVM), and evaluation. Emphasis is placed on recall as we aim to detect heart disease accurately.

## Conclusion

The conclusion section summarizes the results and key findings from the project. It highlights the best-performing models for each dataset and the reasoning behind their performance. The impact of data characteristics and model choice on performance is discussed.

For detailed code and analysis, please refer to the respective notebook files.

Feel free to explore the code and analysis in each notebook for more in-depth information about each dataset and model's performance.


