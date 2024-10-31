# DataScience Intership Task 2

## Introduction
This repository contains the code and analysis for Task 2 of my Data Science internship at Prodigy Info Tech. This task focuses on data cleaning and exploratory data analysis (EDA) using the Titanic dataset, chosen for its relevance in demonstrating key data analysis techniques.

## Dataset
The Titanic dataset, sourced from Kaggle, includes details about passengers aboard the Titanic, such as demographic information and survival status. Known for its utility in educational data science projects, it offers a practical framework for analyzing patterns and relationships within historical data.

### About the Dataset
We are using the Titanic Dataset here. It contains both numerical and string values. The predefined columns are:
- **Passenger ID**: Unique identifier for passengers
- **Survived**: Survival status (1 = Yes, 0 = No)
- **P Class**: The class passengers traveled in
  - **pclass**: A proxy for socio-economic status (SES); 1st = Upper, 2nd = Middle, 3rd = Lower
- **Name**: Passenger Name
- **Sex**: Gender of Passenger
- **Age**: Age of passenger (Age is fractional if less than 1. If the age is estimated, it's in the form of xx.5)
- **SibSp**: Number of siblings or spouse aboard
- **Parch**: Number of parents or children aboard
- **Ticket**: Ticket number
- **Fare**: Amount paid for the ticket
- **Cabin**: Cabin of residence
- **Embarked**: Port of embarkation

## Task Overview
The aim of this task was to apply data cleaning and EDA methods to uncover insights within the Titanic dataset. This process involved handling missing values and exploring inter-variable relationships to reveal patterns in survival rates and other factors.

## Key Analysis Insights
- Addressed missing values and removed duplicate data entries.
- Examined connections between variables like gender, passenger class, age, fare, and survival status.
- Found patterns, including a higher survival rate among females, the influence of passenger class on survival, and the connection between age and survival outcomes.

## Conclusion
Through thorough data cleaning and EDA, this analysis highlighted influential factors in Titanic survival rates, offering historical insights and underscoring the value of data science techniques in interpreting real-world events.

### Key Findings
- **Gender Disparity**: The survival rate for females was notably higher than that of males, consistent with the "women and children first" protocol implemented during the Titanic evacuation. This pattern reflects societal norms of the time, which prioritized the safety of women and children.

- **Passenger Class Disparity**: Although passengers in Class 3 made up the largest group, they experienced the lowest survival rates, suggesting a link between socio-economic status and survival likelihood. Passengers in higher classes may have had better access to lifeboats and resources during the evacuation.

- **Gender and Passenger Class Interaction**: Analyzing gender and class together shows that males in Class 3 had the lowest survival rates, highlighting a compounded effect where gender and socio-economic status influenced survival outcomes. Male passengers in lower classes faced a higher risk of not surviving the disaster.

- **Age Factor**: Younger adults had lower survival rates, indicating that age influenced survival outcomes. This aligns with the “women and children first” policy, which prioritized younger passengers during evacuation efforts.

- **Correlations with Survival**: Variables like fare, gender, passenger class (Pclass), and embarkation point (Embarked) were found to correlate with survival outcomes, underscoring their significance in determining survival probabilities during the Titanic disaster.

## Contact Information
For questions or feedback, please reach out to:

**Anushka Kadam**  
Email: anushkapkadam@gmail.com

## Dataset Link
You can access the dataset in this repository [here](Titanic-Dataset.csv).
