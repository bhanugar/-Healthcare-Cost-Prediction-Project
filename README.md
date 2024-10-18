Healthcare Cost Prediction Project
==================================

Project Overview
----------------

This project focuses on analyzing a healthcare cost dataset from a Health Management Organization (HMO) to identify key factors driving high healthcare costs and to predict individuals likely to incur high expenses. The project includes data cleaning, exploratory analysis, and the development of predictive models to provide actionable insights to the HMO.

Dataset
-------

The dataset contains 7582 records with 14 variables, including demographic and lifestyle information, such as:

*   **Age**
    
*   **Location**
    
*   **Exercise habits**
    
*   **Smoking status**
    
*   **BMI**
    
*   **Yearly physical**
    
*   **Hypertension**
    
*   **Gender**
    
*   **Education level**
    
*   **Marital status**
    
*   **Number of children**
    
*   **Total healthcare cost**
    

Project Goals
-------------

1.  Predict individuals who will have high healthcare costs in the next year.
    
2.  Provide actionable insights to the HMO to reduce overall healthcare costs.
    

Exploratory Data Analysis (EDA)
-------------------------------

*   **Data Cleaning**: Addressed missing values in bmi and hypertension using interpolation.
    
*   **Visualizations**: Histograms, scatter plots, and box plots to explore relationships between healthcare costs and factors like BMI, smoking, exercise, age, and hypertension.
    

Predictive Models
-----------------

1.  **Linear Regression Model**: Significant model with an R-squared value of 56.97%.
    
2.  **Support Vector Machine (SVM)**: Achieved high accuracy and sensitivity in predicting high healthcare costs.
    
3.  **Treebag Model**: Another model tested for predicting costs.
    

Key Insights
------------

*   **BMI vs Cost**: Higher BMI correlates with higher healthcare costs, suggesting the need for weight management programs.
    
*   **Smoking vs Cost**: Smokers have significantly higher healthcare expenses.
    
*   **Exercise vs Cost**: Regular exercise reduces healthcare costs.
    
*   **Age vs Cost**: Older individuals have higher healthcare expenses.
    

Recommendations
---------------

1.  **Fitness Programs**: HMO should encourage exercise and smoking cessation workshops.
    
2.  **Weight Management**: Incentivize customers to reduce BMI to lower healthcare costs.
    
3.  **Hypertension Awareness**: Monitor and guide customers with early-stage hypertension.
    

Conclusion
----------

This project provided predictive models and valuable insights to help HMOs reduce healthcare costs by targeting key factors such as BMI, smoking, exercise, and hypertension.

Tools Used
----------

*   **R**: Data analysis and model building.
    
*   **Tidyverse**: Data wrangling and visualization.
    
*   **imputeTS**: Handling missing data.
