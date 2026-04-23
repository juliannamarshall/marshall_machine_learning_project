# Data Exploration and Preparation

## Overview
The datasets required significant preprocessing before analysis. The goals was to clean, align, and reduct the data into meaningful features for modeling.

---

## Crime Data Processing
- Filtered relevant columns (location, crime type)
- Aggregated crime incidents by geographic area
- Created a new feature, crime intesity (crime count per area)

## Airbnb Data Processing
- Removed missing and null values
- Selected relevant numerical features: price, bedrooms, bathrooms, number of reviews, availability 365
- Removed unnecessary text based columns
- Standardized formats for analysis


---

## Feature Engineering
- Matched Airbnb listings and crime data using location
- Converted raw data into structured numerical features
- Ensured compatibility across datasets for modeling

---

## Dimensionality Reduction (PCA)
Principal Component Analysis was applied to understand variance structure:

- PC1 explained ~36% of variance
- PC2 explained ~22% of variance
- Total of ~59% variance explained with two components

This indicates that a small number of features capture most of the dataset’s structure.

---

## Clustering (K-Means)
K-Means clustering was applied to Airbnb data:

- Identified 3 clusters
- Clusters represent different types of listings:
  - Lower-priced, high-availability listings
  - Mid-range listings
  - Higher-priced, lower-availability listings

This reveals natural groupings in the Airbnb market.

---

## Key Observations
- Airbnb listings are not evenly distributed
- Strong internal structure exists in pricing and availability
- Crime data required heavy transformation to be usable
