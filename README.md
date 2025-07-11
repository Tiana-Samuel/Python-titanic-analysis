# 🛳️ Titanic Survival Analysis with Python  
<img width="328" height="186" alt="image" src="https://github.com/user-attachments/assets/5d1ea8bb-b4de-42a8-a4ec-9f212a618574" />

## 📌 Project Summary

The sinking of the Titanic remains one of the most well-known tragedies in maritime history. This project analyzes real-world passenger data to understand **who survived, who didn’t, and why**.  
While this dataset is commonly used in data science, my approach focuses not on machine learning, but on **analytical storytelling**: finding patterns, testing hypotheses, and creating visuals that make the data speak clearly.  

This notebook is a great example of how thoughtful **Exploratory Data Analysis (EDA)** can provide actionable insights even without building a predictive model.

## 🎯 Objectives
- Clean and prepare a real-world dataset
- Explore missing values and inconsistent data
- Create meaningful visualizations to highlight survival trends
- Identify and explain **factors that influenced survival**, such as:
  - Gender
  - Passenger class
  - Family size
  - Port of embarkation
  - Age groups
  - Titles (e.g., Miss, Mrs, Master, etc.)

This project is ideal for:
- Beginners in data analytics
- Python learners looking for real project examples
- Anyone building a portfolio with strong EDA

## 📊 Key Insights
From my analysis, some standout patterns include:
- **Gender Matters:** Female passengers had a significantly higher survival rate than males.
- **Social Class Advantage:** First-class passengers had the highest chance of survival, while third-class passengers faced the greatest loss.
- **Cabin and Port Information Gaps:** Missing cabin data and embarked port “Q” showed notable differences in survival probability.
- **Family Size:** Those traveling with small families had better odds than those alone or in large groups.
- **Age Groups:** Children had better chances, supporting the “women and children first” theory.

These findings were supported by visualizations using Seaborn and Matplotlib.

## 🧪 Tools & Libraries Used
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-2E8B57?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)](https://matplotlib.org/)

- `pandas` for data wrangling  
- `seaborn` and `matplotlib` for advanced charting  
- `numpy` for numerical operations  
- `warnings`, `os`, and `datetime` for utility

## 📂 Files in This Repository
- `titanic_analysis.ipynb`: Main notebook with complete EDA, visualizations, and commentary
- `README.md`: You're here!
- `requirements.txt`: Library versions for reproducibility

## 🚀 Getting Started
You can view the notebook directly in this repo or run it locally:

```bash
# Clone this repository
git clone https://github.com/yourusername/titanic-analysis.git
cd titanic-analysis

# Open the notebook
jupyter notebook titanic_analysis.ipynb
