Welcome to my Data Science Portfolio. I am passionate about innovation and leveraging data analytics, data science, and machine learning to help businesses make informed decisions. Below are summaries of a few projects that I have recently completed. Click project links below to view full details including Python code, visualizations, and interpretations.

# [Project 1: EDA & Linear Regression](https://github.com/dandersonghub/EDA_Linear_Regression/blob/main/EDA_Linear_Regression.ipynb)
This project demonstrates the process of using Exploratory Data Analysis (EDA) to clean a dataset, understand the variables, and analyze the relationships between variables using simple linear regression and multiple linear regression. A survey dataset of population health-related data was explored in this project and linear regressions were modeled to determine the main features that predict systolic blood pressure (BP).

Descriptive statistics and correlation coefficients were calculated to review and compared the relationships between the target and 7 potential predictor variables. The variable 'AGE' was determined to be a statistically significant predictor of blood pressure with a moderate correlation of 0.46 and a p-value <0.001. Nineteen percent of the variation in systolic BP is explained by age. Variables for age, smoking status, and BMI were modeled to explain the variation in blood pressure. After controlling for BMI, the age and smoking status effects on blood pressure decreased. Twenty percent of the variation in BP can be explained by age, smoking status, and BMI.

### Linear Regression
![](/images/SLR_.png)




# [Project 2: Logistic Regression](https://github.com/dandersonghub/Logistic_Regression/blob/main/Logistic_Regression.ipynb)
A logistic regression classification model was built to predict cigarette smokers based on 20 health-related predictor variables. First, all missing values were imputed, normalized, and the dataset was split into training and testing datasets for modeling. Next, the model was fit to the datasets, class weights were adjusted to account for imbalanced data, and probability estimates were calculated. The confusion matrix was used to visually display the binary classifier's ability to correctly predict the classes (1=smoker, 0=nonsmoker). 

Out of all the people that the model predicted would be a smoker, only 60% were. Out of all the people who were true smokers, the model only predicted this outcome correctly for 67% of those people. The average accuracy for this logistic regression classifier is 68%. Based on the model accuracy and AUC (Area Under the Curve) (0.75) of this classifier, I recommend using an alternative classification model to obtain higher accuracy. The following techniques should be explored to find a better performing model; comparing other classification algorithms, oversampling/under sampling, decision threshold moving, and additional parameter tuning.

### Confusion Matrix
![](/images/conf.png)




# [Project 3: Comparing Classification Models](https://github.com/dandersonghub/Comparing-Classification-Models/blob/main/DA_Case_Study.ipynb)
This project compares and evaluates the performance of multiple binary classification models on their ability to predict the registration status of medical providers (registered or unregistered). The goal of this analysis is to understand the association between a provider's registration status and their demographic, geographic, communication, and behavioral characteristics. Four classification algorithms were built and trained to predict the provider registration status, and the performance of each model was evaluated based on six key accuracy metrics. After comparing all 4 models, the Gradient Boosting Machine (GBM) was found to be the best-performing model with the highest degree of accuracy (90%). The sanction count and location count were discovered to be the two most important features.The model can be further enhanced to produce better results by tuning hyperparameters, comparing different classifiers, or incorporating additional data.

### Model Performance: Comparison of 4 Classification Models
![](/images/class_compare1.png)



# [Project 4: Data Visualization](https://colab.research.google.com/github/dandersonghub/Data-Visualization/blob/main/Data_Visualization.ipynb)
This project utilizes Python to generate data visualizations on data extracted from the web. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to visualize trends, and patterns in data. The datasets explored in this project included immigration data from the United Nation's website and vacation rental data from the city of New Orleans' website. This project outlines the use of the following visualizations to explore data trends and insights, line plots, area plots, histograms, bar charts, pie charts, box plots, scatter plots, bubble plots, and maps. 

### Immigration Trends of Top 5 Countries
![](/images/Line_Plot2.png)




