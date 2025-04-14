# 🛳 Titanic Dataset - Exploratory Data Analysis (EDA)

This project involves a detailed exploratory data analysis of the Titanic dataset, focusing on understanding the patterns and relationships in the data, especially those related to passenger survival.

## 📂 Files Included

- `EDA_Titanic_Dataset.ipynb` – Jupyter Notebook containing code and visualizations
- `titanic_eda_report.pdf` – PDF report summarizing the key findings
- `README.md` – Project overview and documentation(This File)

## 📌 Objective

The primary aim of this project is to:

- Clean and preprocess the Titanic dataset
- Perform univariate, bivariate, and multivariate analyses
- Derive insights using visualizations
- Conduct statistical hypothesis testing (T-test, Chi-square, ANOVA)

## 📊 Key Steps in Analysis

1. **Initial Data Exploration**  
   Understanding structure, null values, and statistical properties.

2. **Data Cleaning & Feature Engineering**  
   - Imputation of missing values  
   - Dropping redundant columns  
   - Feature creation: `FamilySize`, `IsAlone`, and `Title`

3. **Univariate Analysis**  
   Visual exploration of single variables like Age, Fare, Family Size, etc.

4. **Bivariate Analysis**  
   Understanding survival rates in relation to variables such as:
   - Sex
   - Passenger Class
   - Age Groups
   - Family Size
   - Alone or not

5. **Multivariate Analysis**  
   - Correlation heatmap  
   - Survival rates segmented by Sex and Class

6. **Statistical Tests**  
   - T-Test: Age vs Survival  
   - Chi-square: Sex vs Survival  
   - ANOVA: Fare across Passenger Classes

## 📈 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (for statistical tests)
- Jupyter Notebook

## 📌 Dataset Source

[Titanic Dataset - Data Science Dojo GitHub](https://github.com/datasciencedojo/datasets/blob/master/titanic.csv)

## 📎 How to Run

1. Clone the repository
2. Open `EDA_Titanic_Dataset.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis
4. View final report in `titanic_eda_report.pdf`

## ✅ Conclusion

The Titanic EDA project demonstrates the power of combining data cleaning, visualization, and statistical reasoning to uncover insights into real-world datasets. The analysis also helps identify the most influential features affecting survival.

---

