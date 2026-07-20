# 🏥 Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

Healthcare insurance companies must accurately estimate the expected medical expenses of customers before issuing an insurance policy. Incorrect estimation can lead to financial losses due to underpriced premiums or reduced competitiveness due to overpriced premiums.

This project develops an end-to-end Machine Learning regression model to predict individual medical insurance charges based on customer demographic and health-related information. The project includes comprehensive exploratory data analysis, feature engineering, preprocessing, model comparison, hyperparameter tuning, and business-driven insights to identify the most suitable model for insurance cost prediction.

---

## 🎯 Business Problem

Insurance providers need to estimate future medical expenses to determine appropriate insurance premiums and manage financial risk.

The objective of this project is to build a predictive model that estimates medical insurance charges using customer information such as:

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Residential Region

---

## 📊 Dataset Information

- **Domain:** Finance / Insurance
- **Dataset:** Insurance Cost Prediction
- **Rows:** 1338
- **Features:** 7 Input Features + 1 Target Variable

### Input Features

| Feature | Description |
|----------|-------------|
| Age | Age of the policyholder |
| Sex | Gender of the customer |
| BMI | Body Mass Index |
| Children | Number of dependents covered |
| Smoker | Smoking status |
| Region | Residential region |

### Target Variable

- **Charges** – Individual medical insurance expenses billed by the insurance company.

---

# 🚀 Project Workflow

```
Business Understanding
        │
        ▼
Data Collection
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
        │
        ▼
Final Model Selection
```

---

# 🔍 Exploratory Data Analysis

The project performs detailed EDA including:

- Dataset overview
- Missing value analysis
- Duplicate record analysis
- Distribution analysis
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Outlier detection
- Business insights

Visualizations include:

- Histograms
- KDE plots
- Count plots
- Box plots
- Scatter plots
- Correlation heatmap
- Pair plots

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Missing value verification
- Duplicate removal
- Binary encoding
- One-Hot Encoding
- Feature Engineering
- Feature Scaling
- Train-Test Split

### Engineered Features

- Smoker × BMI
- Smoker × Age

These interaction features help capture the combined effect of smoking and health indicators on insurance charges.

---

# 🤖 Machine Learning Models

Multiple regression algorithms were trained and evaluated.

### Linear Models

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet

### Non-Linear Models

- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

# 🎯 Hyperparameter Tuning

GridSearchCV was used to optimize the best-performing models.

Models tuned include:

- Random Forest
- XGBoost

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

Cross-validation was also performed to evaluate model generalization.

---

# 📊 Business Insights

The analysis revealed several important findings:

- Smoking status is the strongest predictor of insurance charges.
- Higher BMI values generally lead to increased medical expenses.
- Older individuals tend to incur higher insurance costs.
- The combined effect of smoking and obesity significantly increases healthcare expenses.
- Region has comparatively less influence on insurance charges.

---

# 🏆 Best Performing Model

After comparing multiple machine learning algorithms, the best-performing model was selected based on predictive accuracy and generalization performance.

Evaluation considered:

- Highest R² Score
- Lowest RMSE
- Lowest MAE
- Cross-validation performance
- Model robustness

---

# 💼 Business Value

This solution can assist insurance companies by:

- Estimating expected healthcare expenses
- Supporting premium pricing decisions
- Identifying high-risk customers
- Improving underwriting efficiency
- Reducing financial risk
- Assisting data-driven decision making

---

# 🛠️ Technologies Used

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn
- XGBoost

### Model Persistence

- Joblib

### Development Environment

- Jupyter Notebook

---

# 📁 Project Structure

```
Insurance-Cost-Prediction/

│── data/
│      insurance.csv

│── notebooks/
│      Insurance_Cost_Prediction.ipynb

│── models/
│      best_model.pkl

│── images/

│── README.md

│── requirements.txt
```

---

# 📌 Future Improvements

Future enhancements include:

- SHAP Explainability
- LIME Explainability
- Customer Risk Segmentation
- Premium Recommendation Engine
- What-if Scenario Analysis
- Fairness Analysis
- Data Drift Detection
- Streamlit Dashboard
- FastAPI Deployment
- MLOps Integration
- Model Monitoring

---

# 📖 Key Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end Machine Learning workflow
- Exploratory Data Analysis
- Feature Engineering
- Regression Modeling
- Hyperparameter Optimization
- Model Evaluation
- Business-oriented Data Analysis
- Insurance Domain Understanding

---

# 👨‍💻 Author

**Karnulu Suresh**

AI Engineer | Machine Learning | Data Science

GitHub:https://github.com/karnulusuresh

LinkedIn: https://www.linkedin.com/in/karnulu-suresh-117139316/
