\# Task 2: Data Cleaning, EDA, Linear Regression \& Dashboard



This directory contains the full pipeline for Task 2 of the CodeOrbit project.



\## 📋 Task Breakdown \& Summary Report



\### 1. Data Cleaning \& Exploration

\- \*\*Handling Missing \& Duplicate Data:\*\* Filtered out missing values (`dropna()`) and removed potential duplicate entries (`drop\_duplicates()`).

\- \*\*Statistics:\*\* Calculated mean, median, standard deviation, and value counts to verify data integrity.



\### 2. Exploratory Data Analysis (EDA)

\- \*\*Distribution:\*\* Examined score spread using histograms.

\- \*\*Insights:\*\* High correlation observed between total study hours and exam performance.



\### 3. Simple Linear Regression Model

\- \*\*Model:\*\* Built using `scikit-learn.linear\_model.LinearRegression`.

\- \*\*Accuracy \& Evaluation:\*\* The model achieved an $R^2$ score confirming strong predictive power for score targets based on study hours.



\### 4. Data Visualization Dashboard

\- \*\*Layout:\*\* Combined bar, line, regression scatter, and box plots into a unified 2x2 grid dashboard using `matplotlib` and `seaborn`.

