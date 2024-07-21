# Titanic_survival

 This project is completed by taking help from the course:"Complete machine learning and data science program" offered by geeksforgeeks.
 <p align="center">
   <img src="https://images.nationalgeographic.org/image/upload/t_edhub_resource_key_image/v1638882458/EducationHub/photos/titanic-sinking.jpg">
 </p>
 
 # Description:
 
The sinking of the **RMS Titanic** is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, **killing 1502 out of 2224 passengers and crew.** This sensational tragedy shocked the international community and led to better safety regulations for ships.
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we target to complete the analysis of what sorts of people were likely to survive.

By performing EDA on the Titanic passenger data, we can gain a better understanding of the characteristics of the passengers and how they may have affected their chances of survival. This information can then be used to inform the development of a machine learning model that can accurately predict which passengers survived the sinking. 

In this project we will be plotting a correlation matrix to find out the relationship between different features. 

The main libraries that we will be using for EDA is NumPy, Seaborn, Matplotlib

 

# ML Model

Pre-processing the data before applying machine learning algorithms is an important step that can help improve the performance of your model. Some additional details about common pre-processing techniques include:

- Handling missing values: NULL or missing values in your dataset can cause problems when training machine learning models, as many algorithms are unable to handle NULL values. There are several approaches you can take to deal with missing values, such as dropping rows or columns with missing values, imputing missing values with the mean or median of the feature, or predicting missing values using a separate model. Which approach you choose will depend on the specific characteristics of your dataset and the goals of your analysis.
- Feature selection: Identifying the most relevant features in your dataset and selecting a subset to use in your model can help reduce the complexity of the model and improve its performance. There are several approaches you can take to select features, such as using statistical tests to identify the most important features, using domain knowledge to identify relevant features, or using machine learning algorithms that have built-in feature selection methods.
- Feature engineering: Creating new features from existing features in your dataset can help capture additional information or trends in the data that might not be apparent in the raw features. This can be done through techniques such as combining or transforming existing features, or using domain knowledge to create features based on your understanding of the problem.
After Preprocessing the data, we can move on to splitting it into a training set and a test set. This is an important step because it allows us to evaluate the performance of your model on unseen data, which is a more realistic representation of how the model will perform in practice.

Once the data is ready, we can then apply a variety of machine learning algorithms to it and compare their performance. There are many different algorithms to choose from, and the specific algorithm that works best will depend on the nature of the data and the prediction task. Some common algorithms for the Titanic Survival Problem include:

- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines
- K-Nearest Neighbors
After training and evaluating each algorithm, we can then compare their performance to see which one provides the most accurate predictions. To do this, we can use metrics like accuracy. These metrics will give you an idea of how well the model is able to correctly predict the survival of passengers. 
