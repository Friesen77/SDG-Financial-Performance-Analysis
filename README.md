# Corporate Sustainability Analytics: SDG Adoption and Financial Performance Analysis

This project investigates the relationship between corporate adoption of the United Nations Sustainable Development Goals (SDGs) and corporate financial performance using business analytics and machine learning techniques.

The objective is to evaluate whether SDG adoption contributes to predicting a company's **Total Revenue per Share (TRPS)** and compare its predictive power against traditional financial control variables. The project integrates data preprocessing, predictive modelling, interactive dashboard development, and web application deployment to provide both analytical and business insights.

---

## Dashboard Preview

### SDG Adoption Overview

![SDG Adoption Overview](dashboard/images/overview.jpg)

### Financial Performance

![Financial Performance](dashboard/images/financial_performance.jpg)

### Geographic Analysis

![Geographic Analysis](dashboard/images/geographic_analysis.jpg)

### Sector & Industry Analysis

![Sector & Industry Analysis](dashboard/images/sector_industry_analysis.jpg)

📄 **View the complete dashboard:** [dashboard/dashboard.pdf](dashboard/dashboard.pdf)

---

## Project Components

### 📊 Data Analytics
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data transformation

### 🤖 Machine Learning
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter tuning using RandomizedSearchCV
- Model evaluation and comparison

### 📈 Power BI Dashboard
Developed an interactive dashboard to visualize:

- SDG adoption trends
- Financial performance
- Geographic distribution
- Sector and industry comparisons

### 🖥️ Streamlit Application
Developed an interactive Streamlit application for:

- Dataset exploration
- Dashboard integration
- Model evaluation
- Revenue prediction

---

## Project Workflow

```text
Business Understanding
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Exploratory Data Analysis
        ↓
Machine Learning
        ↓
Model Evaluation
        ↓
Power BI Dashboard
        ↓
Streamlit Application
```

---

## Machine Learning Models

Three regression models were developed and evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Hyperparameter optimization was performed using **RandomizedSearchCV** with **5-fold cross-validation**.

Evaluation metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Repository Structure

```text
.
├── notebooks/
│   └── corporate_sustainability_analysis.ipynb
│
├── src/
│   └── main.py
│
├── dashboard/
│   ├── README.md
│   ├── dashboard.pdf
│   └── images/
│
├── requirements.txt
└── README.md
```

---

## Technologies Used

### Programming
- Python
- Jupyter Notebook

### Data Analysis
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- XGBoost

### Data Visualization
- Power BI
- Matplotlib
- Plotly

### Web Application
- Streamlit

---

## Key Findings

- Binary SDG adoption indicators alone demonstrated limited predictive power for predicting corporate financial performance.
- Incorporating company-specific control variables significantly improved model performance.
- XGBoost achieved the strongest predictive performance among the evaluated models.
- Traditional financial characteristics remained stronger predictors than individual SDG adoption indicators.

---

## Dataset

The original dataset is **not included** in this repository.

The data was provided for academic purposes through the **London Stock Exchange Group (LSEG) Workspace** accessed via **Sunway University**. Due to licensing and institutional access restrictions, the dataset cannot be redistributed publicly.

This repository focuses on the analytical methodology, implementation, and visualization components of the project.

---

## Installation

Clone the repository and install the required Python packages:

```bash
git clone https://github.com/<your-username>/corporate-sustainability-analytics.git

cd corporate-sustainability-analytics

pip install -r requirements.txt
```

---

## Author

**Friesen Tjou Jazernicky**

Master of Business Analytics  
Sunway University
