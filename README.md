# employee-churn
Employee Attrition Analysis

The purpose of this case study was to determine the factors which impact employee churn, then to use those factors and predict the likelihood of an employee leaving the company. 

The features involved with employment, and tracked by the traditional human resources department, were used in this analysis; things like whether or not the employee worked overtime, the duration of their commute, their monthly income, their age, how long they have worked for this company, the total length of their work history, their education level, as well as a few others not mentioned here.

The results revealed that, while there were no perfectly correlated features, there are strong positive correlations between the following factors. The top 10 pairs are listed in descending order of impact:

 1. Job level and monthly income.
 2. Job level and total working years.
 3. Percentage of salary increase and performance.
 4. Monthly income and total working years.
 5. Number of years at the company, and the number of years with the current manager.
 6. Number of years at the company, and the number of years in the current role.
 7. Number of years with the current manager, and the number of years in the current role.
 8. The employee's age and the length of their work history.
 9. The duration of their work history, and the number of years with the company.
 10. The number of years at the company, and the number of years since their last promotion.

Random forest analysis suggests that overtime is the leading cause of attrition. 
The full analysis is viewable within the Jupyter Notebook.

### About the data.

The data is the IBM HR Analytics Employee Attrition & Performance dataset. This is a fictional dataset made by IBM Data Scientists and has 1470 rows across 35 columns.

The full dataset is available [here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

### Tools Used.

+ Python
+ Sci-kit Learn Random Forest Classifier
+ Seaborn Heatmap
+ Kaggle
+ Jupyter Notebook
