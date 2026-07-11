# softnexis-tasks
# Data Analysis Project

## Project Overview

This project demonstrates the complete data analysis workflow using Python and popular data science libraries. It consists of three tasks:

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Time Series Analysis & Forecasting

The project uses publicly available Kaggle datasets.

---

# Datasets

## Task 1: Sales Data

Dataset:
Sample Sales Data

Download:
https://www.kaggle.com/datasets/kyanyoga/sample-sales-data

File Used:
sales_data_sample.csv

---

## Task 2: Titanic Dataset

Dataset:
Titanic Dataset

Download:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

File Used:
Titanic-Dataset.csv

---

## Task 3: Air Passengers Dataset

Dataset:
Air Passengers (1949–1960)

Download:
https://www.kaggle.com/datasets/chirag19/air-passengers

File Used:
AirPassengers.csv

---

# Project Structure

```
Project/
│
├── data/
│   ├── sales_data_sample.csv
│   ├── Titanic-Dataset.csv
│   └── AirPassengers.csv
│
├── Task1_DataCleaning.ipynb
├── Task2_EDA.ipynb
├── Task3_TimeSeries.ipynb
│
├── cleaned_sales_data.csv
│
└── README.md
```

---

# Requirements

Install Python 3.9 or above.

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels
```

or

```bash
pip install -r requirements.txt
```

---

# Required Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- statsmodels

---

# How to Run the Project

## Step 1

Download all three datasets from Kaggle.

Place them inside the project folder.

Example:

```
Project/
    sales_data_sample.csv
    Titanic-Dataset.csv
    AirPassengers.csv
```

---

## Step 2

Open Jupyter Notebook.

```bash
jupyter notebook
```

or open the notebooks in VS Code.

---

## Step 3

Run each notebook from top to bottom.

Run in this order:

1. Task1_DataCleaning.ipynb
2. Task2_EDA.ipynb
3. Task3_TimeSeries.ipynb

---

# Task 1 – Data Cleaning & Preprocessing

Performed the following operations:

- Loaded CSV dataset
- Initial data inspection
- Missing value handling
- Duplicate removal
- Column management
- Data type correction
- Format standardization
- Invalid value removal
- Exported cleaned dataset

Output:

```
cleaned_sales_data.csv
```

---

# Task 2 – Exploratory Data Analysis

Performed:

- Dataset overview
- Summary statistics
- Missing value treatment
- Distribution analysis
- Correlation analysis
- Outlier detection
- Pairplot visualization
- FacetGrid visualization
- Business insights

Visualizations include:

- Histogram
- Boxplot
- Countplot
- Heatmap
- Pairplot
- FacetGrid

---

# Task 3 – Time Series Analysis

Performed:

- Time series visualization
- Trend decomposition
- Seasonality analysis
- Moving averages
- SARIMA forecasting
- RMSE calculation
- Forecast visualization
- Business insights

Model Used:

SARIMAX

Reason:

The Air Passengers dataset contains strong yearly seasonality, making SARIMAX more suitable than ARIMA.

---

# Expected Outputs

Task 1

- Cleaned sales dataset
- Summary statistics
- Missing value report

Task 2

- Histogram
- Boxplot
- Heatmap
- Pairplot
- FacetGrid
- Correlation analysis

Task 3

- Original time series plot
- Trend decomposition
- Moving average plot
- SARIMA forecast
- RMSE value

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

# Conclusion

This project demonstrates the complete workflow of data preprocessing, exploratory data analysis, and time series forecasting using real-world datasets from Kaggle. It highlights essential data science techniques such as data cleaning, visualization, statistical analysis, and forecasting using the SARIMAX model.
