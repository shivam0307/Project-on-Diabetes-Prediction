# Diabetes Prediction using Machine Learning Techniques

<img src="https://user-images.githubusercontent.com/107324616/179756553-012c7e06-3ef5-46fd-8a09-2aa180ebd153.png" width="724" height="434">

This Project is an Real Life Application of Machine Learning Techniques in Medical Field. The main objective is to predict better predictions of Diabetic Result based on Patients' Body following attributes:
1. Pregnancies (number of times pregnant)
2. Oral glucose tolerance test - OGTT (two hour plasma glucose concentration after 75g anhydrous glucose in mg/dl)
3. Blood Pressure (Diastolic Blood Pressure in mmHg)
4. Skin Thickness (Triceps skin fold thickness in mm)
5. Insulin (2 h serum insulin in mu U/ml)
6. BMI (Body Mass Index in kg/m2)
7. Age (years)
8. Pedigree Diabetes Function ('function that represents how likely they are to get the disease by extrapolating from their ancestor’s history')

## What is the need for this Analysis?

Diabetes is a serious health disease due to the presence of high glucose levels in the human body. If diabetes is untreated, it can cause other critical health issues in person. 

### Report by WHO (10 Nov 2021)
- The number of people with diabetes rose from 108 million in 1980 to 422 million in 2014. Prevalence has been rising more rapidly in low- and middle-income countries than in high-income countries.
- Diabetes is a major cause of blindness, kidney failure, heart attacks, stroke and lower limb amputation.
- Between 2000 and 2016, there was a 5% increase in premature mortality from diabetes.
- In 2019, diabetes was the ninth leading cause of death with an estimated 1.5 million deaths directly caused by diabetes.
- A healthy diet, regular physical activity, maintaining a normal body weight and avoiding tobacco use are ways to prevent or delay the onset of type 2 diabetes.

Diabetes can be treated and its consequences avoided or delayed with diet, physical activity, medication and regular screening and treatment for complications. The main aim of the project is to predict diabetes by analyzing different human body attributes. The proposed methodology adopts two types of machine learning algorithms for diabetes prediction:
1. Logistics Regression
2. Supporting Vector Machine

This project discusses important attributes responsible for inducing diabetes. It also computes the correlation between them. The project also compares the performance of different classifiers based on different evaluation metrics.

## About the Dataset

#### Dataset used: Pima Indians Diabetes Dataset, National Institute of Diabetes and Digestive and Kidney Diseases

I've explored, analyzed the Pima Indians Diabetes Dataset, and applied ML Techniques.

The Pima Indian Diabetes Dataset, originally from the National Institute of Diabetes and Digestive and Kidney Diseases, contains information of 768 women from a population near Phoenix, Arizona, USA. The outcome tested was Diabetes, 258 tested positive and 500 tested negative. Therefore, there is one target (dependent) variable and the 8 attributes (TYNECKI, 2018): pregnancies, OGTT(Oral Glucose Tolerance Test), blood pressure, skin thickness, insulin, BMI(Body Mass Index), age, pedigree diabetes function. The Pima population has been under study by the National Institute of Diabetes and Digestive and Kidney Diseases at intervals of 2 years since 1965. As epidemiological evidence indicates that T2DM results from interaction of genetic and environmental factors, the Pima Indians Diabetes Dataset includes information about attributes that could and should be related to the onset of diabetes and its future complications.

But Before all these, we should have basic understnding of Machine Learning & Deep Learning Concepts!

## What is Machine Learning?

Machine Learning is the field of study that gives computers the capability to learn without being explicitly programmed. ML is one of the most exciting technologies that one would have ever come across. As it is evident from the name, it gives the computer that makes it more similar to humans: The ability to learn. Machine learning is actively being used today, perhaps in many more places than one would expect.

**Supervised learning** is when the model is getting trained on a labelled dataset. A labelled dataset is one that has both input and output parameters. In this type of learning both training and validation, datasets are labelled.

**Unsupervised learning** is the training of a machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance. Here the task of the machine is to group unsorted information according to similarities, patterns, and differences without any prior training of data.

![image](https://user-images.githubusercontent.com/107324616/176885992-928d2320-50ae-4fa6-921b-509ac938ab8e.png)

## Logistic Regression

Logistic regression is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for a given set of features(or inputs), X.

Contrary to popular belief, logistic regression IS a regression model. The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function

#### Sigmoid Function: g(z) = $\frac{1}{1 + e^-z}\$

<img src="https://user-images.githubusercontent.com/107324616/179775279-b2ca154b-9c00-4464-87f2-8c7d1b1a4390.png" width="400" height="400">

## Supporting Vector Machine

Support Vector Machine (SVM) is a supervised machine learning algorithm that can be used for both classification or regression challenges. However,  it is mostly used in classification problems. In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is a number of features you have) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well.

To separate the two classes of data points, there are many possible hyperplanes that could be chosen. Our objective is to find a plane that has the maximum margin, i.e the maximum distance between data points of both classes. Maximizing the margin distance provides some reinforcement so that future data points can be classified with more confidence.

<img src="https://user-images.githubusercontent.com/107324616/179776508-541d72c7-15ef-4934-a283-88f9f09c9192.png"> 

## Basic Working Pipeline of the Project

![image](https://user-images.githubusercontent.com/107324616/179779255-ed3840c4-d44f-4fb1-b042-364fc9c0e0a7.png)

The following steps are used to create a Machine Larning Project using predefined dataset:
1. Data Collection: The very first step is to collect the data and required dependencies.
2. Data Analysis and Data Preprocessing
2.1 Data Analysis: After that, we used to analyze the dataset, about it's behaviour, trend and changes with respect to independent attributes. We also have to analyze the dependencies between every attribute, such that our model must be fitted perfectly.
2.2 Data Cleaning and Preprocessing: This is the most important step in model creation. The Cleaning of our dataset, such that the good data can be used for next process and unrequired/bad data should be removed so that the condition of overfitting and underfitting won't occur.
3. Feature Enginnering: It is a machine learning technique that leverages data to create new variables that aren't in the training set. It can produce new features for both supervised and unsupervised learning, with the goal of simplifying and speeding up data transformations while also enhancing model accuracy.
4. Data Splitting (Train-Test): Now we will spilt the dataset into two parts, the training part will be used to create the model and testing part will be used to verify the results of our model.
5. At last, we will select the most accurate result between both the techniques.

## Required Dependencies

1. [numpy](https://github.com/numpy/numpy)
2. [pandas](https://github.com/pandas-dev/pandas)
3. [matplotlib](https://github.com/matplotlib/matplotlib)
4. [scikit-learn](https://github.com/scikit-learn/scikit-learn)
5. [seaborn](https://github.com/seaborn/seaborn)


