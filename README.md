# Data Mining Course Project - Movie Dataset Analysis

## Overview
 
This repository contains the implementation of a two-phase data mining project for the Data Mining course (Spring 1403, Persian Calendar). The project focuses on analyzing a movie dataset to uncover patterns and insights using clustering and classification techniques. Phase 1 involves exploratory data analysis and preprocessing, while Phase 2 focuses on clustering and classification tasks to identify patterns in movie attributes such as genres, revenue, production companies, and spoken languages.

The project is implemented in Python, utilizing libraries such as Pandas, NumPy, Scikit-learn, and NLTK for data processing, clustering, classification, and visualization. The goal is to analyze movie success factors, identify trends, and build predictive models.

## Features


### Phase 1: Dataset Exploration and Preprocessing





- Outlier Detection and Handling: Identified and managed outliers in the dataset (e.g., budget and revenue) using statistical methods like mean, median, or regression-based imputation.



- Data Normalization: Normalized numerical features to ensure compatibility with machine learning algorithms.



- Feature Engineering: Created new features from existing ones and transformed text data into numerical or categorical formats.



- Text Preprocessing: Applied NLP techniques (e.g., lemmatization, stemming, stopword removal) on textual columns like overview using the NLTK library.



- Genre Analysis: Analyzed movie genres to determine which genres generate the highest revenue and popularity.



- Production Company Analysis: Evaluated production companies to identify those associated with higher revenue and popularity.



- Adult Content Analysis: Compared the success (revenue and popularity) of adult vs. non-adult films.



- Language Analysis: Categorized movies based on spoken languages and analyzed their prevalence.



- Revenue-to-Budget Ratio: Calculated the revenue-to-budget ratio to assess financial success.



- Missing Data Handling: Imputed missing values using methods like mean, median, or regression.

### Phase 2: Clustering and Classification





Clustering:





- Performed clustering on numerical and categorical features using K-Means and DBSCAN algorithms.



-Analyzed clusters to identify patterns in movie attributes across seasons or years.



- Conducted hyperparameter tuning for K-Means and tested at least three configurations for DBSCAN.



-Evaluated clustering performance using appropriate metrics (e.g., silhouette score).



- Visualized clustering results to highlight patterns and relationships.



Classification:





- Selected features correlated with movie popularity and success.



- Split data into training and test sets for model evaluation.



- Built and evaluated classification models (specific algorithms not detailed in the provided documents, but typically include models like Decision Trees, SVM, or Random Forest in such projects).



- Visualization: Used charts and visualizations to represent clustering patterns and classification results.

