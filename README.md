# 🏠 Boston Housing — Statistics for Data Science (IBM / Coursera)

Peer-graded final project for IBM's **Statistics for Data Science with Python** course on Coursera. It uses the Boston Housing dataset to answer real questions about house prices with visualisation and hypothesis testing.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square)
![IBM](https://img.shields.io/badge/IBM-Coursera-052FAD?style=flat-square&logo=ibm&logoColor=white)

## What's in the notebook

**Descriptive statistics & visualisation**
- Boxplot of median home value (`MEDV`)
- Bar plot of homes bounded by the Charles River (`CHAS`)
- Scatter plot of nitric-oxide concentration vs. non-retail business acres
- Histogram of the pupil-to-teacher ratio

**Hypothesis testing**

| Question | Test |
|---|---|
| Do homes bounded by the Charles River have a different median value? | Independent t-test |
| Does median value differ by the age of the housing stock (pre-1940 share)? | One-way ANOVA |
| Is nitric-oxide concentration related to non-retail business acreage? | Pearson correlation |
| What is the effect of distance to employment centres on median value? | Linear regression (statsmodels OLS) |

Each test states H₀ and H₁, reports the statistic and p-value, and gives a conclusion.

## Run it

```bash
pip install pandas seaborn matplotlib scipy statsmodels
jupyter notebook "stats coursera.ipynb"
```
The dataset loads directly from IBM's public URL inside the notebook.

---
**Dakshraj Singh Chandawat** · [GitHub](https://github.com/DakshrajKurki) · [LinkedIn](https://www.linkedin.com/in/dakshraj-singh-chandawat-0a6349314)
