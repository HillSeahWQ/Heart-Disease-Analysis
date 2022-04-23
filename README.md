# Heart-Disease-Analysis Repository

# About
This is the project for SC1015(Introduction to Data Science and Artificial Intelligence).
Full code has been separated into the respective components for data analysis and prediction.
For the complete, comprehensive and robust analysis, wiew the source code files sequentially in the order stated below:
> 1. [Data Extraction and Cleaning](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)
> 2. [Exploratory Data Analysis]()
> 3. [Preprocessing (Encoding and Resampling)](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Preprocessing%20-%20Encoding%20and%20Resampling.ipynb)
> 4. [Machine Learning (Creation of classification models)](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Machine%20Learning.ipynb)


# Contributors
[@HillSeahWQ](https://github.com/HillSeahWQ)

[@Aloysius Ang](https://github.com/ConcealedSword)

[@Chia-Jer-Wen](https://github.com/Chia-Jer-Wen)

# Introduction: Problem Definition and Practical Motivation
Our interest in heart disease actually came from one of the other modules we are taking, which taught us that heart disease is one of the biggest killers in Singapore. This sparked our interest and led us to research further on the significance of heart disease. We found that heart disease is the second biggest killer in Singapore, with 4,031 deaths and accounting for 18.8% of total deaths in 2019 alone. Heart disease is also the biggest killer in the United States and Globally, according to the WHO. 

# Data Preparation and Cleaning
> [JupterNotebook #1: Data Extraction and Cleaning](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)

Data shaping and processing for more accurate analysis and exploration. 

# Exploratory Data Analysis
> [JupterNotebook #2: Exploratory Data Analysis]()

**Data Visualisation** - Using different plots and graphs to paint insightful pictures of the relationship between the response variable "HeartDisease" and the numerical and categorical predictor variables

**Univariate Analysis** - used to find pattern in the data to describe the variable. In univariate analysis, all variables are analysed independently. For each numeric variable, analyse it through looking at its mean, mode, median, quartiles and distribution. For each categorical variable, analyse it through looking at its number of categories, top, and cardinality.

**Bivariate Analysis** - used to find relationship between variables, specifically to determine the existence and the degree of statistical association . For instance, relationship between predictors and response are analysed. The purpose of this is to discover variables that have significant statistical association with response variable, so that it may be used in machine learning. For bivariate analysis between "HEARTDISEASE" and a categorical variable: the probability of having heart disease is analysed for different conditions in that categorical variable. For bivariate analysis between "HEARTDISEASE" and a numeric variable: the distribution of that numeric variable, for having and not having heart disease, are displayed in boxplot, stripplot, violin plot and kde plot. 

**Multivariate Analysis** - similar to Bivariate Analysis, Multivariate Analysis is also used to identify the statistical association between variables. The difference is to study multiple factors at once, and this particularly effective in minimizing bias. For multivariate between "HEARTDISEASE" and 2 categorical variables: probability of having heart disease is analysed for different combination of conditions in those 2 variables.

# Data Preprocessing
> [JupyterNotebook #3: Data Preprocessing Jupyter Notbook](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Preprocessing%20-%20Encoding%20and%20Resampling.ipynb)

**Encoding** - Used One Hot Encoder to encode non-ordinal categorical data. This is to allow the machine learning algorithms in Scikit-Learn that require numerical data to operate on the encoded categorical data directly.

**Resampling** - The response variable has severe imbalance of 10:1 for the classes of data. Since classification algorithms tend to have a low prediction accuracy toward the minority class because they assume that there is a balance between the classes, resampling is done. Upsampling and downsampling is performed and then later compared to see which results in a model with higher prediction accuracy.

# Machine Learning
> [JupyterNotebook #4: Machine Learning ](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Machine%20Learning.ipynb)

**Decision tree** - a supervised machine learning model to predice whether a patient has heart disease or not. Used for classification data such as the one used for our project.

**Random Forest** - Utilizes ensemble learning. A random forest contains multiple decision trees. The forest is trained through bagging or bootstrap aggregating. The random forest produces the outcome based on the predictions of the decision trees. It predicts by taking the average or mean of the output from various trees. Increasing the number of trees increases the precision of the outcome. Random forest is able to reduce the limitations of decision tree and reduces overfitting. However, we can still improve on this.

**Grid Search Cross-Validation** - used to find the optimal hyperparameters of a model which maximises the accuracy of the machine learning model. It can be used to prevent overfitting of the model, especially where the amount of data may be limited. In cross-validation, the data is partitioned into a fixed number of folds, and analysis is run on each fold. Then, the average of the overall error estimate is calculated. Cross-validation is a method used to assess the skill of machine learning models.

# Conclusion
Hospitals and doctors can predict whether a patient has or is going to have heart disease using the other health-related variables to increase early detection

_**Data-Driven Insights**_

> 1. **Increase early treatment** - Patients who detected heart disease early can go for early treatment and increase chances of recovering

> 2. **Lower medical costs** - With early treatment, operations and surgeries are less likely to be needed for the patient to recover

> 3. **Lower hospital demands** - Early treatment prevents heart disease and allows patients to recover on their own, reducing the need to stay at hospitals

> 4. **Increase survivability** - Early detection leads to early intervention which saves lives


# New Learnings
> 1. Encoding
> 2. Resampling
> 3. Random Forest
> 4. Grid Search (Cross-Validation)

# References

Brownlee, J. (2020, August 17). Ordinal and one-hot encodings for Categorical Data. Machine Learning Mastery. Retrieved April 22, 2022, from https://machinelearningmastery.com/one-hot-encoding-for-categorical-data/

Emily Cronkleton (30 January 2022), Medical News Today, The biggest causes of death in 2020, https://www.medicalnewstoday.com/articles/death-statistics-by-cause-2020#causes-of-death-in-the-us

Great Learning Team, (24 September 2020), What is Cross Validation in Machine learning? Types of Cross Validation, https://www.mygreatlearning.com/blog/cross-validation/

MOH (n.d), PRINCIPAL CAUSES OF DEATH, https://www.moh.gov.sg/resources-statistics/singapore-health-facts/principal-causes-of-death

Kibet, A. (2020, September 1). Classification framework for imbalanced data. Medium. Retrieved April 22, 2022, from https://towardsdatascience.com/classification-framework-for-imbalanced-data-9a7961354033 

Mayur Kulkarni, (7 September 2017), Decision Trees for Classification: A Machine Learning Algorithm, https://www.xoriant.com/blog/product-engineering/decision-trees-machine-learning-algorithm.html#:~:text=Introduction%20Decision%20Trees%20are%20a,according%20to%20a%20certain%20parameter.

Onesmus Mbaabu, (11 December 2020), Introduction to Random Forest in Machine Learning, https://www.section.io/engineering-education/introduction-to-random-forest-in-machine-learning/#:~:text=A%20random%20forest%20is%20a%20machine%20learning%20technique%20that's%20used,provide%20solutions%20to%20complex%20problems

Rohan Joseph, (30 December 2018), Grid Search for model tuning, https://towardsdatascience.com/grid-search-for-model-tuning-3319b259367e#:~:text=Grid%2Dsearch%20is%20used%20to,the%20most%20'accurate'%20predictions

WHO (11 June 2021), Cardiovascular diseases (CVDs), https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)#:~:text=Cardiovascular%20diseases%20(CVDs)%20are%20the,%2D%20and%20middle%2Dincome%20countries
