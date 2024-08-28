# 🏠 Real Estate Data Analysis: Subset Selection Methods 📊

## 🎯 Project Overview

**AIM:** Apply data mining techniques to derive insights from real estate data. The analysis focuses on using subset selection methods—exhaustive, forward, and backward—to identify the best predictive models for house age. This approach is scalable and applicable to larger datasets, making it valuable for organizations in the real estate industry.

<div align="center">

[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/devarchanadev/Statistical-Data-Mining-on-Real-Estate)
[![Download Dataset](https://img.shields.io/badge/Download-Dataset-green?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/)

</div>

## 💼 Business Impact

This project helps real estate companies and analysts by identifying the most influential factors affecting property values. By applying the optimal models identified in this analysis, businesses can make informed decisions on pricing, investments, and resource allocation. The ability to scale this approach to larger datasets adds significant value, offering broader insights into market trends and property valuation.

## 🔑 Key Insights and Recommendations

### 🛠️ Tools and Methods

| Category | Details |
|----------|---------|
| **Data Source** | Real estate dataset from [Kaggle](https://www.kaggle.com/) |
| **Tools Used** | R, RStudio |
| **Libraries** | MASS, ggplot2, dplyr |
| **Data Cleaning** | Removed unnecessary columns, renamed variables for clarity |

### 🔍 Subset Selection Methods

Three methods were applied to select the best predictors for house age:
1. Exhaustive
2. Forward
3. Backward

These methods ensure the models are not overfitted while maintaining high predictive accuracy.

### 📊 Model Comparison

<details>
<summary>Click to expand model comparison details</summary>

#### Metrics Used:
- **Mallows' Cp:** Balances bias and variance.
- **Bayesian Information Criterion (BIC):** Penalizes models with more parameters to avoid overfitting.

#### Findings:
The Cp and BIC metrics consistently indicated that models with three predictors were optimal across all methods.

</details>

<img width="517" alt="Screenshot 2024-08-28 143316" src="https://github.com/user-attachments/assets/b9814e2f-58db-4c2b-a8c3-66dce2776f8f">


### 💡 Recommendations

1. **Forward Selection Method:** Chosen randomly for further analysis due to the consistency of results across methods.
2. **Model Validation:** The model with three predictors showed the lowest test error, confirming its robustness.

<img width="267" alt="Screenshot 2024-08-28 143430" src="https://github.com/user-attachments/assets/162765e2-0b1e-4416-8805-81b0fbe301e1">


## 🤔 Business Questions Answered

1. **What factors most influence house age?**
   - The analysis identified a consistent set of three predictors across all methods.
2. **How can companies use this model to improve decision-making?**
   - The model provides a reliable tool for predicting house age, assisting in property valuation and investment decisions.

## 📈 Results and Conclusion

The analysis confirmed that models with three predictors are optimal for predicting house age. These models were consistent across all subset selection methods used, making them highly reliable for scaling to larger datasets.

> **Statistical Importance:** The consistent results across Cp and BIC metrics validate the robustness of the model selection process. This highlights the importance of statistical methods in ensuring accurate model selection, crucial for data scientists to make reliable predictions.

**Conclusion:** The forward selection method was chosen for its simplicity and consistency, making it an ideal choice for further analysis and application in real-world scenarios. This approach ensures that the derived models are not only accurate but also practical for use in larger datasets and diverse market conditions.

## 🚀 Getting Started

### Tools and Dataset

- **Dataset:** Real estate data available on [Kaggle](https://www.kaggle.com/)
- **Tools:** R, RStudio, Libraries: MASS, ggplot2, dplyr

### Installation Steps

1. Clone the repository:
2. Navigate to the project directory:
3. Install dependencies:
```R
install.packages(c("MASS", "ggplot2", "dplyr"))
```
## 🧠 Key Takeaways for Data Scientists

- **Consistency in Model Selection:** Always check for consistency across different methods to ensure robustness.
- **Importance of Model Validation:** Validate your models using training and testing sets to ensure predictive accuracy.
- **Statistical Significance:** Understand the statistical metrics (Cp, BIC) to avoid overfitting and ensure model reliability.

> **Remember:** The methods you choose should balance complexity with accuracy, especially when scaling up to larger datasets.
