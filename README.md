# Product Sales Prediction and Customer Segmentation Framework

## Overview

This project presents a machine learning framework for an electronics retail business. It combines two key analytics tasks:

* **Product Review Classification**: Predicting product performance based on customer reviews
* **Customer Segmentation**: Grouping customers into clusters to support targeted marketing strategies

The project simulates a real-world business scenario where data-driven insights are used to improve inventory management and customer engagement.

---

## Objectives

### Part A – Review Classification

* Merge product and review datasets
* Convert ratings (1–5) into categories:

  * Bad (1–2)
  * Mediocre (3)
  * Good (4–5)
* Apply text preprocessing techniques
* Train and compare classification models:

  * Decision Tree
  * K-Nearest Neighbors (KNN)
* Evaluate model performance

---

### Part B – Customer Segmentation

* Clean and preprocess customer data
* Perform feature engineering (age, total spending, number of children)
* Simplify categorical variables (education, marital status)
* Apply K-Means clustering with different values of k
* Interpret customer segments for marketing insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* NLTK

---

## Project Structure

```
product-sales-and-customer-segmentation/
│
├── data/
│
├── notebooks/
│   ├── 01_review_classification.ipynb
│   └── 02_customer_segmentation.ipynb
│
├── README.md
└── requirements.txt
```

---

## Notebooks

### 01_review_classification.ipynb

This notebook contains the full workflow for text classification:

* Data merging
* Target variable creation
* Text preprocessing
* Feature extraction (TF-IDF)
* Model training (Decision Tree, KNN)
* Model evaluation

---

### 02_customer_segmentation.ipynb

This notebook contains the customer clustering analysis:

* Data cleaning and preprocessing
* Feature engineering
* Data scaling
* K-Means clustering
* Cluster visualization and interpretation

---

## Dataset

The datasets are not included in this repository.

To run the project, place the following files inside the `data/` folder:

* 20191226-items.csv
* 20191226-reviews.csv
* customers.csv

---

## Business Value

This framework enables businesses to:

* Predict product demand based on customer reviews
* Improve inventory management for high-demand products
* Segment customers for targeted marketing campaigns
* Support data-driven decision making

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Place datasets in the `data/` folder

3. Open and run the notebooks:

* `01_review_classification.ipynb`
* `02_customer_segmentation.ipynb`

---

## Author

Konstantinos Noulis
Data Analytics & Machine Learning Portfolio Project
