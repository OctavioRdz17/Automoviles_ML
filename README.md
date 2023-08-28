![Static Badge](https://img.shields.io/badge/Python-gray?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=seaborn)
![Static Badge](https://img.shields.io/badge/scikit--learn-gray?style=flat&logo=scikitlearn)
![linear_regretion](https://img.shields.io/badge/linear--regretion-gray?style=flat&logo=scikitlearn)
![svm](https://img.shields.io/badge/svm-gray?style=flat&logo=scikitlearn)


# Machine Learning Project: Market Research for Automotive Industry

This repository contains code and documentation for a Machine Learning project focused on performing market research for an automotive company. The project involves analyzing vehicle data to gain insights into market trends, building predictive models, and generating insights for pricing strategies and target audience segmentation.

## Project Overview

The main goal of this project is to assist an automotive company in entering a new market by providing data-driven insights and predictive models. The project involves the following steps:

1. **Problem Statement: During this stage, we reviewed the client's requirements to create the most suitable model that aligns with their needs.

2. **Exploratory Data Analysis (EDA):** Conducted exploratory analysis to gain insights into market trends, price distribution, and correlations between features.

3. **Data Preprocessing:** Cleaned and transformed the data, handled missing values, and encoded categorical variables.


4. **Model Building:SVM**
   Implemented a classification model to categorize vehicles into high-price and low-price categories based on the median price.
 

5. **Model Evaluation:SVM** Evaluated the models using confusion matrix for classification.

6. **Model Building:Linear Regression**
   Developed a regression model to predict vehicle prices using relevant features.

7. **Model Evaluation:Linear Regression** Evaluated the models using metrics such as Mean Squared Error (MSE) for regression 

8. **Conclusions**  Review of the results for both models

## Project Files

- `ML_cars.csv`: Dataset containing vehicle information and prices.
- `clean_model.csv`: Dataset after ETL.
- `MarketResearch_Automotive_ML.ipynb`: Jupyter Notebook containing code for data preprocessing, EDA, model implementation, and visualization.
- `README.md`: This document, providing an overview of the project.

## Environment Setup

1. Install required libraries using the following command:

   ```bash
   pip install pandas numpy scikit-learn seaborn matplotlib
   ```
## License
This project is licensed under the MIT License.