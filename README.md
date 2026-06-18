🚢 Titanic Dataset - Data Cleaning, Loading & Exploratory Data Analysis (EDA)

This project performs Data Cleaning, Preprocessing, Feature Engineering, and Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python and popular data science libraries. The goal is to understand passenger characteristics, handle missing values, create meaningful features, and identify factors affecting survival rates. 


---

📌 Project Overview

The Titanic dataset contains information about passengers aboard the RMS Titanic, including demographics, ticket details, passenger class, and survival status.

This project focuses on:

Loading and understanding the dataset

Cleaning missing and inconsistent data

Performing descriptive statistical analysis

Feature engineering

Survival analysis across different groups

Correlation analysis between numerical features



---

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab



---

📂 Dataset Information

Dataset Size: 891 rows × 12 columns

Features

Column	Description

PassengerId	Unique Passenger ID
Survived	Survival Status (0 = No, 1 = Yes)
Pclass	Passenger Class
Name	Passenger Name
Sex	Gender
Age	Age of Passenger
SibSp	Number of Siblings/Spouses aboard
Parch	Number of Parents/Children aboard
Ticket	Ticket Number
Fare	Ticket Fare
Cabin	Cabin Number
Embarked	Port of Embarkation



---

🔍 Exploratory Data Analysis

Dataset Inspection

Checked shape and structure of dataset

Displayed first few records

Examined data types and null values


Descriptive Statistics

Generated statistical summaries including:

Mean

Median

Standard Deviation

Minimum & Maximum Values

Quartiles



---

🧹 Data Cleaning

Missing Values Handling

Column	Missing Values

Cabin	687
Age	177
Embarked	2


Cleaning Strategy

Dropped Cabin column due to excessive missing values.

Filled missing Age values using median age.

Filled missing Embarked values using mode.


Result:

No missing values remaining.


Duplicate Records

Checked for duplicate rows.

No duplicate records found.



---

⚙️ Feature Engineering

Created new features to improve analysis:

Age Group

Passengers categorized into:

Child

Teenager

Young Adult

Adult

Senior


Family Size

FamilySize = SibSp + Parch + 1

IsAlone

IsAlone = 1 if FamilySize == 1 else 0


---

📊 Key Insights

Survival Rate by Gender

Gender	Survival Rate

Female	74.2%
Male	18.9%


Observation: Female passengers had significantly higher survival rates.


---

Survival Rate by Passenger Class

Class	Survival Rate

1st Class	63.0%
2nd Class	47.3%
3rd Class	24.2%


Observation: Higher-class passengers had better chances of survival.


---

Survival Rate by Age Group

Age Group	Survival Rate

Child	58.0%
Teenager	42.9%
Young Adult	35.3%
Adult	40.0%
Senior	22.7%


Observation: Children had the highest survival rate, while seniors had the lowest.


---

Average Fare by Passenger Class

Class	Average Fare

1st Class	84.15
2nd Class	20.66
3rd Class	13.68



---

🔗 Correlation Analysis

Correlation matrix generated for:

Survived

Pclass

Age

Fare

FamilySize


Key observations:

Survival negatively correlates with Passenger Class.

Fare shows a positive relationship with survival.

Age has a weak correlation with survival.

Family Size shows very little direct correlation with survival.



---

📈 Future Improvements

Add advanced visualizations

Build predictive machine learning models

Perform feature selection

Apply classification algorithms:

Logistic Regression

Random Forest

Decision Tree

XGBoost




---

▶️ How to Run

1. Clone the repository



git clone https://github.com/yourusername/titanic-eda.git

2. Install dependencies



pip install pandas numpy matplotlib seaborn

3. Run the notebook/script



python titanic_eda.py


---

📚 Learning Outcomes

Through this project, I gained practical experience in:

Data Cleaning

Missing Value Treatment

Feature Engineering

Exploratory Data Analysis (EDA)

Statistical Analysis

Data Visualization

Real-world Dataset Handling



---

👩‍💻 Author

Akanksha
B.Tech (CSE - AI & ML)
Passionate about Data Science, Machine Learning, and AI.

⭐ If you found this project useful, don't forget to star the repository!
