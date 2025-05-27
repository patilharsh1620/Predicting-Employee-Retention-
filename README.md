
# 📊 Predicting Employee Retention

## 📌 Overview

This project focuses on predicting employee retention using a logistic regression model. Employee retention is a key factor in maintaining organizational stability, reducing recruitment/training costs, and enhancing team productivity. The aim is to empower HR departments with data-driven insights for better strategic decision-making.

---

## 🎯 Objective

To develop a Logistic Regression model that predicts whether an employee will stay or leave the company based on various personal, professional, and performance-related features.

---

## 🗂️ Project Structure

```bash
.
├── Employee_data.csv                  # Raw employee dataset
├── Predicting_Employee_Retention_Starter.ipynb   # Jupyter notebook with code
├── Predicting Employee Retention Report.pdf       # Full project report
└── README.md                          # Project overview and documentation
```

---

## 📂 Dataset Details

- **Records**: 74,610 employees  
- **Features**: 24 (after cleaning)  
- **Domains**: Demographics, income, satisfaction, job level, performance, etc.

### Preprocessing Steps
- Removed missing/inconsistent rows
- Dropped redundant columns (e.g., `Employee ID`, `Overtime`)
- Filtered outliers in `Number of Dependents` and `Monthly Income`
- Performed a 70:30 train-test split

---

## ⚙️ Model Used

- **Model Type**: Logistic Regression (binary classification)
- **Feature Selection**: Recursive Feature Elimination (RFE)
- **Key Features**:  
  - `Job Satisfaction`  
  - `Monthly Income`  
  - `Age`  
  - `Work-Life Balance`

---

## 📈 Evaluation Metrics

- **Training Accuracy**: 85%  
- **Test Accuracy**: 83%  
- **Precision**: 72%  
- **Recall (Sensitivity)**: 73%  
- **Specificity**: 70%  
- **Confusion Matrix**: Balanced performance in detecting both retained and non-retained employees  
- **ROC Curve**: Evaluated trade-offs between TPR and FPR

---

## 🔍 Analysis Highlights

- High attrition among employees with <3 years of experience
- Younger employees (ages 25–35) are more likely to leave
- Compensation dissatisfaction is a major factor
- Poor work-life balance correlates with attrition
- Emotional engagement plays a critical role

---

## 🧠 Key Insights

- Predictive features help in proactively managing attrition risk
- Model provides interpretable and actionable outputs for HR policies

---

## 🚀 Future Enhancements

- Implement advanced models like **Random Forest** and **Neural Networks**
- Include **time-series** analysis to detect trends
- Apply **sentiment analysis** for qualitative inputs
- Use **cross-validation** for more robust performance evaluation

---

## 📋 Author & License

**Author**: [Your Name]  
**License**: [Choose a license, e.g., MIT]
