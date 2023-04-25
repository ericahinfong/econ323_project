# ECON323_FINAL-PROJECT

## This is the Final Project of ECON323, course that is associated with the Vancouver School of Economics at the University of British Columbia.

### The project was completed by 
- Eric Fang(BSc. Mathematics, Class of 2025)
- Mingrui Li and Qinhuai Xu(MEng. Electronic and Computer Engineering, Class of 2024)


### Background

The dataset we cited originally from Kaggle is intended to provide an analysis and prediction to the heart attack by using corresponding machine learning models. The drive we planned to investigate this special topic can be attributed to [Simmons' findings in 2021](https://libres.uncg.edu/ir/ecsu/f/Brandon_Simmons_Thesis-Final.pdf), in which he clarified due to the complexity and the variations of the increasing number of risk factors, modern researchers are depending on Machine Learning techniques to make the further breakthroughs on this challenging topic. Besides, according to [Garg, Khan and Sharma(2020)](https://iopscience.iop.org/article/10.1088/1757-899X/1022/1/012046), Heart Attack Prediction by using machine learning technique has started to play a significant role in the medical care and other corresponding research fields.

### Outline

* Exploratory Data Analysis (EDA)

> During the EDA stage, our goal was to identify the main factors that contribute to the occurrence of heart attacks in the dataset. We are particularly interested in examining the impact of age on heart disease, as it is commonly assumed that older individuals are more susceptible to developing heart disease compared to younger individuals.

* Classification and Prediction

> > During the latter part of our project, we aim to utilize multiple machine learning models to forecast the likelihood of a heart attack using our dataset, and analyze their respective performances. The input features we consider span from the first to the thirteenth columns. The output value we're trying to predict is situated in the fourteenth column, named 'output', where the value 0 denotes a lower likelihood of a heart attack, while 1 indicates a higher likelihood. We intend to apply a total of six different models: `Random Forest`, `Gradient Boosting`, `Support Vector Machine`, `K-Nearest Neighbors`, `Naive Bayes`, and `Multi-layer Perceptron of Neural Network`.


### Concluding Remarks

> EDA Stage

- During the EDA stage, our results successfully refuted a long-standing intuition that the older a person is, the higher the likelihood of experiencing a heart attack. However, based on our analysis of the data distribution, the probability of a heart attack actually decreases as age increases. 

- Furthermore, using the Naive Bayes Regression Model to analyze the relationship between Resting Blood Pressure and Cholesterol, as measured by the BMI Sensor, we can obtain a dataset related to heart attack research. Although the relationship between these two features is relevant to identifying heart disease, if one of these indicators is unusually high, it can also lead to other health issues, such as obesity.

> Machine Learning Stage

- Our dataset contains only 304 samples, which could constrain the effectiveness of machine learning. The limited amount of training data may result in poor performance of certain machine learning models. Consequently, different classifiers might be required to handle small and large datasets separately.

- The presence of outliers in our dataset can negatively impact the performance of certain classification algorithms like KNN, which are susceptible to being influenced by outlier data. To prevent such issues, it is important to enhance the quality of our data by verifying it and eliminating outliers. Ultimately, the accuracy and dependability of our predictions will depend on the quality of our data.

- The hyperparameter tuning is a method of enhancing the generalization capability of a model while preventing overfitting. When dealing with complex models like MLP with multiple layers, increasing the number of layers may not necessarily enhance prediction performance but may lead to overfitting. Conversely, simple models like KNN may fail to capture the relationship between X and Y, resulting in poor generalization. Each model has its own strengths and weaknesses, and there is no perfect machine learning model that can solve all prediction tasks. Therefore, choosing the appropriate model is a critical step in all machine learning tasks.
