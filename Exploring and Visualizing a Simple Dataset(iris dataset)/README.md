# Task 1: Exploring and Visualizing the Iris Dataset 🌸

## 📌 Project Overview
The Iris dataset is a classic in machine learning and statistics. In this task, I performed Exploratory Data Analysis (EDA) to understand the dataset's structure and the relationships between different flower features.

## 🎯 Objective
- To load and inspect the dataset using **Pandas**.
- To visualize data distributions and identify patterns between species.
- To detect outliers using statistical plots.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn

## 🚀 Methodology & Steps
1. **Data Inspection:** Used `.shape`, `.columns`, and `.head()` to understand the number of entries and feature types (Sepal Length, Sepal Width, Petal Length, Petal Width).
2. **Data Summary:** Used `.describe()` to get mean, standard deviation, and quartiles.
3. **Visualizations:**
    * **Histograms:** To check the frequency distribution of each feature.
    * **Scatter Plots:** To observe how species are separated based on petal and sepal measurements.
    * **Box Plots:** To identify the spread of data and detect any outliers in the measurements.



## 📈 Key Insights
- **Species Separation:** Setosa species is easily distinguishable from Versicolor and Virginica based on petal length and width.
- **Feature Correlation:** Petal length and petal width show a very strong positive correlation.
- **Data Quality:** The dataset is clean with no missing values, making it ideal for initial exploration.

## 📂 File Structure
- `Iris_Dataset.ipynb`: Complete Python code with visualizations.
- `README.md`: Task documentation.
