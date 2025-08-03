# Food Delivery ETA Prediction: Analysis Visualization and Modeling

This repository provides an end-to-end data science project focused on predicting the **Estimated Time of Arrival (ETA)** for food deliveries. It covers the entire pipeline from in-depth exploratory data analysis (EDA) and feature engineering to building and evaluating a predictive regression model.

-----

## 💡 Key Features

  * **Comprehensive EDA:** Deep dives into data distributions, missing values, and analysis of categorical and numerical features.
  * **Advanced Visualizations:** Geospatial mapping of delivery routes, statistical plots, and interactive charts to uncover insights.
  * **Robust Feature Engineering:** Creation of new features like haversine distance from coordinates, extraction of temporal data (hour, day of the week), and intelligent encoding of categorical variables.
  * **Predictive Modeling:** Implementation of a Random Forest Regressor to predict delivery times with detailed performance evaluation using metrics like **RMSE**, **MAE**, and **$R^2$**.
  * **Modular & Reproducible:** The entire workflow is organized into separate Jupyter notebooks for clarity and ease of reproduction.

-----

## 🛠️ Technology Stack

  * **Data Manipulation & Analysis:** `pandas`, `numpy`
  * **Data Visualization:** `matplotlib`, `seaborn`, `plotly`
  * **Geospatial Calculations:** `geopy`
  * **Machine Learning:** `scikit-learn`

-----

## ⚡️ Getting Started

Follow these steps to set up the project locally.

### 1\. Clone the Repository

```bash
git clone https://github.com/deep-khimani/Food-Delivery-ETA-Prediction-Analysis-Visualization-and-Modeling.git
cd "Food Delivery Analysis"
```

### 2\. Download the Dataset

This project uses the [Food Delivery Dataset from Kaggle](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset)

1.  Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset).
2.  Download `train.csv`, `test.csv`, and `Sample_Submission.csv`.
3.  Place the downloaded files into the `dataset/` directory.

### 3\. Install Dependencies

Install all the required Python packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn geopy plotly 
```

### 4\. Run the Analysis

The project is organized into three main notebooks. It's recommended to run them in order:

  * **`01_deeper_eda.ipynb`:** Start here for initial data inspection and exploratory analysis.
  * **`02_delivery_time_analysis.ipynb`:** Dive into feature engineering and advanced visualizations.
  * **`03_modeling.ipynb`:** Build, train, and evaluate the prediction model.

-----

## 📊 Notebook Workflow & Outputs

Each notebook is self-contained and includes all necessary code, explanations, and visualizations.

  * **Notebook 01 (`deeper_eda`)** focuses on understanding the raw data's structure and identifying patterns.
  * **Notebook 02 (`delivery_time_analysis`)** cleans the data, engineers critical features like route distance, and creates insightful plots.
  * **Notebook 03 (`modeling`)** contains the complete machine learning pipeline, from data preparation to model evaluation and interpretation of the results.

All outputs, including charts and performance metrics, are generated and displayed inline within the Jupyter notebooks.

-----

## 🙏 Acknowledgments

  * The project relies on the excellent [Food Delivery Dataset](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset) shared by Gaurav Malik on Kaggle.
  * A big thank you to the open-source community for developing the powerful data science libraries used in this analysis.
