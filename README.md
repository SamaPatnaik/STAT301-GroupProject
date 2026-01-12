# Hungary Airbnb Price Prediction (Budapest Case Study)

## Project Overview
Airbnb has become one of the most widely used platforms for short-term accommodation in major cities, and Budapest is no exception. A growing mix of private hosts and business-oriented operators now list entire apartments, private rooms, and shared spaces across the city. Understanding what drives Airbnb prices is relevant not only for travelers planning affordable trips, but also for hosts and policymakers interested in how short-term rentals participate in local tourism and housing markets.

This project uses Airbnb listing data from Budapest to explore how the **total cost of a two-night stay for two guests** varies with listing characteristics, host attributes, and location-based features. Rather than making causal claims, the focus is on **prediction and interpretation**, examining how well different features help explain observed price variation.

---

## Research Question
**How well can we predict the total price of a two-night stay (for two guests) using listing, host, and location features, including whether the listing is business-oriented or privately hosted?**

---

## Data Description
The dataset contains Airbnb listings in Budapest with information on:

- **Price outcome**
  - `realSum`: total price for two guests over two nights (response variable)
- **Listing & host characteristics**
  - Business vs. private host indicator (`biz`)
  - Room type
  - Review and rating scores
- **Location & neighbourhood features**
  - Attraction and location indices
  - Distances to points of interest
- **Additional listing attributes**
  - Amenities and other structural features

---

## Methodology
The analysis follows a structured workflow:

1. **Exploratory Data Analysis (EDA)**  
   - Distribution of prices  
   - Relationships between price and key predictors  
   - Identification of potential nonlinearities and outliers  

2. **Predictive Modeling**  
   - Multiple regression-based models for predicting `realSum` including LASSO and Ordinary Least Squares
   - Model comparison using predictive performance metrics such as RMSE, R^2, MAE 
   - Interpretation of important predictors  

3. **Evaluation & Interpretation**  
   - Assessment of model fit and predictive accuracy  
   - Discussion of how listing type, ratings, and location relate to price variation  

The emphasis throughout is on **predictive performance and practical interpretation**, not causal inference.

---

## Key Takeaways
- Airbnb prices in Budapest reflect a combination of **listing characteristics**, **host type**, and **location factors**
- Business-oriented listings and neighbourhood accessibility play an important role in explaining price differences
- The results align with broader evidence that short-term rental markets behave similarly to housing and tourism markets at the city level

---

## Tools & Skills
- Statistical modeling
- Regression analysis  
- Exploratory data analysis and visualization  
- Model diagnostics and interpretation  
- R 
- Jupyter Notebook  

---

## Notes
This project was completed as part of a university statistics course.  
All analysis and interpretations are intended for educational and exploratory purposes.

---

## Repository Contents
- `report.ipynb` – Full analysis, modeling, and discussion  
- `README.md` – Project overview and context  

