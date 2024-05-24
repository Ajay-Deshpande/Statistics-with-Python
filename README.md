# Ames Housing Dataset Analysis

## Overview

This project aims to analyze the Ames Housing Dataset, a dataset containing information about residential properties in Ames, Iowa. The dataset includes various features such as the sale price, lot size, number of bedrooms, and more. The analysis involves data cleaning, exploratory data analysis (EDA), and building predictive models to understand factors influencing housing prices.

## Dataset

The Ames Housing Dataset consists of a CSV file named `AmesHousing.csv`. It contains information about 2930 properties and includes 82 columns describing different aspects of each property.

## Project Structure

- **Data Preprocessing**: The `clean_housing_no_na` function is used to clean the dataset by handling missing values and converting categorical variables into a suitable format for analysis.
- **Exploratory Data Analysis (EDA)**: Various visualizations and statistical analyses are performed to understand the relationships between different features and the target variable (sale price). This includes histograms, scatter plots, correlation analysis, and hypothesis testing.
- **Model Building**: Linear regression and XGBoost regression models are trained to predict housing prices based on the available features. Feature selection and feature engineering techniques are applied to improve model performance.

## Requirements

To run the analysis, you need Python installed along with the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `scikit-learn`
- `xgboost`

You can install these dependencies using `pip`:

```bash
pip install numpy pandas matplotlib scipy scikit-learn xgboost
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/ames-housing-analysis.git
```

2. Navigate to the project directory:

```bash
cd ames-housing-analysis
```

3. Run the Jupyter notebooks to execute the analysis:

```bash
jupyter notebook
```

4. Follow the instructions provided in the notebooks to clean the data, perform exploratory analysis, and build predictive models.
