# Greenhouse Gas Emission Prediction and Analysis - Shell-Edunet AICTE Internship Project

## Project Overview

This project is developed as part of the **Shell-Edunet Skills4Future AICTE Internship**, focusing on **Green Skills using AI technologies**. The core objective is to analyze and predict Greenhouse Gas (GHG) emission factors within various industrial and commodity supply chains. By developing a robust predictive model and identifying key emission drivers, this project aims to provide actionable insights that align with sustainable development goals and support a productive career in the rapidly evolving job market.

## Data Source

The primary dataset used for this project is `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`. It contains detailed emission factors for a range of commodities and industries across multiple years (2010-2016). The data includes various substances (carbon dioxide, methane, nitrous oxide, other GHGs) and associated data quality metrics.

## Key Features & Improvisations

My approach to this project involved several key enhancements and improvisations:

* **Comprehensive Data Integration:** Data from multiple Excel sheets (Commodity and Industry details) across various years (2010-2016) were combined into a single, comprehensive DataFrame for holistic analysis.
* **Automated Data Cleaning & Encoding:** Implemented robust preprocessing steps, including stripping whitespace from column names, dropping irrelevant empty columns  and programmatically converting categorical features  into numerical representations suitable for machine learning models.
* **In-depth Exploratory Data Analysis (EDA):** Performed extensive EDA, including visualizing the distribution of the target variable and identifying the top-emitting industries, which provided critical insights into the dataset.
* **Comparative Model Evaluation & Optimization:** Trained and evaluated multiple regression models (Linear Regression and Random Forest Regressor). The Random Forest model's performance was significantly optimized through hyperparameter tuning using `GridSearchCV`.
* **Reusable Model Assets:** The best-performing model (`LR_model.pkl`) and the data scaler (`scaler.pkl`) were saved using `joblib` for convenient future use and deployment.

## Technologies Used

* **Python:** Programming language
* **Pandas:** Data manipulation and analysis
* **NumPy:** Numerical operations
* **Seaborn & Matplotlib:** Data visualization
* **Scikit-learn:** Machine learning (data splitting, scaling, modeling, evaluation, hyperparameter tuning)
* **Joblib:** Model persistence
* **Openpyxl:** For reading `.xlsx` files

## Setup and Installation

To set up and run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/VarunSugandhi/varun-edunet-greenhousegas.git](https://github.com/VarunSugandhi/varun-edunet-greenhousegas.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd varun-edunet-greenhousegas
    ```
3.  **Install the required libraries:**
    It's recommended to use a virtual environment.
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn joblib openpyxl
    ```

## Usage

1.  **Download the Dataset:** Ensure the `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx` dataset is placed in your project directory.
2.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Then open `varun-shell-edunet.ipynb`.
3.  **Run the Notebook:** Execute all cells in the notebook sequentially to reproduce the data preprocessing, analysis, model training, evaluation, and saving of the model and scaler.

---
