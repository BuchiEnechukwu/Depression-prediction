# Depression Prediction Using BRFSS 2015 Survey Data

This project explores the prevalence of depression across ten U.S. states using the 2015 Behavioral Risk Factor Surveillance System (BRFSS) dataset. It applies data cleaning, exploratory analysis, and logistic regression to identify key predictors of depression.

## Project Objectives

1. Predict depression prevalence based on sociodemographic, socioeconomic, and behavioural factors, comorbidities.
2. Identify key risk factors associated with depression.
3. Support awareness and early intervention efforts through open-access analysis.

## Tools and Libraries
•	pandas for data cleaning and manipulation
•	seaborn, matplotlib for exploratory data visualisation
•	scikit-learn for logistic regression modelling and evaluation
•	Jupyter Notebook for interactive development

## Dataset

- **Source**: [CDC BRFSS 2015 Public Use Data](https://www.cdc.gov/brfss/annual_data/annual_2015.html)
- **Sample Size**: Over 440,000 survey responses across U.S. states
- **Format**: Structured data (CSV)
- **Key Variables**: Mental health status, chronic disease, age, gender, education, income, alcohol/tobacco use, physical activity, BMI

## Methodology

- **Data Cleaning**: Null value treatment, type conversion, and variable selection
- **Exploratory Data Analysis (EDA)**: Descriptive statistics and univariate plots to examine data distributions. Correlation analysis
- **Feature Engineering**: Recoding of categorical variables, binary mapping, and removal of irrelevant columns
- **Modelling**: Logistic Regression with model evaluation using accuracy, precision, recall, and ROC-AUC
- **Tools Used**: Python (pandas, seaborn, matplotlib, scikit-learn)

## Key Insights

- Depression was more prevalent among younger adults, females, and those with chronic illness or limited physical activity
- Lack of healthcare access and unhealthy behaviours (e.g., heavy drinking) were also associated with increased depression risk
- The logistic regression model achieved reasonable predictive power, with an ROC AUC of approximately 0.78


## Challenges and Learnings

- **Challenge**: Class imbalance between depressed and non-depressed groups required attention in modelling
- **Resolution**: Applied class weight balancing during model training to address this
- **Learning**: Working with real-world public health data demands careful feature selection and interpretation

## Future Work

- Expand to multi-model comparison (e.g., random forest, gradient boosting)
- Apply feature selection techniques like LASSO or recursive elimination
- Extend the dataset to recent BRFSS years (2018–2022) for temporal comparison
- Include social determinants of health (e.g., housing, employment) if available

## Repository Structure

- `Depression_prediction.ipynb` — Full analysis notebook
- `data/` — Folder containing cleaned CSV file (not shared publicly due to size)
- `README.md` — This documentation

## Author

- **Onyebuchi Enechukwu** 

## Author Notes

This project was developed as part of my independent data science work to explore public health topics using open datasets. Feedback and suggestions are welcome.
