# HR Analytics - Predict Employee Attrition

## Objective
The goal of this project is to leverage analytics to:
- Understand the key factors contributing to employee resignations.
- Build a predictive model to forecast future attrition.
- Visualize insights interactively using Power BI.
- Suggest actionable strategies to retain employees based on data findings.

---

## Tools & Technologies
- **Python**: For data analysis and predictive modeling  
  - Libraries: `Pandas`, `Seaborn`, `Scikit-learn`, `SHAP`
- **Power BI**: For interactive dashboard visualizations
- **Jupyter Notebook / Google Colab**: For development and experimentation

---

## Dataset
The dataset includes 250 employee records with the following columns:

- `Age`, `Gender`, `Department`, `Years at Company`, `Job Role`, `Salary Band`
- `Marital Status`, `Training Hours`, `Job Satisfaction`, `Work-Life Balance`
- `Performance Rating`, `Attrition` (Target variable)

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Department-wise attrition distribution
- Salary band trends vs. attrition
- Job satisfaction and training patterns
- Correlation matrix and outlier checks

### 2. Feature Engineering & Preprocessing
- Label encoding for categorical features
- Scaling of numerical values
- Data split into training and test sets

### 3. Predictive Modeling
- Logistic Regression and Decision Tree models were tested
- Accuracy, precision, recall, and confusion matrix evaluated
- Best-performing model selected for interpretability

### 4. SHAP Value Analysis
- Used SHAP to explain model predictions
- Identified most influential features:
  - Job Satisfaction
  - Years at Company
  - Work-Life Balance

### 5. Power BI Dashboard
- Visual elements included:
  - KPIs: Attrition Rate, Avg Job Satisfaction, Avg Training Hours
  - Charts: Donut, Bar, Column, Pie
  - Filters/Slicers: Department, Gender, Job Role
- Insightful visuals to help HR make data-driven decisions

---

## Deliverables
- Power BI Dashboard (.pbix file)
- Python notebooks (.ipynb/.py)
- Model evaluation report (accuracy + confusion matrix)
- SHAP summary plots
- PDF report with attrition prevention suggestions

---

## Key Insights
- Departments like Sales and R&D had the highest attrition rates.
- Employees with lower job satisfaction and work-life balance were more likely to leave.
- Training and promotions significantly affected retention.

