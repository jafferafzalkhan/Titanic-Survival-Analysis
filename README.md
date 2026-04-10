Titanic Survival Analysis
Overview

This project performs exploratory data analysis on the Titanic dataset to understand the factors influencing passenger survival. The analysis focuses on data preprocessing, feature engineering, and visualization to extract meaningful insights from real-world data.

Project Structure
titanic-analysis/
│
├── titanic.csv
├── titanic-eda-analysis.ipynb
└── README.md
Methodology

This project follows a structured exploratory data analysis workflow, including data cleaning, handling missing values, feature engineering, and visualization. The goal is to analyze patterns and relationships between variables that impact survival outcomes.

Steps Performed
Conducted initial data exploration to understand dataset structure and identify missing values
Performed data preprocessing by imputing missing values using median and mode
Removed irrelevant and non-informative features to improve data quality
Transformed categorical variables into meaningful and interpretable formats
Engineered a new feature (FamilySize) to capture the influence of family presence
Developed multiple visualizations to analyze distributions and relationships
Generated a correlation matrix to evaluate relationships among numerical features
Interpreted patterns and trends to derive data-driven insights
Exploratory Data Analysis (EDA)

The analysis includes multiple visualizations to study the distribution of features and their relationship with survival.

EDA Summary
Visualization Type	Feature(s) Used	Purpose	Key Insight
Count Plot	Survived	Analyze overall survival distribution	Majority of passengers did not survive
Count Plot	Sex vs Survived	Compare survival across gender	Females had significantly higher survival rates
Count Plot	Pclass vs Survived	Evaluate impact of passenger class	First-class passengers had higher survival probability
Histogram + KDE	Age	Understand age distribution	Most passengers were between 20–40 years
Box Plot	Fare vs Survived	Analyze fare distribution across survival groups	Higher fare passengers had better survival chances
Heatmap (Correlation)	Numerical Features	Identify relationships between numerical variables	Fare and class showed correlation with survival
Scatter Plot	Age vs Fare	Examine relationship between age, fare, and survival	Higher fare increased survival likelihood regardless of age
Visualization Insights

The survival distribution indicates that the majority of passengers did not survive. Gender-based analysis reveals that female passengers had a significantly higher survival rate, highlighting the impact of evacuation priorities. Passenger class plays a crucial role, with first-class passengers showing higher survival probabilities, indicating the influence of socio-economic status.

The age distribution shows that most passengers were young adults, while fare analysis suggests that higher-paying passengers had better survival chances. The correlation analysis further supports the relationship between fare, class, and survival. Additionally, the scatter plot demonstrates that fare has a stronger influence on survival compared to age.

Key Insights
Gender is a strong predictor of survival
First-class passengers had higher survival rates
Higher fare increased survival probability
Majority of passengers were young adults
Family size influenced survival patterns
Learning Outcomes
Developed a strong understanding of data preprocessing and cleaning techniques
Gained practical experience in handling missing values using statistical methods
Enhanced skills in feature engineering to improve analytical depth
Strengthened proficiency in data visualization using Matplotlib and Seaborn
Improved ability to analyze datasets and extract meaningful insights
Built the ability to communicate analytical findings in a structured and professional manner
