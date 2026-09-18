# FinRisk 📈

FinRisk is a comprehensive machine learning and data analysis project designed to assess and predict financial risk. It leverages historical data, exploratory data analysis (EDA), and advanced machine learning models (such as XGBoost) to extract insights and evaluate potential financial defaults or risks.

## 🚀 Features

- **Data Extraction**: Connects seamlessly to a MySQL database to extract financial data (`connect_to_sql.ipynb`).
- **Exploratory Data Analysis (EDA)**: In-depth statistical analysis and visualizations to understand the dataset (`eda.ipynb`).
- **Data Cleaning & Feature Engineering**: Robust pipelines for missing value imputation, outlier handling, and creating predictive features (`data_cleaning and feature_engineering.ipynb`).
- **Model Training**: Implementation of machine learning models (e.g., XGBoost, scikit-learn) with hyperparameter tuning (`modelTraing.ipynb`).
- **Model Evaluation**: Comprehensive evaluation using SHAP values and performance metrics to ensure model interpretability and accuracy (`modelEvaluation.ipynb`).
- **Model Deployment & Testing**: Scripts for testing saved models and preparing for deployment via Streamlit (`test_saved_model.ipynb`).

## 🛠️ Technology Stack

- **Data Manipulation & Analysis**: `pandas`, `numpy`
- **Machine Learning**: `scikit-learn`, `xgboost`
- **Model Interpretability**: `shap`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Database Connectivity**: `sqlalchemy`, `mysql-connector-python`
- **Web App / UI**: `streamlit`
- **Testing & Environment Management**: `pytest`, `python-dotenv`, `joblib`

## 📁 Project Structure

```text
finrisk/
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter Notebooks for EDA, ML, and Analysis
│   ├── connect_to_sql.ipynb
│   ├── eda.ipynb
│   ├── data_cleaning and feature_engineering.ipynb
│   ├── modelTraing.ipynb
│   ├── modelEvaluation.ipynb
│   └── test_saved_model.ipynb
├── reports/               # Generated reports and figures
├── .env.example           # Example environment variables file
├── ml_data_1.ipynb        # Additional data pipeline notebook
└── requirements.txt       # Project dependencies
```

## ⚙️ Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankitabehera777/finrisk.git
   cd finrisk
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Configuration:**
   Create a `.env` file from the example to configure your database credentials (if any):
   ```bash
   cp .env.example .env
   ```

## 📊 Usage

Navigate to the project directory and open Jupyter Notebook or JupyterLab to interact with the project step-by-step:

```bash
jupyter notebook
```
Follow the sequential flow of notebooks from `notebooks/connect_to_sql.ipynb` down to model evaluation.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request if you want to contribute.
