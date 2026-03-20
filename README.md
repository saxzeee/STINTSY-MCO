# STINTSY-MCO

## Project Overview

This project applies supervised machine learning to the **Dry Bean Dataset** in order to **predict bean class based on shape, size, structure, and related physical measurement features**. The task is a multiclass classification problem where each sample belongs to one of several dry bean varieties.

## Machine Learning Task

**Predict bean class based on shape, size, structure, and other morphological features derived from bean measurements.**

Target variable:
- `Class`

Input features include:
- `Area`
- `Perimeter`
- `MajorAxisLength`
- `MinorAxisLength`
- `AspectRation`
- `Eccentricity`
- `ConvexArea`
- `EquivDiameter`
- `Extent`
- `Solidity`
- `roundness`
- `Compactness`
- `ShapeFactor1`
- `ShapeFactor2`
- `ShapeFactor3`
- `ShapeFactor4`

## Dataset

- Dataset name: `Dry Bean`
- Source: UCI Machine Learning Repository
- DOI: https://doi.org/10.24432/C50S4B
- Dataset page: https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

The dataset contains image-derived numerical measurements of dry beans. These measurements describe the beans' physical characteristics, which can be used to distinguish different bean varieties.

## Why This Task Is Interesting

Dry beans are nutritious ingredients widely used in protein-rich and vegetarian diets. Since each bean type has distinct physical characteristics and its own market value, building a model that can classify bean varieties from measurable features makes the task both practical and meaningful to explore.

## Project Contents

- `STINTSY-MCO-Group2.ipynb`:
  Full notebook containing data preprocessing, exploratory data analysis, model training, tuning, evaluation, and conclusions.

## Models Used

The notebook implements three supervised machine learning models:

- K-Nearest Neighbors
- Multinomial Logistic Regression
- Neural Network

## Output

The project compares the performance of the selected models and identifies the best-performing classifier for the dry bean classification task.
