🏡 **Real Estate Price Analysis and Forecasting in Canadian Cities**
This project analyzes and forecasts real estate prices across 45 Canadian cities using various machine learning algorithms. Our goal is to identify the most affordable housing markets by examining how features like the number of bedrooms, bathrooms, and median family income influence home values.

📊 **Dataset**
We used the Canadian House Prices for Top Cities dataset from Kaggle [1], which includes detailed property listings and socioeconomic data.

🔍 **Project Scope**
**Exploratory Data Analysis (EDA):**
Performed descriptive analysis and data wrangling to clean and refine the dataset.

**Feature Engineering:**
Focused on variables such as price, number of bedrooms, bathrooms, median income, population, latitude, and longitude.

**Clustering & Linear Regression:**
Used to uncover market trends and city groupings based on affordability and demographics.

🤖 **Machine Learning Models**
Four machine learning models were trained and evaluated:
- Linear Regression
- Decision Tree
- Gradient Boosting
- Random Forest

Each model was fine-tuned using hyperparameters (e.g., max_depth) for optimal accuracy. Performance was assessed using five evaluation metrics:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- F1 Score
- Matthews Correlation Coefficient (MCC)

✅ ****Results**
The Random Forest model outperformed all others, followed by Gradient Boosting, Decision Tree, and finally Linear Regression.

Based on the predictions, the most affordable cities in the coming years are projected to be:

🟢 Red Deer
🟢 Edmonton
🟢 Saskatoon

The least affordable cities are projected to be:

🔴 White Rock
🔴 Vancouver
🔴 Burnaby

This suggests that Alberta and Saskatchewan may continue to offer affordable housing options, while British Columbia cities remain among the most expensive.

**References**

[1] J. Larcher, Canadian House Prices for Top Cities, Kaggle, 2023. [Online]. Available: https://www.kaggle.com/datasets/jeremylarcher/canadian-house-prices-for-top-cities. [Accessed: Mar. 26, 2025]. 
