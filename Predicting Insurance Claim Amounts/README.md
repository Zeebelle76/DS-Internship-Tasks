# Task 4: Medical Insurance Cost Prediction 🏥

## 📌 Project Overview
As part of my Data Science internship at **Developers Hub Corporation**, I have developed a Machine Learning model to predict medical insurance costs. Insurance premiums are influenced by various factors like age, lifestyle, and physical health. This project uses **Linear Regression** to estimate these costs accurately.

## 🎯 Objective
- To analyze the relationship between personal attributes (Age, BMI, Smoking status) and insurance charges.
- To build and evaluate a regression model to predict the claim amounts.

## 📊 Dataset Description
The "Medical Cost Personal Dataset" includes the following information:
- **Age**: Age of the primary beneficiary.
- **Sex**: Insurance contractor gender (Female, Male).
- **BMI**: Body Mass Index (Ideal: 18.5 to 24.9).
- **Children**: Number of children covered by health insurance.
- **Smoker**: Smoking status (Yes, No).
- **Region**: Beneficiary's residential area.
- **Charges**: Individual medical costs billed by health insurance (Target Variable).

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🚀 Methodology
1. **Data Preprocessing:** Handled categorical data using encoding (Converting Sex, Smoker, and Region into numerical values).
2. **Exploratory Data Analysis (EDA):** Visualized the distribution of charges and the impact of smoking on insurance costs.
3. **Model Training:** Split the data into 80% training and 20% testing sets and applied the **Linear Regression** algorithm.
4. **Evaluation:** Measured the model's accuracy using R-squared, MAE, and RMSE.

## 📈 Key Insights & Results
- **Smoking Impact:** The most significant factor; smokers are charged much higher premiums than non-smokers.
- **Age & BMI:** Show a positive correlation with insurance costs; as these increase, the charges tend to rise.
- **Model Accuracy:** Achieved an **R-squared value of 0.74**, indicating that the model explains 74% of the variance in insurance costs.

## 📂 Project Structure
- `Medical_Insurance_Cost.ipynb`: The Jupyter Notebook containing the full code and analysis.
- `insurance.csv`: The dataset used for this project.
- `README.md`: Project summary and documentation.

## 👤 Author
- **Name:** Zainab Sohail
- **Internship:** Data Science & Analytics Intern at Developers Hub Corporation
