#  Zomato Restaurant Analysis (EDA Project)

##  Project Overview

Ever wondered what makes a restaurant successful? 🤔  
Is it pricing, popularity, or something else?

To explore this, I worked on a **Zomato restaurant dataset sourced from Kaggle** and performed **Exploratory Data Analysis (EDA)** to uncover key factors influencing restaurant performance and customer satisfaction.

---

##  About the Dataset

The dataset contains detailed information about restaurants, including:

- Restaurant ratings and votes  
- Price range  
- Cuisines offered  
- City and location  
- Features like photos, services, etc.  

At first glance, the dataset appeared rich, but it required significant preprocessing before analysis.

---

##  Data Cleaning & Preprocessing

The dataset had several issues that needed to be addressed:

- Missing values in multiple columns  
- Irrelevant columns (IDs, URLs, coordinates)  
- Inconsistent categorical data (e.g., cuisines)  
- Skewed distributions in votes and photos  

### Steps Taken:
- Removed unnecessary columns to reduce noise  
- Handled missing values appropriately  
- Cleaned and standardized categorical features  
- Created new features such as:
  - `cuisine_count` → number of cuisines offered  
  - `photo_bins` → grouped photo counts for better analysis  

---

##  Exploratory Data Analysis

The analysis was performed in three stages:

###  Univariate Analysis
- Studied distribution of ratings, votes, and price range  
- Identified skewness and outliers  

###  Bivariate Analysis
- Price Range vs Rating  
- Votes vs Rating  
- Cuisine vs Rating  
- Photo Count vs Rating  

###  Multivariate Analysis
- Combined impact of multiple features like price, votes, and cuisines  
- Correlation heatmap to identify relationships  

---

## Key Insights

- Most restaurant ratings lie between **3.0 and 4.5**, indicating generally good performance  
- **North Indian and Fast Food cuisines** dominate the market  
- Higher price does **not guarantee better ratings**  
- Votes and photo counts indicate popularity but have **limited impact on ratings**  
- Metro cities have the highest restaurant concentration  
- Correlation analysis shows that **no single factor strongly influences ratings**  

---

## Recommendations

### For Restaurant Owners:
- Focus on **food quality and service consistency**  
- Maintain strong **online presence (photos & engagement)**  
- Provide **value for money** instead of just premium pricing  
- Ensure consistency across outlets when scaling  

### For Platforms / Users:
- Do not rely only on price or popularity  
- Consider multiple factors like ratings, reviews, and features  
- Improve recommendation systems using **quality-based ranking**  

---

## Tools & Technologies Used

- **Python**  
- **Pandas & NumPy** → Data cleaning and manipulation  
- **Matplotlib & Seaborn** → Visualization  
- **Plotly** → Interactive visualizations  

---

## Conclusion

This project highlights that restaurant success depends on a **combination of multiple factors** rather than a single variable.  

While features like pricing, popularity, and amenities play a role, **customer satisfaction is primarily driven by quality, consistency, and overall experience**.

---

## Future Scope

- Incorporate **time-based data** to analyze trends  
- Perform **sentiment analysis on reviews**  
- Build predictive models for rating prediction  

---
