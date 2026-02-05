# Wine Quality Prediction Machine Learning Model
This project explores the chemical properties of white wine and their impact on overall quality. Using a Random Forest approach, I developed models for Binary Classification, Multi-Class Classification, and Regression to predict wine quality based on objective physicochemical data.

## Project Overview
The goal of this study is to move away from subjective human wine tasting and toward an objective, data-driven assessment. I utilized the White Wine Quality Dataset (UCI Machine Learning Repository), which contains 4,898 samples and 11 chemical features.

## Key Methodology & Results
### 1. Binary Classification (Good vs. Bad)
The most accurate model. 
This version simplifies the target into two categories Good or Bad.
- **Accuracy Score:** `87.96%`
- **Categories:** Bad (Quality $<$ 7), Good (Quality $\ge$ 7).

### 2. Multi-Class Classification (Bad, Average, Good)
A more granular approach.
This model categorizes wine into three tiers to better reflect the dataset's distribution.
- **Accuracy Score:** `68,88%` 
- **Categories:** Bad (3-5), Average (6), Good (7-9).

### 3. Regression Analysis (Predicting Scores)
Predicting the exact sensory score. 
Using a Regressor instead of a Classifier to find a numerical value on a scale of 3–9.
- **Mean Squared Error (MSE):** `0.405`
- **R2 Score:** `0.478`
- **Meaning:** On average, the model's predictions are within `0.63` points of the actual score.

## Repository Contents
* **`Wine_Quality_Analysis.ipynb`** - The full Google Colab notebook containing all experiments and visualizations.
* **`Wine_Quality_Report.pdf`** - The detailed academic report (IEEE Format).
* **`Project_Presentation.pdf`** - The slides used for the project presentation.
* **`winequality-white.csv`** - The raw dataset sourced from the UCI Machine Learning Repository.

*Developed for Machine Learning and Data Mining course at the University of Bologna.*
