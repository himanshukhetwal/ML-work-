Machine Learning Data Analysis Projects

This repository contains data analysis and preprocessing projects implemented using Python and Jupyter Notebook.
The main focus of these notebooks is to understand datasets, perform Exploratory Data Analysis (EDA), clean the data, engineer useful features, and analyze relationships between variables before applying machine learning models.

These projects demonstrate data handling, visualization, and statistical analysis skills, which are important steps in any machine learning pipeline.

📁 Repository Structure
ML-work-
│
├── Untitled.ipynb   → Insurance Dataset Data Analysis
├── Heart.ipynb      → Heart Disease Dataset Analysis
└── README.md

Each notebook focuses on understanding the dataset and preparing it for machine learning tasks.

📊 Project 1: Insurance Dataset Analysis

📄 File: Untitled.ipynb

This notebook analyzes a medical insurance dataset to understand how different factors influence insurance charges.

🔎 Tasks Performed
1️⃣ Data Loading

Imported dataset using Pandas

Checked dataset structure using:

head()

info()

describe()

2️⃣ Data Cleaning

Checked for missing values

Verified data types of each column

Ensured dataset consistency

3️⃣ Feature Engineering

Created additional features to improve analysis:

Gender encoding

Smoker status encoding

Region encoding

BMI category classification

Example BMI categories created:

Underweight

Normal

Overweight

Obese

4️⃣ Exploratory Data Analysis (EDA)

Performed detailed analysis to understand relationships between variables.

Analysis included:

Age vs Insurance Charges

BMI vs Charges

Smoking status impact

Gender distribution

Regional analysis

5️⃣ Data Visualization

Used Matplotlib and Seaborn to visualize patterns in the dataset:

Histograms

Count plots

Correlation heatmaps

Distribution plots

These visualizations helped identify important features affecting insurance cost.

❤️ Project 2: Heart Disease Dataset Analysis

📄 File: Heart.ipynb

This notebook analyzes a heart disease dataset to understand factors that contribute to heart disease.

The aim is to explore the dataset and identify important medical attributes that could be useful for prediction models.

🔎 Tasks Performed
1️⃣ Data Exploration

Examined the dataset structure:

Total number of records

Feature descriptions

Data types

Important medical attributes studied include:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Maximum heart rate

Exercise induced angina

2️⃣ Data Cleaning

Performed preprocessing steps such as:

Handling missing values

Checking inconsistent data

Preparing dataset for analysis

3️⃣ Exploratory Data Analysis (EDA)

Analyzed relationships between heart disease and different features.

Key analysis performed:

Age distribution of patients

Gender-based heart disease risk

Impact of cholesterol levels

Blood pressure trends

Chest pain type distribution

4️⃣ Data Visualization

Created visualizations to understand patterns in the dataset:

Bar charts

Histograms

Correlation analysis

Feature distribution plots

These visualizations help understand which features strongly influence heart disease.

🛠️ Technologies Used

The following tools and libraries were used in these projects:

Technology	Purpose
Python	Programming language
Jupyter Notebook	Interactive development environment
Pandas	Data manipulation and analysis
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical visualization
📈 Skills Demonstrated

These projects showcase the following skills:

✔ Data Cleaning
✔ Exploratory Data Analysis (EDA)
✔ Feature Engineering
✔ Data Visualization
✔ Statistical Analysis
✔ Dataset Preparation for Machine Learning

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/himanshukhetwal/ML-work-.git
2️⃣ Navigate to the Project Folder
cd ML-work-
3️⃣ Open Jupyter Notebook
jupyter notebook
4️⃣ Run the Notebook

Open any .ipynb file and run the cells step by step.

🎯 Future Improvements

Possible improvements to this project:

Build Machine Learning models

Apply classification algorithms

Perform feature selection

Evaluate models using metrics like accuracy, precision, recall

👨‍💻 Author

Himanshu Khetwal
Computer Science Engineering Student
Graphic Era Hill University
