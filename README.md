### Predicting Players' Potential Ratings

This project develops a predictive model that forecasts players' potential ratings, helping users strategically build squads with optimal future prospects.

**Objective**

Accurately predicting potential ratings in FIFA’s Career Mode to help:

- **FIFA Gamers:** Identify top players to enhance team performance.
- **Soccer and Sports Fans:** Discover emerging talents who could become future superstars.

**Data Cleaning Summary**

|      | Rows  | Columns |
|------|-------|---------|
| **Before** | 17,760 | 18      |
| **After**  | 17,376 | 32      |

**Summary:** After cleaning, the dataset was refined to ensure better data quality, reducing the number of rows due to the removal of incomplete or irrelevant data and expanding the number of columns to include additional relevant features.

**Data Cleaning Process:**

- Removed irrelevant columns like 'Photo', 'Flag', and 'ID'.
- Converted categorical variables ('Preferred Foot', 'Work Rate', 'Body Type', 'Position') into dummy variables, increasing columns to 32.
- Eliminated rows with missing data, representing about 0.2% of the dataset.

**Models Used**

The predictive models used include Linear Regression, Ridge Regression, Lasso Regression, K-Nearest Neighbors (KNN), and Decision Trees, providing a comprehensive approach to forecast players’ potential ratings accurately.

**Model Performance**

<img width="261" alt="Screenshot 2024-09-16 at 6 46 46 PM" src="https://github.com/user-attachments/assets/191b2614-d4f4-4a82-ad48-3bfc86c61875">


Decision Trees outperformed all other models, suggesting that the relationship between predictors and the output is likely non-linear and potentially involves interactions between features.
