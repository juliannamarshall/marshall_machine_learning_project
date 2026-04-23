## Overview
This project explores both the internal structure of Airbnb listings in Los Angeles and the external influence of crime rates on those listings. Using clustering, regression, classification, and dimensionality reduction techniques, the analysis uncovers patterns in pricing, availability, and lcoation while evaluating whther crime is a meaningful predictor of Airbnb activity. 

## Goals
- Identify patterns in Airbnb listings using unsupervised learning
- Predict Airbnb prices using regression models
- Classify listing behavior using machine learning models
- Evaluate whether crime rates influence Airbnb distribution

## Methods Used
- Data cleaning and feature engineering
- Principal Component Analysis
- K-Means Clustering
- Linear Regression
- Decision Tree, Random Forest, Neural Network

## Project Sections
- [Raw Data](./RAW_DATA.md)
- [Data](./DATA.md)
- [Analysis](./ANALYSIS.md)
- [Conclusions](./CONCLUSIONS.md)

## Key Takeaways
- Airbnb listings naturally group into distinct clusters based on price, size, and availability
- A small number of features explain most of the variance in the dataset (via PCA)
- Regression models show moderate ability to predict price
- Classification models struggled, suggesting weak predictive signals
- Crime rate was not a strong standalone predictor of Airbnb patterns

  
## What I Learned
This project demonstrated that real world datasets often contain week or indirect relationships. While machine learning models can identify structure within Airbnb data, external factors like crime do not strongly explain listing behavior on their own.
