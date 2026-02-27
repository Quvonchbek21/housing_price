**Tashkent Housing Price Prediction**

This project focuses on analyzing the real estate market in Tashkent and predicting house prices using various features. It covers the entire data science pipeline: data cleaning, Exploratory Data Analysis (EDA), and Machine Learning modeling.

**Key Insights from Analysis**

During the data exploration phase, the following key trends were identified:

**Floor Analysis:** The majority of sold properties are located on the 4th floor. Generally, houses on floors 1, 2, 3, and 4 see the highest sales volume.

**Building Types:** Most transactions occur in 4, 5, and 9-story buildings.

**Room Count:** 2-room and 3-room apartments are the most high-demand units in the market.

**District Trends:**

**Most Active Districts:** Chilonzor and Mirzo Ulugbek lead in terms of sales volume, followed by Yunusobod and Uchtepa.

**Premium Areas:** Mirabod and Yakkasaroy districts have a significantly higher average price per square meter compared to others.

**Most Affordable Area:** Bektemir district has the lowest average prices.

**Business Solutions & Recommendations**

Targeted Investment: Real estate investors should focus on Chilonzor and Mirzo Ulugbek for high liquidity (high sales volume), or Mirabod and Yakkasaroy for premium rental yields and high-value flipping.

Optimal Portfolio Construction: For developers, building 2-3 room apartments in 4-9 story buildings aligns best with current market demand in Tashkent.

Pricing Strategy: Real estate agencies can use this Random Forest model to provide instant, data-driven valuations to sellers, reducing the time a property stays on the market due to overpricing.

Market Expansion: Bektemir represents an entry-level market. Low prices per square meter suggest it could be a prime location for "Budget Housing" projects or long-term land-value appreciation.

**🛠 Technologies Used:**

Python (Pandas, NumPy)

Matplotlib & Seaborn (For data visualization)

Feature Engineering , Pipeline

Scikit-learn (For Machine Learning), RandomForest, metrics, Cross Validation(CV), RandomizedSearchCV

**Model & Performance**

The project utilizes the Random Forest Regressor algorithm to predict house prices. By considering multiple factors such as district, number of rooms, total area, and floor level, the model achieved high predictive accuracy.

MAE: 6790.603791809947

RMSE: 10555.403345225895

R2: 0.8805747431687113




