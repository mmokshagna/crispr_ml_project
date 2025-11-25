
# AI Usage Documentation

## Project: CRISPR gRNA On-Target Efficiency Prediction

**Team Members:** Dedeepya Chaalika Chukka (1002231599), Puli Joshith Reddy (1002231617), Mokshagna (1002198292)

**Date:** November 2025

---

## Overview

This document provides a transparent account of how artificial intelligence tools were utilized throughout this machine learning project. We believe in academic integrity and want to clearly document where and how AI assisted our work.

---

## AI Tools Used

- **ChatGPT** (OpenAI GPT-4)
- **GitHub Copilot**
- **Google Gemini**

---

## Specific Use Cases

### 1. Understanding Esoteric Library Functions

AI was extensively used to understand and implement functions from specialized Python libraries that were new to our team:

#### scikit-learn Advanced Features
- **`PolynomialFeatures`**: Understanding the `interaction_only` parameter and how degree-2 interactions work
- **`mutual_info_classif`**: Learning how mutual information scoring differs from ANOVA F-test
- **`SelectKBest`**: Figuring out how to extract selected feature names after transformation
- **`GridSearchCV`**: Understanding the `cv`, `scoring`, and `n_jobs` parameters for efficient hyperparameter tuning

#### XGBoost Parameters
- **`use_label_encoder`**: Understanding why this parameter is deprecated and how to handle it
- **`eval_metric`**: Learning the difference between 'logloss', 'auc', and 'error' metrics
- **`subsample` and `colsample_bytree`**: Understanding regularization through sampling
- **`gamma`**: Comprehending minimum loss reduction for tree splitting


#### Matplotlib/Seaborn Visualization
- **`plt.tight_layout()`**: Preventing label overlap in complex plots
- **ROC curve plotting**: Proper formatting of false positive rate vs true positive rate

### 2. Parameter Tuning Guidance

AI helped us understand which hyperparameters to tune and reasonable ranges:

- **Learning rates**: Why [0.01, 0.05, 0.1, 0.2] is a good range for gradient boosting
- **Tree depth**: Understanding the trade-off between depth and overfitting
- **Ensemble sizes**: Why 100-300 estimators is typically sufficient
- **Regularization**: How C parameter in logistic regression affects model complexity

### 3. Documentation and Formatting

AI was used for creating professional documentation:

#### README.md
- **Markdown tables**: Formatting model performance comparison tables
- **Emoji usage**: Adding visual indicators (✅, ⚠️, 📊, 🎯) for better readability
- **Code blocks**: Proper syntax highlighting for bash and python snippets
- **Project structure tree**: Creating ASCII tree representation of directory structure

#### Report Writing
- **LaTeX-style formatting**: Creating professional-looking equations and formulas
- **Table alignment**: Ensuring consistent column widths and alignment
- **Section organization**: Structuring methods, results, and discussion sections

#### Jupyter Notebook
- **Output formatting**: Making print statements more readable




## What AI Did NOT Do

To be clear about the boundaries of AI assistance:


### What We Did:
- Conceptualize the entire project based on the Doench 2016 paper
- Select appropriate models based on literature review
- Design the advanced feature engineering pipeline (polynomial interactions, MI selection)
- Run all experiments and collect results
- Interpret findings in biological context
- Make all analytical decisions
- Verify all AI-suggested code before using it
  
---

## Learning Outcomes

Using AI tools enhanced our learning by:

- **Accelerating understanding** of complex library functions
- **Exposing us to best practices** we might not have discovered independently
- **Saving time on formatting** so we could focus on analysis
- **Providing multiple perspectives** on implementation approaches

However, we ensured that:

- We **understood** every line of code before using it
- We could **explain** all methods and parameters
- We **independently verified** all results
- We **learned** the underlying concepts, not just copied solutions

---

## Ethical Considerations

We believe this use of AI is:

- **Transparent**: Fully documented in this file
- **Educational**: Enhanced our learning rather than replacing it
- **Appropriate**: Used for understanding tools, not generating original research
- **Honest**: We can defend and explain all work independently


## Conclusion

AI tools served as **learning accelerators** and **documentation assistants**, not as replacements for our own analytical thinking and research skills. We take full responsibility for all work presented and can independently explain and defend every aspect of this project.

This project represents our genuine effort to understand and apply machine learning to CRISPR gRNA efficiency prediction, with AI serving as a helpful resource in the same way textbooks, documentation, and Stack Overflow would be used.

---

## Acknowledgments

We acknowledge the use of:
- GitHub Copilot for code completion suggestions
- Google Gemini for markdown table formatting

---

**Signed:**
- Dedeepya Chaalika Chukka
- Puli Joshith Reddy
- Mokshagna

**Date:** November 25, 2025
