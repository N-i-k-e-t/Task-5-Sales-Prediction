# Sales Prediction using Advertising Data

## Internship Details

* **Company:** The Black Pearls
* **Internship Period:** June 15, 2024 - July 15, 2024 

## Introduction

This project aims to predict sales based on advertising spending across different media (TV, radio, newspaper). By building a machine learning model, the goal is to understand the relationship between advertising expenditure and sales performance.

**Business Context:** Accurately predicting sales based on advertising investments is crucial for optimizing marketing budgets and maximizing return on investment.  This project demonstrates the ability to apply predictive modeling to real-world business challenges faced by companies like The Black Pearls.

## Dataset and Features

* **Data Source:**  This project utilizes the Advertising dataset. [Provide a link if the dataset is publicly available; otherwise, briefly describe the source]. 
* **Features:**
    * **TV:** Advertising spending on TV (in thousands of dollars)
    * **Radio:** Advertising spending on radio (in thousands of dollars)
    * **Newspaper:** Advertising spending on newspapers (in thousands of dollars)
* **Target Variable:**
    * **Sales:** Sales of a product (in thousands of units)
* **Data Preprocessing:** 
    * Feature scaling was applied to standardize the features (TV, radio, newspaper) using StandardScaler. This ensures that features with larger scales do not disproportionately influence the model.

## Methodology

* **Approach:** This project employs a supervised learning approach, specifically regression, as the target variable (sales) is continuous.
* **Algorithms:** The following regression algorithms were explored:
    * Linear Regression
    * Decision Tree Regression
    * Random Forest Regression
    * Support Vector Regression (SVR)
    * K-Nearest Neighbors Regression
    * XGBoost Regression
* **Model Selection:** Models were evaluated using Mean Squared Error (MSE) and R-squared. The model with the lowest MSE and highest R-squared on the test set was considered the best performing.

## Results and Evaluation

* **Key Findings:** The project revealed that advertising spending on TV and radio exhibited a strong positive correlation with sales, while newspaper advertising had a weaker correlation. 
* **Performance Metrics:** 
    * **Linear Regression:** MSE = 3.174, R-squared = 0.899
    * **Decision Tree:** MSE = 1.474, R-squared = 0.953
    * **Random Forest:** MSE = 0.516, R-squared = 0.984
    * **Support Vector Machine:** MSE = 2.774, R-squared = 0.912
    * **K-Nearest Neighbors:** MSE = 2.011, R-squared = 0.936
    * **XGBoost:** MSE = 0.869, R-squared = 0.972
* **Visualizations:** [Add a sentence about the types of visualizations created and either include them directly in the README or provide a link to a separate folder containing them].

## Conclusion

* **Summary:** This project successfully built and compared multiple regression models to predict sales based on advertising data. The Random Forest model emerged as the most accurate, achieving an R-squared of 0.984, indicating that it explains approximately 98.4% of the variance in sales.
* **Business Implications:** The insights derived from this project can assist The Black Pearls in making more data-driven decisions regarding advertising budget allocation. The models suggest a strong positive relationship between TV and radio advertising spending and sales. By optimizing investments in these media, the company can potentially maximize its marketing ROI. 
* **Future Work:**
    * **Feature Engineering:** Explore additional features that might influence sales, such as seasonality, competitor analysis, and product promotions.
    * **Hyperparameter Tuning:** Fine-tune the hyperparameters of the best-performing models to further enhance their predictive accuracy.
    * **Model Deployment:** Develop a system to deploy the model for real-time sales predictions on new advertising data.

## Technical Information

* **Installation:**
    * Ensure you have Python installed.
    * Install the required libraries using pip:  `pip install pandas matplotlib scikit-learn xgboost` 
* **How to Run:** 
    * Download the 'Advertising.csv' dataset and place it in your project directory.
    * Update the path to the dataset in the code if necessary.
    * Execute the Python script.

Let me know if you have any other questions.
