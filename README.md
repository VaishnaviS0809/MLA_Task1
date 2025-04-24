# MLA Task 1 - Data Cleaning & Preprocessing

This repository contains the solution for **Task 1** of the **MLA Internship Program**. The objective is to clean and preprocess raw data (Titanic dataset) for machine learning using Python and its data science libraries.

---

## 📌 Task Objective

To perform data cleaning and preprocessing steps such as:
- Handling missing values
- Encoding categorical data
- Normalizing numeric features
- Outlier detection and removal
- Visualizing data using plots

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📁 Files Included

- `MLA_Task1_DataCleaning.ipynb`: Main Jupyter notebook with all steps implemented.
- `titanic.csv`: Dataset used (upload manually if not visible).
- `cleaned_titanic.csv`: (Optional) Output of the cleaned dataset.

---

## 📊 Steps Performed

1. **Data Loading** – Read the Titanic dataset using `pandas`.
2. **Data Exploration** – View null values, data types, and stats.
3. **Missing Value Handling** – Use median and mode to fill missing entries.
4. **Feature Encoding** – Label encode `Sex` and one-hot encode `Embarked`.
5. **Normalization** – Apply `StandardScaler` to `Age` and `Fare`.
6. **Outlier Removal** – Visualize and remove outliers using IQR method.
7. **Final Output** – Export the cleaned dataset.

---

## 📷 Sample Visualizations

- Boxplot of Age and Fare to identify outliers.
- Histograms (optional) to understand distribution.

---

## ✅ How to Use

1. Open the notebook using [Google Colab](https://colab.research.google.com/).
2. Upload the `titanic.csv` file manually if needed.
3. Run all cells one by one.
4. View results and clean data.

---

## 📬 Contact

**Author**: Vaishnavi S  
If you have any questions or suggestions, feel free to open an issue or reach out!

---

> This project is part of the **MLA Internship** program under the module: Data Preprocessing.
