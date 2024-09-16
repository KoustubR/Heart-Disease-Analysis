# Heart Disease Analysis

## Overview
This project focuses on analyzing the factors contributing to heart disease using statistical and machine learning techniques. The analysis was performed using **R**, and the report was generated from an **RMarkdown** file. The dataset includes various health attributes, and the objective is to identify key risk factors and build a model to predict the likelihood of heart disease.

## Dataset
The dataset used in this analysis comes from the Centers for Disease Control and Prevention (CDC). It includes a variety of features such as age, BMI, physical and mental health, smoking habits, alcohol consumption, and history of stroke.

## Key Objectives
- **Exploratory Data Analysis (EDA)**: Visualize and explore the relationships between key variables such as age, BMI, and heart disease occurrence.
- **Model Building**: Develop and evaluate machine learning models like decision trees and logistic regression to predict heart disease.
- **Feature Importance**: Analyze which features contribute the most to predicting heart disease risk.

## Methods
- **Data Preprocessing**: The dataset was cleaned and prepared, handling missing values and standardizing features where necessary.
- **Modeling**: Decision Trees and Logistic Regression models were implemented and evaluated using metrics such as accuracy and AIC (Akaike Information Criterion).
- **Model Evaluation**: The performance of the models was assessed through misclassification error rates and visualized using decision trees.

## Tools Used
- **R**: The primary language used for data analysis and modeling.
- **Tidyverse**: For data manipulation and visualization.
- **Caret**: For machine learning model development.
- **RMarkdown**: For generating the final report.
- **KableExtra**: For creating formatted tables in the report.
- **ggplot2**: For creating data visualizations.

## Results
- The decision tree model had a misclassification error of 20.65%.
- Logistic regression analysis indicated that variables such as BMI, smoking, and stroke history were significant predictors of heart disease risk.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/heart-disease-analysis.git
    ```
2. Open the R project in RStudio.
3. Install the required R packages:
    ```r
    install.packages(c("tidyverse", "caret", "kableExtra", "ggplot2"))
    ```
4. Knit the **RMarkdown** file to generate the HTML report:
    ```r
    rmarkdown::render("Heart_Disease_Analysis.Rmd")
    ```

## Files
- **Heart_Disease_Analysis.Rmd**: The RMarkdown file containing the full analysis.
- **Heart_Disease_Analysis.html**: The knitted report in HTML format.
- **data/**: The folder containing the dataset used in this analysis.

## Conclusion
This project highlights the importance of health factors such as BMI, smoking, and stroke history in predicting heart disease. It demonstrates the power of decision trees and logistic regression in understanding the relationships between health attributes and disease risk.
