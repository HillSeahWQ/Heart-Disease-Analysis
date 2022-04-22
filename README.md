# Heart-Disease-Analysis Repository

# About
This is the project for SC1015(Introduction to Data Science and Artificial Intelligence).
Full code has been separated into the respective components for data analysis and prediction.
For the complete, comprehensive and robust analysis, wiew the source code files sequentially in the order stated below:
> 1. [Data Extraction and Cleaning](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)
> 2. Exploratory Data Analysis
> 3. [Preprocessing (Encoding and Resampling)](https://github.com/HillSeahWQ/Heart-Disease-Analysis/blob/main/Data%20Preprocessing%20-%20Encoding%20and%20Resampling.ipynb)
> 4. Machine Learning (Creation of classification models)


# Contributors
@HillSeahWQ - 
@Aloysius Ang -
@	Chia-Jer-Wen - 

# Introduction: Problem Definition and Practical Motivation
Our interest in heart disease actually came from one of the other modules we are taking, which taught us that heart disease is one of the biggest killers in Singapore. This sparked our interest and led us to research further on the significance of heart disease. We found that heart disease is the second biggest killer in Singapore, with 4,031 deaths and accounting for 18.8% of total deaths in 2019 alone. Heart disease is also the biggest killer in the United States and Globally, according to the WHO. 
# Models used
Decision tree: a supervised machine learning model to predice whether a patient has heart disease or not. Used for classification data such as the one used for our project.

Random Forest: utilizes ensemble learning A random forest contains multiple decision trees. The forest is trained through bagging or bootstrap aggregating. The random forest produces the outcome based on the predictions of the decision trees. It predicts by taking the average or mean of the output from various trees. Increasing the number of trees increases the precision of the outcome. Random forest is able to reduce the limitations of decision tree and reduces overfitting. However, we can still improve on this.

Cross validation: used to estimate the performance (or accuracy) of machine learning models. It can be used to prevent overfitting of the model, especially where the amount of data may be limited. In cross-validation, the data is partitioned into a fixed number of folds, and analysis is run on each fold. Then, the average of the overall error estimate is calculated. Cross-validation is a method used to assess the skill of machine learning models.

Grid Search: used to find the optimal hyperparameters of a model which maximises the accuracy of the model.
# Conclusion

# New Learnings

# References
Emily Cronkleton (30 January 2022), Medical News Today, The biggest causes of death in 2020, https://www.medicalnewstoday.com/articles/death-statistics-by-cause-2020#causes-of-death-in-the-us

Great Learning Team, (24 September 2020), What is Cross Validation in Machine learning? Types of Cross Validation, https://www.mygreatlearning.com/blog/cross-validation/

HOH (n.d), PRINCIPAL CAUSES OF DEATH, https://www.moh.gov.sg/resources-statistics/singapore-health-facts/principal-causes-of-death

Mayur Kulkarni, (7 September 2017), Decision Trees for Classification: A Machine Learning Algorithm, https://www.xoriant.com/blog/product-engineering/decision-trees-machine-learning-algorithm.html#:~:text=Introduction%20Decision%20Trees%20are%20a,according%20to%20a%20certain%20parameter.

Onesmus Mbaabu, (11 December 2020), Introduction to Random Forest in Machine Learning, https://www.section.io/engineering-education/introduction-to-random-forest-in-machine-learning/#:~:text=A%20random%20forest%20is%20a%20machine%20learning%20technique%20that's%20used,provide%20solutions%20to%20complex%20problems

Rohan Joseph, (30 December 2018), Grid Search for model tuning, https://towardsdatascience.com/grid-search-for-model-tuning-3319b259367e#:~:text=Grid%2Dsearch%20is%20used%20to,the%20most%20'accurate'%20predictions

WHO (11 June 2021), Cardiovascular diseases (CVDs), https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)#:~:text=Cardiovascular%20diseases%20(CVDs)%20are%20the,%2D%20and%20middle%2Dincome%20countries
