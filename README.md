# 🚢 Titanic Dataset Analysis

This project explores and analyzes a dataset of passengers aboard the Titanic. The goal is to uncover insights about survival rates, passenger demographics, and socio-economic factors that influenced survival.

## 📂 Dataset

The dataset used in this project includes detailed information about passengers aboard the Titanic. It includes the following features:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Full name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard
- **Parch**: Number of parents or children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 📊 Project Goals

- Understand the distribution of passengers based on class, age, and gender.
- Analyze survival rates across different groups (e.g., gender, class).
- Identify important features influencing survival.
- Visualize key trends and patterns in the dataset.

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- Google Colab

## 🔑 Key Learnings

- **Higher-class passengers (1st class) had a higher survival rate** compared to lower classes.
- **Women and children** had a higher likelihood of survival than adult men.
- **Passengers embarking from Cherbourg (C)** had a slightly higher survival rate compared to other ports.
- **Age, gender, and class** were significant factors affecting survival chances.
- **Missing data** (especially for 'Age' and 'Cabin') requires careful handling through imputation or exclusion.
