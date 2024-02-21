Health Insurance Prediction -ML Project

The majority of the countries finalize health insurance costs based on many factors such as age, number of people in families, etc. What should be the actual health insurance price for an individual or a family is an issue for many companies. Hence, one insurance company hired you as a data scientist to predict the health insurance cost for possible future customers. They have already collected samples required to perform all data analysis and machine learning tasks. Your task is to perform all data analysis steps and finally create a machine learning model which can predict the health insurance cost.
Variables in the dataset:
1.	age: age of the primary beneficiary
2.	sex: insurance contractor gender, female, male
3.	bmi: Body Mass Index, providing an understanding of body weights that are relatively high or low relative to height, objective index of body weight (kg/m²) using the ratio of height to weight, ideally 18.5 to 24.9
4.	5.	children: number of children covered by health insurance, number of dependents
6.	smoker: smoking or not
7.	region: the beneficiary’s residential area in the US, northeast, southeast, southwest, northwest.
8.	charges: individual medical costs billed by health insurance

Predicting health insurance costs accurately is important for several reasons. Firstly, it helps insurance companies to determine the premium that they should charge their customers. Secondly, it helps customers to make informed decisions about their health insurance plans. Thirdly, it helps policy makers to design policies that are more effective in providing affordable health care to the population


Some of the steps followed in EDA are:

1.Checking the data types, shape, and summary statistics of the data

2.Handling missing values and outliers

3.Plotting histograms, boxplots, and density plots to examine the distribution of each variable

4.Plotting scatterplots, correlation matrices, and heatmaps to explore the relationship between variables

5.Performing hypothesis testing and ANOVA to compare the means of different groups
Applying feature engineering and transformation techniques to improve the data quality and model performance.


Some of the essential patterns that are found in the given data using the EDA approach are:

The insurance cost is positively correlated with age, bmi, and smoking habit, and negatively correlated with the number of children
The insurance cost is higher for smokers than non-smokers, and for females than males
The insurance cost varies across different regions, with the highest in the southeast and the lowest in the southwest
The insurance cost is skewed to the right, with some extreme values above 50,000
The age and bmi variables are approximately normally distributed, while the number of children is discrete and has a mode of 0


Gradient boosting Regressor is one of the most effective techniques for building machine learning models for health insurance cost prediction.Here Gradient boosting Regressor model outperformed other regression models such as  Simple Linear Regression,Support Vector Regression, Random forest Regressor in predicting health insurance costs.
