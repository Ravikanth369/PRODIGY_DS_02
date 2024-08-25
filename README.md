Titanic Exploratory Data Analysis (EDA)
This project focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The Titanic dataset, widely used in data science, offers insights into passenger demographics and survival rates from the tragic Titanic voyage.

Data Understanding
The dataset is sourced from Kaggle's Titanic competition and comprises 891 rows and 12 columns. The columns are:

PassengerId: A unique identifier for each passenger.
Survived: A binary variable indicating whether the passenger survived (1) or did not survive (0).
Pclass: Ticket class (1st, 2nd, or 3rd).
Name: Passenger's name.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard.
Parch: Number of parents/children aboard.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Exploratory Data Analysis
Univariate Analysis

Univariate analysis involves examining and describing the characteristics of individual variables in the dataset. For the Titanic dataset, the following analyses were performed:

Histograms: Displaying the distribution of passenger ages.
Bar Plots: Illustrating the distribution of passenger classes.
Pie Chart: Visualizing the survival rate of passengers.
Bivariate Analysis

Bivariate analysis explores relationships between two variables:

Scatter Plots: Comparing age versus fare to observe any relationship.
Bar Plots: Comparing the number of survivors across different passenger classes.
Box Plots: Comparing fare distributions among different passenger classes.
Correlation Heatmap: Examining the correlation between age and fare.
Multivariate Analysis

Multivariate analysis extends to examining multiple variables simultaneously:

Parallel Coordinates Plots: Used to visualize relationships between multiple variables and survival rates.
Insights and Conclusions
Survival Rate: Approximately 59.4% of passengers did not survive, while 40.6% survived.
Age Distribution: There were relatively fewer children (aged 5-15 years) and elderly passengers (over 60 years) aboard the Titanic.
Passenger Class and Survival: Passengers in Class 1 had a higher likelihood of survival compared to those in Class 2 and Class 3, indicating a potential influence of passenger class on survival chances.
Class Distribution and Survival: Class 3 had the highest number of passengers but the lowest survival rate, suggesting that class might have influenced rescue efforts.
Fare and Survival: A positive correlation exists between fare and survival, indicating that passengers who paid higher fares had a better chance of surviving.
Age and Survival: There appears to be a slight concentration of younger survivors, suggesting that age might have had some impact on survival rates.
