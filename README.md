# 📊 Forecasting Sales — Great Britain Dishwasher Market

This project focuses on predicting monthly dishwasher unit sales in the UK market using machine learning techniques.(Jupyter Notebooks are provided.) By combining market trend analysis with multiple forecasting models, this project helps uncover patterns across brands, pricing, seasonality, offering valuable insights.

**Project Objective: Forecasting Units Sold without Taking "Selling Shops" as an Input**

Inputs:
["Size", "Brand", "Noise Level DB", "Energy Class", "Season", "Water Protect", "Construction Type", "Half Load", "Integration", "Inverter Motor", "Material", "NO OF Placesets", "NO. OF Progr.", "Program Autom.", "Remaining Time", "Sliding Hinges", "Smart Connect", "Third Rack", "Color" "Price"]

**Project Structure**

Dataset Exploration:
A closer look into the dishwasher sales dataset, including:

Product model and brand information, Historical sales volume, Pricing trends and promotional flags, Seasonal patterns and selling platforms

Data Preprocessing:
Steps include:

Handling missing values and outliers, Normalizing and encoding categorical variables, Temporal feature extraction from date fields

Market Analysis:
Performed exploratory data analysis (EDA) to understand:

Top-selling brands and models, Price vs. unit relationships, Monthly demand shifts and trends

**Applied k-means Clustering**

Modeling & Forecasting:
Tested multiple machine learning models:

✅ Random Forest – with feature importance insights

✅ RandomizedSearchCV for Hyperparameter Tuning

✅ MLP(Multi Layer Perceptron) Model

Model Optimization:
Performed hyperparameter tuning using cross-validation Selected models based on evaluation metrics including:

-Mean Absolute Error (MAE) -Root Mean Squared Error (RMSE) -R² Score
