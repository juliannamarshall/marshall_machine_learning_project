# Technical Analysis

## Objective
To evaluate relationships within Airbnb data and determine whether crime rates can predict Airbnb listing behavior.

---

## Regression Analysis
Regression models were used to predict Airbnb prices.

### Findings:
- Moderate predictive ability
- Features like bedrooms, bathrooms, and availability contributed most
- Price is influenced by multiple interacting factors, not a single variable

---

## Classification Models

### Models Used:
- Decision Tree Classifier
- Random Forest Classifier
- Neural Network

### Results:
- Random Forest performed best
- Decision Tree showed moderate performance
- Neural Network performed poorly (likely due to limited feature strength and tuning)

### Interpretation:
The relatively low accuracy across models suggests that:
- The dataset lacks strong predictive signals for classification
- Airbnb behavior is influenced by complex, non-linear factors

---

## PCA Results
- PCA showed that most variance is captured in 2 components
- Indicates redundancy in original features
- Confirms that dimensionality reduction is effective for this dataset

---

## Clustering Results
- K-Means identified 3 meaningful groups
- These clusters reflect real-world listing categories
- Clustering provided more insight than classification models

---

## Crime vs Airbnb Analysis
- Crime data was aggregated and merged with Airbnb data
- Models attempted to use crime as a predictor

### Key Result:
- Crime rate had weak predictive power
- Did not significantly improve model performance

---

## Challenges
- Matching geographic data between datasets
- Handling missing values
- Weak correlations between datasets
- Model performance limitations

---

## Limitations
- Only a limited number of features used
- No socioeconomic or tourism data included
- Geographic matching was approximate

---

## Improvements
- Add external datasets (income, tourism, population density)
- Improve geographic precision
- Tune models more extensively
- Use geospatial models instead of standard ML
