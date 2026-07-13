# 🚢 Titanic Survival Analysis | Exploratory Data Analysis (EDA)

> **An end-to-end Exploratory Data Analysis (EDA) project on the Titanic dataset focused on data preprocessing, feature engineering, visualization, and extracting meaningful insights that explain passenger survival patterns.**

---

## 📌 Project Overview

The Titanic dataset is one of the most well-known datasets in Data Science and Machine Learning. Rather than directly building a prediction model, this project focuses on understanding the data, identifying hidden patterns, and discovering the factors that influenced passenger survival.

This project also marks **my first independently completed EDA project**, where every step—from data cleaning to visualization and insight generation—was performed without following a ready-made solution.

---

## 🎯 Project Objectives

* Understand the dataset and its structure
* Clean and preprocess raw data
* Handle missing values and detect outliers
* Engineer meaningful features
* Perform Univariate, Bivariate, and Multivariate Analysis
* Discover factors influencing passenger survival
* Generate actionable insights through data visualization

---

## 📂 Dataset Information

| Attribute         | Details                         |
| ----------------- | ------------------------------- |
| Dataset           | Titanic Dataset                 |
| Total Records     | **891**                         |
| Original Features | **12**                          |
| Target Variable   | **Survived**                    |
| Analysis Type     | Exploratory Data Analysis (EDA) |

---

## 🛠️ Data Preprocessing

The dataset was cleaned and prepared before analysis.

### ✔ Missing Value Treatment

| Feature  | Method            |
| -------- | ----------------- |
| Age      | Median Imputation |
| Embarked | Mode Imputation   |

### ✔ Removed Columns

* PassengerId
* Name *(after extracting Title)*
* Ticket
* Cabin

### ✔ Other Preprocessing Steps

* Duplicate value checking
* Outlier detection
* Data consistency verification

---

## ⚙️ Feature Engineering

To improve the quality of analysis, several new features were created.

| Feature           | Description                                                  |
| ----------------- | ------------------------------------------------------------ |
| **Title**         | Extracted from passenger names (Mr, Mrs, Miss, Master, etc.) |
| **FamilySize**    | Total number of family members traveling together            |
| **IsAlone**       | Indicates whether the passenger traveled alone               |
| **AgeGroup**      | Categorized passengers into age groups                       |
| **FarePerPerson** | Fare divided by Family Size                                  |

These engineered features helped uncover hidden relationships that were not directly visible in the original dataset.

---

## 📊 Exploratory Data Analysis

### 📈 Univariate Analysis

Analysis performed on individual variables:

* Passenger Class Distribution
* Gender Distribution
* Age Distribution
* Fare Distribution
* Passenger Titles
* Family Size
* Survival Distribution
* Embarked Distribution

---

### 📊 Bivariate Analysis

Relationships between survival and important features:

* Gender vs Survival
* Passenger Class vs Survival
* Age vs Survival
* Fare vs Survival
* Family Size vs Survival
* Embarked vs Survival
* Title vs Survival

---

### 📉 Multivariate Analysis

Combined analysis of multiple variables:

* Gender + Passenger Class + Survival
* Title + Passenger Class + Survival
* Family Size + Gender + Survival
* Fare + Passenger Class + Survival
* Correlation Heatmap

---

# 🔍 Key Insights

### 👩 Gender was the strongest survival factor.

Female passengers had a significantly higher survival rate than male passengers.

---

### 🎟 Passenger class strongly influenced survival.

Passengers traveling in **First Class** had much higher survival rates than those in **Third Class**.

---

### 💰 Higher ticket fares were associated with better survival.

Passengers who paid higher fares generally had a greater chance of surviving.

---

### 👨‍👩‍👧 Family size affected survival.

Passengers traveling with small families showed better survival rates than passengers traveling alone or in very large families.

---

### 🎩 Passenger titles revealed hidden demographic information.

Titles such as **Mrs**, **Miss**, and **Master** showed higher survival probabilities, while **Mr** had the lowest survival rate.

---

### 🚢 Boarding location had a relatively small impact.

Most passengers boarded from Southampton, while passenger class and gender remained much stronger predictors of survival.

---

## 💡 Major Findings

* Survival was **not random**.
* Gender played the most influential role.
* Passenger class significantly affected survival probability.
* Wealth (represented by Fare) influenced survival.
* Feature engineering improved the overall quality of analysis.
* Family structure had a measurable impact on survival outcomes.

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📁 Project Structure

```text
Titanic-Survival-EDA/
│
├── Titanic_EDA.ipynb
├── Titanic-Dataset.csv
├── Cleaned Titanic Dataset.csv
├── README.md
│
├── Images/
│   ├── Age Distribution
│   ├── Fare Distribution
│   ├── Passenger Class
│   ├── Survival Analysis
│   └── Correlation Heatmap
│
└── Outputs/
    └── Cleaned Titanic Dataset.csv
```

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Outlier Detection
* Feature Engineering
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Insight Generation

---

## 📚 Key Learning

This project reinforced an important principle in Data Science:

> **"Before building a machine learning model, understand the data thoroughly."**

Through this project, I strengthened my ability to clean data, engineer meaningful features, visualize complex relationships, and convert raw data into actionable insights.

---

## 🔮 Future Improvements

* Build Classification Models
* Compare Multiple Machine Learning Algorithms
* Hyperparameter Tuning
* Feature Importance Analysis
* Deploy an Interactive Dashboard using Streamlit

---

## 👨‍💻 Author

**Priyanshu Sahu**

**Aspiring Data Scientist | Python | Data Analysis | Machine Learning**

If you found this project helpful or interesting, consider giving it a ⭐ to support the repository.

This version is clean, recruiter-friendly, and follows the style commonly seen in strong Data Science GitHub repositories. It avoids unnecessary decoration while highlighting the technical work, methodology, and outcomes in a professional format.
