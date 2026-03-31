# 🍔 Amazon Fine Food Reviews (Subsampled)

## Description

The dataset contains customer reviews of food products from Amazon.
It includes review text, ratings, and metadata about users and products.

This version is a **subsample of 10,000 reviews** from the original dataset, making it suitable for quick experimentation and NLP tasks.

Each row represents a single customer review.

---

## Target

* `Score` – rating from **1 to 5**

Commonly transformed into:

* sentiment classification (positive / negative)
* regression (predict rating)


## Features

* `Id` – unique review ID
* `ProductId` – product identifier
* `UserId` – user identifier
* `ProfileName` – reviewer name
* `HelpfulnessNumerator` – number of helpful votes
* `HelpfulnessDenominator` – total votes
* `Score` – rating (1–5)
* `Time` – timestamp
* `Summary` – short review title
* `Text` – full review text


## Shape

* **Rows:** 10,000
* **Columns:** 10

## Notes

* Subsampled from original dataset (~500k reviews)

* Contains **text + structured data**

* Minimal preprocessing required, but:

  * text cleaning may improve results
  * timestamps need conversion

* Common challenges:

  * class imbalance (more positive reviews)
  * noisy text

* Suitable for:

  * sentiment analysis
  * text classification
  * NLP feature extraction (TF-IDF, embeddings)
  * recommendation systems

## Example Use Cases

* Predict review sentiment
* Extract keywords from reviews
* Analyze most helpful reviews
* Build a simple recommendation model
  
## Source

* Kaggle: *Amazon Fine Food Reviews* https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
* Original dataset from SNAP (Stanford Network Analysis Project)
