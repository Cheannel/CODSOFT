/** Author: Immaculata Chiamaka Lughas
** Project Name: Titanic Prediction
**/
#Program: CodSodt Internship

# Project Name: Titanic Survival Prediction

## Introduction and Purpose
 This project delves into the historical data of the ill-fated RMS Titanic, aiming to uncover hidden insights and make predictions about passenger survival. The sinking of the Titanic in 1912 was a tragic event, and this project serves as a tribute to those who were on board.
The primary purpose of this project is to apply data analysis and machine learning techniques to answer key questions:

 1. What were the factors that influenced a passenger's chances of surviving the Titanic disaster?
 2. Can a predictive model be built to accurately determine if a passenger survived based on available information?

## Project Overview
This is a classic beginner. This project analyzes the Titanic dataset to predict passenger survival and gain insights into the factors influencing survival rates. It follows a structured process that includes data exploration and visualisation, preprocessing, model building, model evaluation and validation.

## About Dataset
The dataset was downloaded from Kaggle. It contains information  about individual passengers, such as their age, gender, ticket,  class, fare, cabin, and whether or not they survived. In total, there are 12 columns and 418 rows in this particular dataset used.

 1. PassengerId: This column contains the passenger's ID. There is no missing value. This is the unique identifier of the passenger.

 2. Survived: This column represents whether the passenger survived or not. 0 means non-survivor, and 1 means survivor. There is no missing value.

 3. PClass: Also referred to as Passenger Class. There are 3 unique values in this column, it contains information about the class of the ticket purchased by the passenger Class. 1-First class, 2-Second class and 3- Third class.

 4. Name: Names of the passenger and their title.

 5. Sex: This column contains information on the gender of the passengers; male or female.

 6. Parch: This shows the number of parents or children aboard the Titanic.

 7. SibSp: This column contains the number of siblings or spouses aboard the Titanic.

 8. Age: The age of the passenger.

 9. Ticket: This column contains the details of the ticket number.

 10. Fare: The amount paid for the ticket.

 11. Cabin: The cabin number where the passenger stayed (if available). There are about 341 missing values in this column

 12. Embarked: The port of embarkation, is the point where they entered the ship for the passenger.
C: Cherbourg, Q: Queenstown, and S: Southampton.

## Process
 1. Data Exploration
The project begins by loading and exploring the Titanic dataset.
- Key steps:
  - Exploring dataset dimensions and structure.
  - Handling missing values.

  2. Data Visualization
  This involves a graphical representation of the data.
  - Visualizing data distributions and relationships using Matplotlib and Seaborn.

 3. Data Preprocessing
Preprocessing is crucial for preparing data for machine learning models.
- Key preprocessing steps:
  - Encoding categorical features.
  - Splitting data into training and testing sets.

4. Model Building
Building predictive models to predict passenger survival.
- Implemented models:
  - Logistic Regression
  - Random Forest
  - Gradient Booster

 5. Model Evaluation
Evaluating model performance was done using relevant metrics.
- Metrics used include accuracy and F1-score.
- Comparing models to select the best-performing one.

6. Model Validation
The dataset was small, and there was a need to use a technique called cross-validation.
- Cross-validation helps to test the performance of a machine-learning model on different subsets of the training data.

7. Conclusion and Insights
- Summarizing the findings and insights gained from the analysis.
- Identifying the most influential factors in passenger survival.
- Discussing limitations and potential areas for further exploration.

## Usage
1. Clone this repository: `git clone https://github.com/Cheannel/CODSOFT.git`
2. Navigate to the project directory: `cd Project_Titanic_Survival`
3. Follow the Jupyter Notebook `Titanic_Survival_Prediction.ipynb` for a step-by-step walkthrough of the analysis.

## Data Sources
- The dataset used for this project is sourced from [Kaggle] (https://www.kaggle.com/datasets/brendan45774/test-file)

## Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook (Anaconda)

## Conclusion
In conclusion, my analysis of the Titanic dataset has provided valuable insights into the factors that influenced passenger survival during the tragic sinking of the RMS Titanic in 1912. I have discovered trends and patterns in the relationship of the features.

    The gender of passengers played a pivotal role, with a significantly higher survival rate among females.
    Passenger class was another key factor, with first-class (1) passengers having a better chance of survival compared to those in lower classes.
    Age was also a contributing factor, with children having a higher likelihood of survival.

The predictive models, including Logistic Regression, Random Forest, and Gradient Booster, demonstrated same degrees of success in forecasting survival.

However, it's crucial to assert the impediments of the analysis done in this project. The dataset size was relatively small, and some cabin data were missing, which was later was dropped. The survived column had only one category for each gender, which could have influenced the results.

Finally, the Titanic Survival Prediction project not only provides insights into historical events but also serves as a testament to the power of data analysis and machine learning in disclosing hidden patterns and making informed predictions.

## Author
- [Your Name](https://github.com/your-username)

## Project Status
Work in progress.

