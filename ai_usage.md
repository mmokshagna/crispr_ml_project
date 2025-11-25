
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



### 3. Documentation and Formatting

AI was used for creating professional documentation:

#### README.md
- **Markdown tables**: Formatting model performance comparison tables
- **Emoji usage**: Adding visual indicators (✅, ⚠️, 📊, 🎯) for better readability
- **Code blocks**: Proper syntax highlighting for bash and python snippets

#### Jupyter Notebook
- **Output formatting**: Making print statements more readable


### What We Did (not AI):
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
