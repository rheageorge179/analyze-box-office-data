Project: Analyze Box Office Data with Seaborn and Python

This project is part of a hands-on course titled **"Analyze Box Office Data with Seaborn and Python"**, focusing on building data visualization and exploratory data analysis (EDA) skills using the TMDB dataset.

## 📊 Project Overview

The goal of this project is to analyze movie metadata and uncover trends that impact box office revenue. The dataset includes information about over 7,000 films and their associated features like budget, revenue, language, homepage presence, and descriptions.

## ✅ Objectives

- Produce clean, insightful data visualizations using Seaborn.
- Apply graphical techniques for exploratory data analysis (EDA).
- Use `log1p`, categorical encoding, and linear regression to analyze skewed revenue data.

## 📁 Dataset

We use a version of the **TMDB Box Office Prediction** dataset, which includes metadata for thousands of films, originally published for a Kaggle competition.

## 📌 Key Tasks

### 1. Data Loading & Exploration
- Load TMDB dataset using `pandas`
- Explore key columns: `budget`, `revenue`, `original_language`, `homepage`, and `overview`

### 2. Target Distribution Visualization
- Visualize skewed `revenue` distribution using `sns.distplot()`
- Apply logarithmic transformation for better interpretability

### 3. Budget vs. Revenue Analysis
- Compare budget and revenue before and after log transformation
- Use scatter plots to reveal correlations

### 4. Impact of Official Homepage
- Feature engineering: `has_homepage` column
- Use `sns.catplot()` to visualize the effect of homepage presence on revenue

### 5. Language Distribution
- Identify top 10 most common original languages
- Compare revenue across languages using box plots

### 6. Word Cloud Analysis
- Generate word clouds for film titles and descriptions
- Identify commonly used terms in high-revenue movies


## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib
- Scikit-learn
- ELI5
- WordCloud
- Jupyter Notebook

## 📎 Output

All analysis is contained in the [`boxoffice_code.ipynb`] file.

## 📈 Sample Visualizations

- Revenue distribution (log-transformed)
- Budget vs Revenue scatter plot
- Homepage vs Revenue catplot
- Language-based revenue boxplot
- Word clouds of film titles and overviews


## 🚀 Future Work

- Extend the analysis using regression or tree-based models
- Explore genre-based insights
- Predict box office success using machine learning


## 📬 Contact
For questions or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/rheageorge99/).

