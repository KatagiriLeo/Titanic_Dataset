# Titanic Dataset Analysis 🛳️

This project analyzes the Titanic dataset using Python and visualizes insights using libraries like Seaborn and Matplotlib. The dataset is sourced from Seaborn's built-in Titanic dataset.

## 📁 Project Structure

## 📊 Dataset

The dataset is included within the Seaborn library and provides demographic and survival information for passengers aboard the Titanic. Additional features were created through one-hot encoding.

Key columns include:

- `survived` — Survival (0 = No, 1 = Yes)
- `pclass` — Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `sex` — Gender
- `age` — Age in years
- `sibsp` — # of siblings/spouses aboard
- `parch` — # of parents/children aboard
- `fare` — Passenger fare
- `embarked` — Port of Embarkation
- `adult_male` — Whether the passenger is an adult male (True/False)
- `alone` — Whether the passenger is alone (True/False)
- `embarked_C`, `embarked_Q`, `embarked_S` — One-hot encoded ports of embarkation
- `who_child`, `who_man`, `who_woman` — One-hot encoded passenger type by age/gender

## 🔍 Analysis Overview

The analysis includes:

- Data cleaning and preprocessing
- Feature engineering (including one-hot encoding)
- Exploratory data analysis (EDA)
- Visualizations of survival rates by gender, class, and age
- Correlation heatmap
- Conclusions and observations

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/KatagiriLeo/Titanic_Dataset.git
   cd Titanic_Dataset
   ```
