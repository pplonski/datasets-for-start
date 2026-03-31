# 🍷 Red Wine Quality

## Description

The dataset contains physicochemical properties of red wines along with their quality ratings.
The data comes from Portuguese *Vinho Verde* wine samples and was collected for a study on wine quality prediction.

Each row represents a wine sample described by chemical measurements such as acidity, sugar, alcohol, and pH.
The goal is to predict the wine quality score based on these features.


## Target

* `quality` – integer score between **0 and 10**

## Features

* `fixed acidity` – non-volatile acids
* `volatile acidity` – acetic acid (higher → sour taste)
* `citric acid` – adds freshness
* `residual sugar` – remaining sugar after fermentation
* `chlorides` – salt content
* `free sulfur dioxide` – antimicrobial agent
* `total sulfur dioxide` – total SO₂
* `density` – related to sugar and alcohol
* `pH` – acidity level
* `sulphates` – preservative effect
* `alcohol` – alcohol content

## Shape

* **Rows:** 1599
* **Columns:** 12 (11 features + 1 target)


## Notes

* No missing values
* Target is **imbalanced** (most wines are average quality)
* Can be used for:

  * regression
  * classification (e.g., good vs bad wine)

## Source

* UCI Machine Learning Repository
* Cortez et al., 2009
* https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?select=winequality-red.csv
