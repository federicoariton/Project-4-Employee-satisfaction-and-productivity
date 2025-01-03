# Employee Satisfaction and Productivity Analysis

## Overview

This project focuses on enhancing employee satisfaction and productivity by analyzing a comprehensive dataset of employee information. It integrates data preparation, statistical techniques, and machine learning models to uncover actionable insights. Additionally, it explores dimensionality reduction techniques, hypothesis testing, and evaluates machine learning models for predicting employee attrition.

## Additional Resources

- More Information: For a detailed explanation of the project structure, methodologies, and findings, refer to the Full Project Report.[Full Project Report](https://github.com/federicoariton/Project-4-Employee-satisfaction-and-productivity/blob/main/Federico_Ariton_Lvl8_CA2_Integrated_Report.pdf)

---

## Objectives

1. **Identify Key Factors**:
   - Understand factors influencing employee satisfaction and productivity.
   - Detect trends in attrition and employee engagement.

2. **Dimensionality Reduction**:
   - Compare Linear Discriminant Analysis (LDA) and Principal Component Analysis (PCA) for simplifying data complexity.

3. **Hypothesis Testing**:
   - Use t-tests and ANOVA to examine relationships between variables.

4. **Predictive Modeling**:
   - Develop machine learning models to predict employee attrition and assess performance metrics.

---

## Dataset Overview

- **Attributes**:
  - Includes features like Age, Job Role, Job Satisfaction, Work Experience, Monthly Income, etc.
- **Target Variable**:
  - `Attrition`: Indicates whether an employee has left the company (`Yes` or `No`).
- **Size**:
  - Observations: 1,470 employees.
  - Features: 35 attributes.

---

## Key Features

### Data Preparation
1. **Cleaning**:
   - Removed unnecessary columns like `EmployeeNumber`, `Over18`, `StandardHours`.
   - Imputed missing values using:
     - Median for numerical columns.
     - Mode for categorical columns.

2. **Feature Engineering**:
   - Created new metrics such as `JobLevel vs. MonthlyIncome`.

3. **Scaling**:
   - Standardized numerical data to improve algorithm performance.

4. **Encoding**:
   - Transformed categorical variables using `LabelEncoder` for compatibility with machine learning models.

---

## Exploratory Data Analysis (EDA)

- **Insights**:
  - Higher attrition among single employees and those in certain roles (e.g., Sales Representatives).
  - Frequent business travel correlates with higher attrition.
  - Low job satisfaction and work-life balance are associated with attrition.

- **Visualizations**:
  - Correlation Matrix.
  - Frequency Distributions for categorical variables.
  - Box plots for satisfaction metrics.

---

## Statistical Techniques

1. **Hypothesis Testing**:
   - **ANOVA**: Examined differences in job satisfaction across departments.
   - **t-tests**: Analyzed the impact of overtime on job satisfaction.

2. **Findings**:
   - No significant difference in job satisfaction across departments.
   - Overtime did not significantly affect job satisfaction.

---

## Machine Learning

### Models Used
1. **Random Forest**:
   - Feature selection and prediction for employee attrition.
2. **Artificial Neural Networks (ANN)**:
   - Explored for complex and non-linear relationships.

### Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score.

### Findings
- Random Forest provided balanced performance.
- ANN demonstrated overfitting with lower generalization on unseen data.

---

## Dimensionality Reduction

1. **LDA**:
   - Enhanced class separation for classification tasks.
2. **PCA**:
   - Reduced dimensionality while retaining variance.

### Comparison
- PCA focuses on variance, while LDA prioritizes class separability.

---

## How to Use

1. **Setup Environment**:
   - Install dependencies:
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```

2. **Run Scripts**:
   - Execute the analysis and model training scripts.

3. **Explore Results**:
   - Visualizations and model performance metrics are generated.

---

## Key Takeaways

- Job roles, marital status, and business travel significantly influence attrition.
- Dimensionality reduction techniques improve model performance and interpretability.
- Random Forest and ANN are effective but require hyperparameter tuning for optimal results.

---

## Files

- **`analysis.py`**: Data analysis and visualizations.
- **`models.py`**: Machine learning model training and evaluation.
- **`report.pdf`**: Detailed integrated report of the project.

---

## Author

Federico Ariton  
[GitHub Profile](https://github.com/federicoariton)  
[LinkedIn Profile](https://www.linkedin.com/in/federico-ariton-090b18218/)

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
