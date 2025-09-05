Titanic Survival Analysis 🚢
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover meaningful insights about passenger survival patterns. The analysis includes statistical summaries, data cleaning, visualization of distributions, correlations, and detection of anomalies.

🛠 Tools & Libraries

Python (3.x)

Pandas → Data manipulation

NumPy → Numerical operations

Matplotlib & Seaborn → Data visualization

📂 Project Files

EDA.ipynb → Jupyter Notebook containing all the analysis and visualizations.

Titanic-Dataset.csv → Dataset used for the analysis.

README.md → Documentation of the project.

🔎 Steps Performed

Data Understanding

Explored structure using .info(), .describe(), .value_counts(), .isnull().sum().

Missing Data Analysis

Visualized missing values with heatmaps.

Suggested strategies for handling missing Age and Cabin values.

Univariate Analysis

Histograms for numerical features.

Boxplots for outlier detection.

Countplots for categorical distributions.

Bivariate & Multivariate Analysis

Correlation heatmap to identify relationships between variables.

Pairplots for numerical comparisons.

Analyzed survival rates by gender and passenger class.

Grouping & Aggregation

Grouped data by passenger class and sex to find patterns.

Outlier & Skewness Detection

Checked skewness of numerical features.

Suggested log transformation for highly skewed values like Fare.

📊 Key Insights

Gender Effect: Females had significantly higher survival rates than males.

Passenger Class Effect: Higher classes (1st class) had better survival chances than lower classes.

Fare Influence: Passengers who paid higher fares were more likely to survive.

Age Factor: Younger passengers, especially children, had higher survival chances.

Missing Data: Age and Cabin had the most missing values, requiring imputation or removal.

🚀 Deliverables

Jupyter Notebook → EDA.ipynb

Dataset → Titanic-Dataset.csv

README Documentation → README.md

📖 Learning Outcomes

Learned how to break down raw data into interpretable insights.

Gained hands-on experience in visualizing distributions and relationships.

Understood handling of missing values, outliers, and skewed data.

Improved business storytelling using data insights.
