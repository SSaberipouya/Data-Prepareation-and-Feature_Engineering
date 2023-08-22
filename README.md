# Welcome to the Data Preparation Repository!
![Flowchart](introduction-image.jpg)
In this repository, you will discover a collection of valuable queries and curated papers designed to enhance your understanding of data preparation and data engineering techniques for machine learning projects. Whether you're a novice looking to grasp the fundamentals or an experienced practitioner aiming to refine your skills, this repository offers a wealth of resources to help you navigate the intricate world of data for successful machine-learning endeavors.

# 00. Dealing with Outliers

In statistics, an outlier refers to a data point that deviates significantly from the rest of the observations in a dataset. Outliers can arise due to various reasons, such as measurement errors, natural variability, or even genuine extreme values. It's important to handle outliers appropriately because they can distort the results of statistical analyses and impact the accuracy of predictive models.

## Understanding Outliers

Identifying outliers is a crucial step in data preprocessing and analysis. Outliers can have a disproportionate influence on statistical measures like the mean and standard deviation, causing these measures to be skewed. Moreover, they can affect the assumptions of many statistical techniques that assume a certain distribution of data. Failing to address outliers can lead to incorrect conclusions and predictions.

## Dealing with Outliers

While outliers can be problematic, they also provide valuable insights into data quality and potential issues. Therefore, it's important to carefully evaluate whether to remove an outlier from the dataset or not. Here are a few approaches to dealing with outliers:

1. **Understanding Data Sources:** Before labeling a data point as an outlier, it's essential to understand the context of the data and its sources. Sometimes, what appears to be an outlier might actually be a valid and important observation. Investigate the data collection process to ensure the accuracy of the measurement.

2. **Visualization:** Visualizing the data through scatter plots, histograms, or box plots can help in identifying outliers visually. A visual inspection might reveal patterns or explain the presence of certain extreme values.

3. **Statistical Methods:** Statistical methods can be employed to identify outliers quantitatively. Common methods include the use of z-scores or the interquartile range (IQR). Z-scores measure how many standard deviations a data point is away from the mean, while IQR helps detect outliers based on quartiles of the data.

4. **Domain Knowledge:** Subject-matter experts often possess domain knowledge that can aid in differentiating between genuine outliers and meaningful data points. Their input can be invaluable in making informed decisions about outlier handling.

## Useful Links

For further guidance on identifying and handling outliers, you can refer to the following resources:

