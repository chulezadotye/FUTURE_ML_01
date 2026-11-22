# FUTURE_ML_01 – Sales and Demand Forecasting Using Machine Learning

## Project Overview

This project was completed as part of **Future Interns Machine Learning Task 1 (2026)**.

The aim of this project is to develop a machine learning system that analyses historical business sales data and predicts future sales. The project demonstrates how machine learning can help businesses make informed decisions about inventory management, financial planning and resource allocation.

Two machine learning algorithms, Linear Regression and Random Forest Regression, were implemented and compared to identify the better-performing forecasting model.

## Project Objectives

- Clean and prepare historical sales data.
- Analyse historical sales trends and seasonal patterns.
- Create time-based features for forecasting.
- Develop machine learning regression models.
- Evaluate and compare model performance.
- Generate future monthly sales predictions.
- Visualise sales trends and future forecasts.
- Explain how forecasting can support business decisions.

## Dataset

**Dataset:** Superstore Sales Dataset

**Source:** [Kaggle – Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

Dataset information:

- Total records: 9,994
- Original columns: 21
- Historical period: 2014–2017
- Total sales: 2,297,200.86
- Missing values: None
- Duplicate records: None

The dataset contains information about orders, customers, products, sales, quantities, discounts and profits.

## Technologies and Libraries

The project was developed using Python in Google Colab.

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development environment |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Scikit-learn | Machine learning and model evaluation |

## Project Methodology

The project followed these main stages:

1. **Data Loading:** Imported the Superstore dataset into Google Colab.
2. **Data Preprocessing:** Checked missing values, duplicate records and data types.
3. **Exploratory Data Analysis:** Analysed monthly sales, yearly sales and seasonal patterns.
4. **Feature Engineering:** Created year, month, lag features and a three-month rolling mean.
5. **Model Development:** Trained Linear Regression and Random Forest Regression models.
6. **Model Evaluation:** Compared the models using MAE, RMSE and R².
7. **Future Forecasting:** Used the selected model to predict six future months of sales.
8. **Visualisation:** Created graphs to communicate historical sales patterns and future predictions.

## Machine Learning Models

The following models were implemented:

### 1. Linear Regression

Linear Regression was used to model the relationship between historical sales features and monthly sales.

### 2. Random Forest Regression

Random Forest Regression was used as a second model to capture potentially more complex relationships in the sales data.

## Model Evaluation Results

The models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) and R-squared (R²).

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 9,972.240 | 14,552.743 | 0.660 |
| Random Forest | 14,198.662 | 18,360.514 | 0.459 |

### Best Performing Model

**Linear Regression** performed better on the test dataset.

It achieved lower MAE and RMSE values and a higher R² score than Random Forest.

The model was therefore selected to generate the future sales forecasts.

## Future Sales Forecast

The selected Linear Regression model was used to predict sales for six months beyond the historical dataset.

| Month | Predicted Sales |
|---|---:|
| January 2018 | 38,826.37 |
| February 2018 | 50,127.60 |
| March 2018 | 49,876.12 |
| April 2018 | 50,459.95 |
| May 2018 | 56,884.42 |
| June 2018 | 61,746.51 |

The predictions show a generally increasing sales trend from January to June 2018.

**Note:** These are historical out-of-sample forecasts based on data ending in December 2017. They are not current 2026 sales predictions.

## Business Applications

The forecasting system demonstrates how businesses can use machine learning to:

- Estimate future sales and prepare inventory.
- Plan budgets and manage cash flow.
- Prepare staffing levels for expected demand.
- Identify sales trends and seasonal patterns.
- Support better business planning and decision-making.

## Project Files

The repository contains the following project deliverables:

- `Sales_and_Demand_Forecasting.ipynb` – Complete Python implementation and experiments.
- `Final_Project_Report` – Project report documenting the methodology, results and conclusions.
- `Future_Sales_Forecast.csv` – Exported future sales predictions.

## How to Run the Project

1. Clone or download this GitHub repository.
2. Open the `.ipynb` notebook using Google Colab or Jupyter Notebook.
3. Download the Superstore dataset from the Kaggle link provided above.
4. Upload the dataset when prompted by the notebook.
5. Run the notebook cells in order to reproduce the analysis, model training, evaluation and forecasting.

## Conclusion

This project demonstrates the practical application of machine learning in business sales forecasting.

Linear Regression achieved better test performance than Random Forest in this experiment. The selected model was used to generate six monthly sales predictions.

The project highlights how historical business data and machine learning techniques can support inventory planning, financial management and business decision-making.

## Author

**Chuleza Dotye**

Future Interns – Machine Learning Task 1 (2026)

**Project:** Sales and Demand Forecasting for Businesses

---

*Developed using Python, Google Colab, Pandas, NumPy, Matplotlib and Scikit-learn.*
