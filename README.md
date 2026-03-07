# Insurance Dataset Analysis (EDA & Preprocessing)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA), Data Cleaning, and Feature Engineering** on the **Insurance dataset** to understand how different factors influence medical insurance charges.

The notebook analyzes relationships between variables such as **age, BMI, smoking habits, number of children, and gender** with insurance costs.

The goal is to:

* Understand the dataset
* Identify patterns and correlations
* Prepare the data for machine learning models

---

## 📂 Dataset

The dataset used in this project is **insurance.csv**, which contains the following features:

| Feature  | Description            |
| -------- | ---------------------- |
| age      | Age of the individual  |
| sex      | Gender (male/female)   |
| bmi      | Body Mass Index        |
| children | Number of dependents   |
| smoker   | Smoking status         |
| region   | Residential region     |
| charges  | Medical insurance cost |

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔎 Project Steps

### 1️⃣ Data Loading

The dataset is loaded using **Pandas** and inspected using:

* `.head()`
* `.info()`
* `.describe()`

### 2️⃣ Exploratory Data Analysis (EDA)

Various visualizations are used to understand the dataset:

* Histograms for numerical variables
* Count plots for categorical variables
* Boxplots for outlier detection
* Correlation heatmap

### 3️⃣ Data Cleaning

* Duplicate rows are removed
* Missing values are checked
* Data types are verified

### 4️⃣ Feature Engineering

Categorical variables are converted to numerical values for analysis.

Example:

* male → 0
* female → 1

### 5️⃣ Correlation Analysis

Correlation between variables is analyzed to understand which features affect **insurance charges**.

---

## 📊 Visualizations Included

The notebook includes multiple plots:

* Distribution plots
* Count plots
* Box plots
* Heatmap for correlations

These visualizations help identify trends such as:

* Impact of smoking on insurance charges
* BMI distribution
* Age vs insurance cost patterns

---

## 📁 Project Structure

```
ML-work-
│
├── insurance.csv
├── Untitled.ipynb
└── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install required libraries
3. Run the Jupyter Notebook

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open the notebook:

```bash
jupyter notebook
```

---

## 🎯 Future Improvements

* Build Machine Learning models to predict insurance charges
* Feature scaling and normalization
* Model evaluation and comparison
* Deployment using a web app

---

## 👨‍💻 Author

**Himanshu Khetwal**

Computer Science Engineering Student
Interested in **Machine Learning, Data Science, and Software Development**

---