1. [How to Identify Outliers in Your Data](https://machinelearningmastery.com/how-to-identify-outliers-in-your-data/)
2. [Using Statistics to Identify Outliers in Data](https://machinelearningmastery.com/how-to-use-statistics-to-identify-outliers-in-data/)
3. [Strategies for Dealing with Outliers](https://machinelearningmastery.com/how-to-use-statistics-to-identify-outliers-in-data/)

## Conclusion

Dealing with outliers is a critical aspect of data analysis and modeling. While they can disrupt statistical analyses, they also hold valuable information. The decision to remove outliers should be based on a thorough understanding of the data and its context, keeping in mind the goals of the analysis. Remember, each situation is unique, and careful consideration is necessary to make the right choices regarding outlier treatment.

# 01 Dealing with data Leakage 
![Data_leakage](DataLeakage.jpg)

Data leakage is a critical concern in the field of machine learning. It occurs when information from outside the training dataset influences the model's performance during training or evaluation, leading to misleadingly optimistic results. As a result, the model's ability to generalize to new, unseen data is compromised.

Are you ready to enhance your understanding of a critical aspect of machine learning? Dive into the world of data leakage with this comprehensive learning guide, designed to empower you with the knowledge to identify, prevent, and handle data leakage effectively.

1. **What is Data Leakage in Machine Learning?**
   [Link to Article](https://machinelearningmastery.com/data-leakage-machine-learning/)
   
   Discover the fundamental concepts of data leakage in machine learning. This article explores the various forms of data leakage, how they impact model performance, and real-world examples to illustrate the consequences.

2. **How to Avoid Data Leakage During Data Preparation?**
   [Link to Article](https://machinelearningmastery.com/data-preparation-without-data-leakage/)
   
   Effective data preparation is key to building robust and accurate machine-learning models. In this article, we explore strategies to ensure your data preprocessing procedures are free from data leakage, enabling your models to learn meaningful patterns from the right information.

3. **Data Leakage Explained**
   [Link to Kaggle Notebook](https://www.kaggle.com/alexisbcook/data-leakage)
   
   Dive into a practical example on Kaggle that illustrates data leakage. This notebook provides step-by-step insights into recognizing and handling data leakage situations, enhancing your ability to identify and rectify such issues in your own projects.

Stay tuned for updates to this repository as we continue to provide in-depth insights, tutorials, and resources to help you navigate the complex landscape of data leakage in machine learning. Whether you're a novice or an experienced practitioner, our aim is to empower you with the knowledge and skills needed to build reliable and accurate machine learning models.

Happy learning!

*Last updated: August 2023*

# 02 Dealing with missing data
# 03 Dealing with categorical data


# Usefull Links
1. Framework for Data Preparation Techniques in Machine Learning;
https://machinelearningmastery.com/framework-for-data-preparation-for-machine-learning/ & https://medium.com/manomano-tech/a-framework-for-feature-engineering-and-machine-learning-pipelines-ddb53867a420.

2. How to Perform Data Cleaning for Machine Learning with Python?
https://machinelearningmastery.com/basic-data-cleaning-for-machine-learning/ &
https://machinelearningmastery.com/data-cleaning-turn-messy-data-into-tidy-data/

3. How to Choose a Feature Selection Method For Machine Learning? 
https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/
https://www.linkedin.com/pulse/feature-engineering-techniques-machine-learning-sunil-kumar-cheruku/

5. Feature_selection for Regression Problems;
https://towardsdatascience.com/how-to-perform-feature-selection-for-regression-problems-c928e527bbfa &
https://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/

6. How to Use StandardScaler and MinMaxScaler Transforms in Python?
https://machinelearningmastery.com/standardscaler-and-minmaxscaler-transforms-in-python/

7. How to Perform Feature Selection with Categorical Data;
https://machinelearningmastery.com/feature-selection-with-categorical-data/

8. How to Perform Feature Selection With Numerical Input Data;
https://machinelearningmastery.com/feature-selection-with-numerical-input-data/

9. How to extract features from the encoded layer of an autoencoder? 
https://datascience.stackexchange.com/questions/64412/how-to-extract-features-from-the-encoded-layer-of-an-autoencoder &
https://medium.com/@venkatakrishna.jonnalagadda/sparse-stacked-and-variational-autoencoder-efe5bfe73b64

10. A Gentle Introduction to K-fold Cross-Validation
https://machinelearningmastery.com/k-fold-cross-validation/

11. A Gentle Introduction to Activation Regularization in Deep Learning
https://machinelearningmastery.com/activation-regularization-for-reducing-generalization-error-in-deep-learning-neural-networks/

12. How to Identify Overfitting Machine Learning Models in Scikit-Learn
https://machinelearningmastery.com/overfitting-machine-learning-models/

13. How to Perform Data Cleaning for Machine Learning with Python
https://machinelearningmastery.com/basic-data-cleaning-for-machine-learning/

14. Navigating The Hell of NaNs in Python
https://towardsdatascience.com/navigating-the-hell-of-nans-in-python-71b12558895b

15. Merge, join, concatenate in Python
https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html

16. Melt function in Python is used to unpivot a given DataFrame from a wide format to a long format.
https://pandas.pydata.org/docs/reference/api/pandas.melt.html & https://www.w3resource.com/pandas/dataframe/dataframe-melt.php

17. How to Map Data to a Normal Distribution\
[How to Transform Data to Better Fit The Normal Distribution](https://machinelearningmastery.com/how-to-transform-data-to-fit-the-normal-distribution/)\
[Map Data to a Normal Distribution](https://scikit-learn.org/stable/auto_examples/preprocessing/plot_map_data_to_normal.html)


