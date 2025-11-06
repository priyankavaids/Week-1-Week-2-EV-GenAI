# Week-1-EV-GenAI
Week 1 internship task - Electric Vehicle dataset preprocessing
# Week 1 Internship – Electric Vehicle (Gen AI) Domain 🚗⚡

##  Problem Statement
To analyze and prepare Electric Vehicle (EV) specifications data for further AI-based analysis.  
The goal is to collect raw EV data, clean it, and make it ready for model training or insights generation in the EV domain.

---

## Objective
- To collect a raw dataset related to Electric Vehicles.
- To perform data preprocessing and cleaning.
- To prepare the dataset for Gen AI or machine learning applications.

---

## 🧠 Domain
**Electric Vehicle (Gen AI)** — understanding EV specifications and preparing structured data to support intelligent analysis.

---

## 📂 Project Structure
Week-1-EV-GenAI/
│
├── dataset/
│ └── ev_specs_raw.csv # Original dataset downloaded from public source
│
├── cleaned_data/
│ └── ev_specs_cleaned.csv # Preprocessed dataset ready for use
│
└── 01_data_cleaning.ipynb # Google Colab notebook with cleaning steps


## Week 2 — ML Model for EV Range Prediction 

**Objective:**  
To build a machine learning model that predicts the driving range of electric vehicles based on specifications.

**Steps Completed:**
- Imported cleaned dataset from Week-1
- Trained Linear Regression, Random Forest, and XGBoost models
- Compared model performance using MAE, RMSE, and R²
- Visualized actual vs predicted EV range
- Saved best model as `ev_range_rf_model.pkl`

**Results:**
| Model | MAE | RMSE | R² |
|--------|------|------|------|
| Random Forest | *value* | *value* | *value* |

**Files Added:**
- `Week-2/02_ml_model.ipynb`
- `Week-2/ev_range_rf_model.pkl`

