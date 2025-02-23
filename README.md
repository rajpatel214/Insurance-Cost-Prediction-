# Insurance-Cost-Prediction-

**Overview**
This project focuses on predicting medical insurance costs based on a person’s details like age, gender, BMI, smoking habits, and region. The goal is to understand which factors affect insurance charges and build a machine learning model that can estimate costs for new customers.

**Understanding the Data (Exploratory Data Analysis – EDA) :**

**1. Age Distribution**
Most people in the dataset are in their 20s.
This means the dataset has more young individuals compared to older ones.

**2. Gender Count**
The dataset includes both males and females.
The number of males and females is almost equal, so gender won’t heavily impact predictions.

**3. Smoking and Age**
A separate analysis showed that smokers are present across all age groups.
Since smoking is a major health risk, it can significantly increase insurance charges.

**4. Region-wise Distribution**
People belong to different regions, and the dataset shows the number of individuals from each region.
This helps in understanding whether region plays a role in determining insurance costs.

**5. BMI and Age Relationship**
BMI (Body Mass Index) tells whether a person is underweight, normal weight, overweight, or obese.
The analysis showed that BMI varies with age, and higher BMI might lead to higher charges.

**6. How BMI Affects Insurance Charges**
A deeper analysis showed that people with higher BMI tend to have higher insurance costs.
This is because higher BMI can indicate obesity-related health risks, leading to increased medical expenses.

**7. How Gender Affects Insurance Charges**
On average, males tend to have slightly higher insurance costs than females.
However, gender alone is not the biggest factor in determining costs.


**Linear Regression –** A simple model that works well for basic data but doesn’t handle complex patterns well.
**Decision Tree Regressor –** A tree-based model that captures patterns better but can sometimes overfit (memorize data instead of generalizing).
**Random Forest Regressor –** An improved version of Decision Tree, combining multiple trees to increase accuracy and reduce errors.
**K-Nearest Neighbors (KNN) –** Works well for some cases but struggles when there are too many features.
**Support Vector Regressor (SVR) –** A model that works well in specific situations but was not the best choice here.


**Linear Regression: 74% accuracy,
Decision Tree: 83% accuracy,
Random Forest: 86% accuracy,
Gradient Boosting: 81% accuracy**

