# 📊 TelecomX - Customer Churn Analysis (Sequel)

## 📋 Index
- [Project Description](#project-description)
- [Project Status](#project-status)
- [Analysis Features and Demonstration](#analysis-features-and-demonstration)
- [Technologies Used](#technologies-used)
- [Main Results](#main-results)
- [Project Developers](#project-developers)
- [Conclusion](#conclusion)

<a name="project-description"></a>
## 📖 Project Description
This README is the sequel to the original TelecomX challenge report and documents the second phase of the project. The first phase focused on extraction, cleaning, and exploratory analysis. This sequel extends the work into predictive modeling and decision-oriented retention strategy design. 📈

Original repository (source of this sequel):
`https://github.com/BenjaminArauz/challenge-data-science-telecom`

The objective of this continuation is to move from descriptive insights to actionable prediction by implementing a complete machine learning workflow: data preparation for models, train-test split, model training, model comparison, variable relevance interpretation, and strategic recommendations supported by model performance.

<a name="project-status"></a>
## 🚀 Project Status
Current Status: Completed (Sequel Phase)

The sequel has been completed with all planned ML components:
- ML-ready data preparation ✓
- Train/test split implementation ✓
- Baseline model training and comparison ✓
- Evaluation with classification metrics and confusion matrices ✓
- Critical performance analysis (overfitting/underfitting discussion) ✓
- Variable relevance analysis and business interpretation ✓
- Retention strategy report based on findings ✓

<a name="analysis-features-and-demonstration"></a>
## ✨ Analysis Features and Demonstration

### Main Components
- **ML Data Preparation**:
  - Removed non-predictive identifiers
  - One-hot encoded categorical variables
  - Checked class imbalance and applied SMOTE
  - Applied scaling alternatives (standardization and normalization)
- **Data Split for Evaluation**:
  - Stratified train-test split (80/20 by default)
- **Modeling**:
  - Logistic Regression (scaled)
  - Random Forest (non-scaled)
  - Additional interpretation context for KNN and SVM relevance criteria
- **Model Evaluation**:
  - Accuracy, Precision, Recall, F1-score, ROC-AUC
  - Confusion matrices
  - Comparative summary table
- **Interpretation and Reporting**:
  - Critical comparison of model behavior
  - Variable relevance explanation by model type
  - Retention strategy proposal in text-box report format

### Key Findings In The Sequel
1. **Random Forest showed stronger predictive performance** in the model comparison phase.
2. **Logistic Regression remained valuable for interpretability** through coefficient-based reasoning.
3. **Early customer lifecycle and pricing/contract variables** remain central to churn risk.
4. **Feature relevance should be triangulated across model families** for robust decision-making.
5. **Retention actions should be prioritized using model-based risk segmentation**.

### How To Use This Sequel Analysis
1. Open `TelecomX_LATAM.ipynb` in VS Code or Jupyter.
2. Run all cells in order.
3. Review the modeling and evaluation sections.
4. Check the final interpretive text blocks for actionable strategy recommendations.

<a name="technologies-used"></a>
## 💻 Technologies Used
This sequel phase uses the original stack plus ML-oriented libraries:

- **Python 3.x**: Core language
- **pandas / NumPy**: Data processing
- **Matplotlib / Seaborn**: Visualization
- **scikit-learn**: Model training, evaluation, and preprocessing
- **imbalanced-learn**: Class balancing with SMOTE
- **Jupyter Notebook / VS Code Notebook**: Interactive workflow

<a name="main-results"></a>
## 📊 Main Results

### Sequel Deliverables
- End-to-end supervised modeling pipeline on churn data
- Comparative results across at least two model types
- Structured discussion on overfitting and underfitting risk
- Written interpretation of variable relevance by model family
- Business-focused retention strategy report

### Strategic Recommendations From Sequel Results
1. **Deploy risk scoring pipeline** prioritizing high-risk customer cohorts.
2. **Use Random Forest for predictive operations** and Logistic Regression for explainability support.
3. **Strengthen early retention interventions** in the first customer lifecycle months.
4. **Design value-focused offers** around pricing and contract sensitivity.
5. **Increase adoption of support/security services** to reduce churn propensity.

### Expected Operational Impact
- Earlier churn-risk detection
- Better retention campaign prioritization
- Improved alignment between model outputs and business actions
- Higher explainability in decision processes

<a name="project-developers"></a>
## 👨‍💻 Project Developers
This sequel was developed by:

- **Benjamín Arauz**

Contact: benjaminarauzc@gmail.com

<a name="conclusion"></a>
## 🎯 Conclusion
This sequel transforms the original TelecomX challenge from exploratory analysis into a practical predictive framework. It combines model performance, interpretability, and business strategy in a single workflow, enabling data-driven retention decisions.

This provide a complete end-to-end view of the project: from understanding churn behavior to operationalizing churn prediction and retention actions.
