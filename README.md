# NewChic-Product-Category-Classification
This project applies supervised machine learning techniques to classify e-commerce products from the NewChic dataset into appropriate categories. It involves data preprocessing, Naive Bayes, and Decision Tree classification to identify key product insights.

## Objective
- Analyze product data from NewChic.com.
- Predict product categories using classification models.
- Identify the best-performing algorithm and features.
- Report the top 10 products and best product category.

## Dataset
Combined dataset includes selected features from:
accessories.csv, bags.csv, beauty.csv, house.csv, jewelry.csv, kids.csv, men.csv, shoes.csv, women.csv

Used numerical attributes:
- current_price
- raw_price
- discount
- likes_count
- is_new

- Target:category (product category)

## Classification Algorithms
1. Naive Bayes (GaussianNB)
- Used 5-fold Stratified Cross-Validation.
- Evaluated using accuracy and classification report.
- Also used 10-fold cross-validation for additional validation.

2. Decision Tree
- Split data using train_test_split.
- Evaluated using accuracy, feature importance.
- Compared different criterion types (gini, entropy) using 10-fold CV.
- Tuned tree max_depth from 1 to 20 for optimal performance.
