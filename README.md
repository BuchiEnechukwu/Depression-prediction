# Depression Prediction Using BRFSS 2015 Survey Data

This project uses the 2015 Behavioral Risk Factor Surveillance System (BRFSS) dataset to explore factors associated with self-reported depression and to build a predictive model for identifying individuals at higher risk. The work was conducted as part of a personal learning project to strengthen my applied data science skills and demonstrate how health informatics can support population health.

## 📊 Dataset

- **Source**: [CDC BRFSS 2015 Public Use Data](https://www.cdc.gov/brfss/annual_data/annual_2015.html)
- **Sample Size**: Over 250,000 survey responses across U.S. states
- **Format**: Structured data (CSV)
- **Key Variables**: Mental health status, chronic disease, age, gender, alcohol/tobacco use, physical activity, healthcare access, and social support

## 🔍 Objective

- Identify the demographic and behavioural risk factors most associated with depression
- Build and evaluate a logistic regression model to predict the likelihood of self-reported depression
- Demonstrate documentation and coding best practices using Python

## 🧪 Methodology

- **Data Cleaning**: Null value treatment, type conversion, and variable selection
- **Exploratory Data Analysis (EDA)**: Descriptive statistics and univariate plots to examine data distributions
- **Feature Engineering**: Recoding of categorical variables, binary mapping, and removal of irrelevant columns
- **Modelling**: Logistic Regression with model evaluation using accuracy, precision, recall, and ROC-AUC
- **Tools Used**: Python (pandas, seaborn, matplotlib, scikit-learn)

## 📈 Key Insights

- Depression was more prevalent among younger adults, females, and those with chronic illness or limited physical activity
- Lack of healthcare access and unhealthy behaviours (e.g., heavy drinking) were also associated with increased depression risk
- The logistic regression model achieved reasonable predictive power, with an ROC AUC of approximately 0.74

## 📊 Visualisations

Charts and graphs include:
- Distribution of depression by age group and gender
- Correlation heatmaps of selected features
- ROC curve of the logistic regression model

## 🧠 Challenges and Learnings

- **Challenge**: Class imbalance between depressed and non-depressed groups required attention in modelling
- **Resolution**: Applied class weight balancing during model training to address this
- **Learning**: Working with real-world public health data demands careful feature selection and interpretation

## 🔮 Future Work

- Expand to multi-model comparison (e.g., random forest, gradient boosting)
- Apply feature selection techniques like LASSO or recursive elimination
- Extend the dataset to recent BRFSS years (2018–2022) for temporal comparison
- Include social determinants of health (e.g., housing, employment) if available

## 📁 Repository Structure

- `Depression_prediction.ipynb` — Full analysis notebook
- `data/` — Folder containing cleaned CSV file (not shared publicly due to size)
- `README.md` — This documentation

## 👩🏾‍💻 Author

- **Onyebuchi Enechukwu** 

This project is shared for demonstration and portfolio purposes under a permissive educational license.
