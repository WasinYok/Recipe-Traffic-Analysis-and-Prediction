# Recipe-Traffic-Analysis-and-Prediction
This repository contains a comprehensive analysis and predictive modeling project focused on identifying and promoting high-traffic recipes. The notebook leverages data science and machine learning techniques to evaluate recipe performance, extract insights, and optimize content strategies for improving user engagement on a recipe platform.

# Features:
## Data Analysis: 
Exploratory data analysis (EDA) to identify patterns in recipe traffic and nutritional profiles.
## Predictive Modeling:
- Baseline model (Logistic Regression).
- Tuned model (Random Forest Classifier).
- Model evaluation metrics including accuracy, recall, and precision.
## Business Insights:
- Proportion of high-traffic recipes.
- Nutritional content analysis of high-traffic recipes.
- Contribution of categories to high-traffic recipes.
## Statistical Validation: 
Paired t-tests to confirm the significance of model improvements.
## Visualization: 
Interactive and static plots for data insights and model performance.
## Files:
- site_traffic.ipynb: Main notebook containing the analysis, modeling, and results.
- recipe_site_traffic_2212.csv: Dataset with recipe traffic data, nutritional values, and categories.
  - Data Explanation :
    - recipe : Numeric, unique identifier of recipe
    - calories : Numeric, number of calories
    - carbohydrate : Numeric, amount of carbohydrates in grams
    - sugar : Numeric, amount of sugar in grams
    - protein : Numeric, amount of protein in grams
    - category : Characterm type of recipe. Recipes are listed in one of ten possible groupings ("Lunch/Snacks", "Beverages", "Potato", "Vegetable", "Meat", "Chicken", "Pork", "Dessert", "Breakfast", "One Dish Meal").
    - servings : Numeric, number of servings for the recipe
    - high_traffic : Character, if the traffic to the site was high when this recipe was shown, this is marked with "High".
## Technologies:
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
Machine Learning (Scikit-learn)
Statistical Analysis (SciPy)
## Use Cases:
- Content Optimization: Identifying which categories and nutritional profiles drive user engagement.
- Performance Monitoring: Benchmarking and tracking key metrics for recipe success.
- Business Strategy: Allocating resources toward high-performing categories and improving underperforming ones.

