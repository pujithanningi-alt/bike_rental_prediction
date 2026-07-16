# Bike Rental Demand Prediction 🚲

## Project Overview
[cite_start]With the increasing demand for sustainable and eco-friendly transportation, bike-sharing systems have gained significant popularity[cite: 109]. [cite_start]This project applies data analytics and machine learning techniques to predict daily bike rental demand based on environmental and seasonal factors[cite: 111]. [cite_start]Accurate demand prediction helps bike rental operators optimize bike availability, reduce operational costs, and improve overall customer satisfaction[cite: 177].

## Dataset
[cite_start]The dataset contains **731 daily records** and **16 attributes** capturing mobility behavior across different conditions[cite: 112, 120]. 
Key features include:
* [cite_start]**Environmental:** Temperature, feeling temperature (`atemp`), humidity, wind speed, and weather conditions[cite: 112].
* [cite_start]**Temporal/Seasonal:** Season, year, month, holidays, and working days[cite: 112].
* **Target Variable:** Total daily rental count (`cnt`).

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting)
* **Data Visualization:** Matplotlib, Seaborn

## Methodology
1.  [cite_start]**Exploratory Data Analysis (EDA):** Visualized relationships between weather/seasonal factors and rental counts[cite: 161]. 
2.  [cite_start]**Data Preprocessing:** Handled categorical variables and applied standard scaling to numerical attributes like temperature and humidity[cite: 160].
3.  [cite_start]**Model Training & Evaluation:** Trained 6 different regression models and evaluated them using R² Score, RMSE, and Mean Absolute Error (MAE)[cite: 163].

## Key Results & Insights
* [cite_start]**Environmental Impact:** Higher temperatures and favorable weather conditions significantly increase bike rentals, while adverse weather (rain/snow) leads to a noticeable decline[cite: 167, 168].
* [cite_start]**Temporal Trends:** Strong seasonal patterns exist, with peak demand during summer and fall[cite: 146]. [cite_start]Rentals are also consistently higher on working days[cite: 148].
* [cite_start]**Model Performance:** Advanced ensemble models captured non-linear relationships much better than baseline statistical methods[cite: 128, 176]. **Gradient Boosting** was the best-performing model, achieving an **R² Score of 0.8943** and the lowest prediction error.

## Team
* [cite_start]Pujith Kumar [cite: 104]
* [cite_start]Arun Kumar [cite: 105]
* [cite_start]Chandu [cite: 106]
* [cite_start]Jenisha [cite: 107]
