# Credit Default Prediction – Machine Learning Challenge

This project was developed as part of a technical challenge for a data science selection process.  
The goal was to build a predictive model capable of identifying potential defaulters based on customer data.

## 🧠 Objective

To use historical customer data to predict the likelihood of default, with a focus on identifying true defaulters (high recall).

## 📊 Workflow

1. **Exploratory Data Analysis (EDA):**
   - Examined class imbalance and variable distributions
   - Identified relevant patterns in customer behavior

2. **Feature Engineering:**
   - Created new variables to better capture risk signals
   - Normalized and cleaned existing fields

3. **Model Training:**
   - Models used: Logistic Regression, AdaBoost, Gradient Boosting
   - Hyperparameter tuning via grid search
   - Applied `scale_pos_weight` to address class imbalance

4. **Model Evaluation:**
   - Focused on **recall for defaulters** to reduce missed risk
   - Compared performance using classification report and confusion matrix

5. **Improvement Proposals:**
   - Suggested model ensembling (voting-based) to improve robustness
   - Considered potential integration with business rules

## ⚙️ Tech Stack

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## 📈 Metrics Highlight

The best model reached:
- High recall for the positive class (defaulters)
- Balanced trade-off with precision to avoid excessive false positives

## 📚 Learnings

This project reinforced the importance of:
- Matching model performance to business objectives
- Handling imbalanced datasets carefully
- Communicating results clearly and critically

## 🚀 Next Steps

- Deploy the model using a batch prediction API or stream it into dashboards
- Monitor model drift and retrain as new data becomes available

---

**Feel free to explore the notebook and reach out if you’d like to collaborate or share ideas!**

