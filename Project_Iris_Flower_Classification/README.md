# CodSodt Internship
## Author's Name: Immaculata Chiamaka Lughas

## Project Name: Titanic Survival Prediction

# Introduction
The IRIS Flower Classification project is an effort in machine learning to resolve a classic classification problem that involves distinguishing between three IRIS flower species. They include Setosa, Versicolor, and Virginica, respectively. 
This study shows how several machine learning algorithms and methodologies can be applied to this goal.

## Why IRIS Flowers?
IRIS flowers are well-known in the fields of data science and machine learning because of their unique traits and the ease with which they pose a categorization challenge. This makes the IRIS dataset a good place for beginners to start and a standard for evaluating more complex machine learning models.

## Purpose
Learning: One of the objectives of this project is to enable aspiring data scientists to gain hands-on experience in data preprocessing, model training, evaluation, and interpretation.

Model Benchmark: The project aims to create a benchmark for categorizing IRIS flowers.

Model Training: The project also intends to train a machine learning model that can learn from
these measurements and accurately classify the Iris flowers into
their respective species.

Compare Models: The project helped to note how different machine learning methods perform in classifying IRIS flowers.

Practical Application: Above all, the Iris-Flower Classification Project has real-world applications. Automated species identification can be extremely helpful in fields like botany and horticulture, where it can be applied to precisely classify IRIS flowers.

# Project Overview
The IRIS Flower Classification project aims to classify three kinds of IRIS flowers: Setosa, Versicolor, and Virginica. It's an excellent approach to learning about machine learning, and since it uses a well-known dataset, beginners will find it quite helpful.

The characteristics of these flowers, such as the diameters of their petals and sepals, were examined by a computer program to identify the species to which each flower belonged.

Although classifying flowers may appear straightforward, it is the basis for numerous practical applications, such as classifying plant species and automating jobs in agriculture and botany.

One can learn the fundamentals of machine learning, data preprocessing, and how to assess the precision of their predictions by following the step-by-step procedure.

This project is for everyone interested in machine learning, regardless of their expertise level.


## About Dataset
The dataset was downloaded from Kaggle. There is information about measurements of two particular features of three different species. It contains five columns and 150 rows in total. There were no missing values.

sepal_length and sepal_width: Both columns contain information about the sizes (Length and width, respectively) of the sepal feature of the species.

petal_length and petal_width: Both columns contain information about the sizes (Length and width, respectively) of the petal features of the species. 

# Data Exploration
The project begins by loading and exploring the Iris Flower dataset.

Loading the dataset: pandas.read_csv('IRIS_csv'); this command loads a dataset in a CSV file format.
 Exploring dataset dimensions and structure: Functions like info(), describe(), unique(), tail(), head(), and others
  
# Data Visualization 
  This involves a graphical representation of the data to present key relationships between species and the features provided.
  Visualizing data distributions and relationships using Matplotlib and Seaborn: A good number of plots were explored to show the distribution of the features against the species. 

# Data Preprocessing
Preprocessing is crucial for preparing data for machine learning models.
The preprocessing steps include:
Scaling numerical features: The feature data were scaled to ensure that all input features were on a common scale.
Train-test Splitting: The scaled dataset was split into training and testing sets. The purpose of this is to evaluate how well the machine learning model generalizes to new data.

# Model Selection and Training 
Three different machine learning algorithms were used during this project to 
- Model 1: Random Forest Classifier
I used the Random Forest Classifier because it often provides better accuracy and generalization compared to a single decision tree.

- Model 2: KNeighbors Classifier
KNeighbors Classifier is an implementation of K-Nearest Neighbors.
- Model 3: Logistic Regression
Logistic Regression is simple to implement and interpret.


Model training: The models were trained on the scaled training data. I compared the models to select the best-performing one.


# Model Evaluation
The performance of the model on the scaled testing data was evaluated using relevant metrics.
The metrics used include:
- Accuracy, 
- Confusion matrix: This helped to show the true positive, true negative, false positive, and false negative predictions of the Iris flower classification model.
- Precision, recall, and F1-score

## Confusion Matrix on Model Evaluation
The Confusion Matrix helped to show the true positive, true negative, false positive, and false negative predictions of the Iris flower classification model.
- Data visualization was done to display the Confusion matrix.

# Model Validation
The dataset was small, and there was a need to use a technique called cross-validation.
Cross-validation helps to test the performance of a machine learning model on different subsets of the training data. 

# Conclusion
From data discovery to model evaluation, the Iris Flower Classification project has been a voyage through the field of machine learning.

To categorize Iris flowers into the three different species Setosa, Versicolor, and Virginica, three machine learning models were created and trained.

I scaled the features and built up the dataset for training with meticulous data preprocessing.

Additionally, I was able to evaluate the models' performance using a number of metrics, such as accuracy, precision, recall, and F1-score. These measures gave us important information about how effectively my models forecast the future.

To learn more about the performance of the models, crucial visuals like confusion matrices and precision-recall curves were also made.

# Usage
1. Clone this repository: `git clone https://github.com/Cheannel/Project_Iris_Flower_Classification.git`
2. Navigate to the project directory: `cd Project_Iris_Flower_Classification.`
3. Follow the Jupyter Notebook `Iris_Flower_Classification.ipynb` for a step-by-step walkthrough of the analysis.

# Data Sources
- The dataset used for this project is sourced from Kaggle (https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook (Anaconda)

The documentation for this project offers step-by-step instructions and is an invaluable tool for both inexperienced and seasoned data scientists.
Although I have successfully classified iris flowers, there is always room for improvement. This project will require model deployment in later rounds.

It will be my responsibility to employ the top-performing model in real-world applications, such as automating the classification of Iris flower species.

## Author
[Immaculata Lughas] (https://github.com/Cheannel)

## Project Status
Work in progress.




