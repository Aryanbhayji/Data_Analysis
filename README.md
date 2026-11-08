# 📊 Data Analysis with Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge" />
</p>

## 👋 About This Repository

Welcome to my **Data Analysis with Python** repository!

This repository documents my journey of learning and applying data analysis concepts through practical projects, real-world datasets, statistical techniques, and data visualisation.

My goal is to understand data beyond just writing code — discovering patterns, analysing relationships, testing hypotheses, and extracting meaningful insights that can support better decisions.

I am continuously expanding this repository as I develop my skills in **Data Analysis, Statistics, and Machine Learning**.

---

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Numerical and mathematical operations |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| SciPy | Statistical hypothesis testing |
| Jupyter Notebook | Interactive analysis and experimentation |

---

## 📂 Datasets & Projects

I work with different datasets to explore analytical techniques and solve data-related problems.

### 1. Titanic Dataset 🚢
**Objective:** Explore passenger information and understand factors associated with survival.

Topics:
- Data cleaning and preprocessing
- Missing value analysis
- Survival rate analysis
- Gender and passenger-class analysis
- Age distribution
- Correlation and visualisation
- Statistical hypothesis testing

### 2. Sample Superstore Dataset 🏪
**Objective:** Analyse sales and business performance.

Topics:
- Sales and profit analysis
- Category-wise performance
- Regional comparisons
- Customer segmentation
- Business insights through visualisation

### 3. Hotel Bookings Dataset 🏨
**Objective:** Understand hotel booking patterns and customer behaviour.

Topics:
- Booking trends
- Cancellation analysis
- Customer distribution
- Seasonal patterns
- Correlation analysis

### 4. Online Retail Dataset 🛒
**Objective:** Explore transactional data and customer purchasing behaviour.

Topics:
- Revenue analysis
- Product performance
- Customer purchasing patterns
- Sales trends
- Exploratory Data Analysis (EDA)

---

## 📈 Concepts I'm Exploring

### Data Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Preprocessing
- Missing Value Treatment
- Outlier Detection
- Feature Relationships
- Data Aggregation

### Mathematical & Statistical Analysis
- Mean, Median and Mode
- Variance and Standard Deviation
- Probability Distributions
- Correlation and Covariance
- Hypothesis Testing
- P-Value and Significance Level
- Confidence Intervals
- Chi-Square Test
- Independent Samples T-Test
- Mann-Whitney U Test
- Shapiro-Wilk Test

### Data Visualisation
- Bar Charts
- Histograms
- Scatter Plots
- Box Plots
- Heatmaps
- Pair Plots
- Distribution Plots
- Statistical Comparisons

---

## 🧪 Statistical Analysis Example

One of my analysis experiments involves testing whether passenger gender and survival are statistically associated in the Titanic dataset.

**Hypotheses:**

- H₀: Gender and survival are independent.
- H₁: Gender and survival are associated.

**Statistical method:** Chi-Square Test of Independence.

```python
import pandas as pd
from scipy.stats import chi2_contingency

df = pd.read_csv("titanic.csv")

table = pd.crosstab(df["Sex"], df["Survived"])

chi2, p_value, dof, expected = chi2_contingency(table)

print("Chi-Square Statistic:", chi2)
print("P-Value:", p_value)

if p_value < 0.05:
    print("Significant association found.")
else:
    print("Insufficient evidence of an association.")
```

This experiment demonstrates how statistical methods can help us investigate relationships in datasets.

---

## 🎯 Learning Roadmap

- [x] Python fundamentals
- [x] NumPy basics
- [x] Pandas fundamentals
- [x] Matplotlib visualisation
- [x] Seaborn visualisation
- [x] Exploratory Data Analysis
- [ ] Advanced Statistical Analysis
- [ ] Probability Distributions
- [ ] Feature Engineering
- [ ] Advanced Data Visualisation
- [ ] Machine Learning Applications
- [ ] Interactive Data Dashboards

---

## ⚙️ Getting Started

Clone this repository:

```bash
git clone https://github.com/Aryanbhayji/Data_Analysis.git
```

Navigate to the project directory:

```bash
cd Data_Analysis
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scipy jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Repository Philosophy

I believe that data analysis is not just about creating charts or calculating averages.

It is about asking meaningful questions, selecting appropriate mathematical and statistical methods, interpreting results, and communicating insights.

Every notebook in this repository represents a practical learning experiment.

---

## 👨‍💻 About Me

**Aryan Jain**

B.Tech | Computer Science & Engineering (AI & ML)

Interested in:
- Artificial Intelligence
- Machine Learning
- Data Science
- Statistical Analysis
- Building practical AI projects

I'm continuously learning, experimenting, and building projects to strengthen my understanding of data and intelligent systems.

---

<p align="center">
  <b>Learning by doing. Analysing through data. Building towards AI. 🚀</b>
</p>

<p align="center">
  ⭐ If you find this repository useful, consider giving it a star!
</p>
