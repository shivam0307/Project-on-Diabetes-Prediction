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

Contrary to popular belief, logistic regression IS a regression model. The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function.
g(z) = $\frac{1}{1 + e^-^z}$
