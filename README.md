
# American House Prices Prediction Using Machine Learning

This project aims to predict house prices in the United States using various machine learning techniques. It involves detailed exploratory data analysis (EDA), visualizations, and the application of machine learning models for price prediction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Project](#how-to-run-the-project)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The primary objective of this project is to predict house prices based on several key features such as the number of bedrooms, bathrooms, and location. The project uses machine learning models and extensive EDA to understand the underlying patterns in the data.

## Dataset

The dataset used for this project contains information about house listings in the United States, including the following key features:
- Number of Bedrooms (`Beds`)
- Price (`Price`)
- Number of Bathrooms (`Baths`)
- Living Area Size (`Living Area`), etc.

## Project Structure

The project is organized as follows:

1. **Data Loading**: 
   The dataset is loaded using `pandas.read_csv()`, and basic information about the data (shape, column names, data types) is displayed using `df.info()`, `df.columns`, and `df.describe()`.

2. **Exploratory Data Analysis (EDA)**: 
   Various EDA techniques, including scatter plots, were used to explore relationships between variables like `Beds` and `Price`.

3. **Data Visualization**: 
   Visualization tools like `matplotlib` and `seaborn` were used to create plots for understanding the distribution of features.

4. **Modeling**:
   Different machine learning algorithms were employed to predict house prices. The project evaluates the models based on performance metrics like RMSE, R-squared, etc.

## Features

- **Data Preprocessing**: Handling missing values, removing duplicates, and data cleaning.
- **Exploratory Data Analysis (EDA)**: In-depth exploration of data distribution and relationships between features.
- **Data Visualization**: Scatter plots and histograms to visualize the correlation between house attributes and their prices.
- **Model Training**: Different machine learning models were tested, such as Linear Regression, Random Forest, and Gradient Boosting.

## Technologies Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/sarveshdesai/american-house-prices-prediction.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd american-house-prices-prediction
   ```
   
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook American_House_Prices_Prediction_ML.ipynb
   ```

5. Execute the cells in the notebook to see the EDA and machine learning model results.

## Results

The project concludes by showing the predicted house prices based on the trained machine learning models. Model performance is evaluated based on various metrics, including the RMSE and R-squared values.

## Contributing

Contributions are welcome! If you'd like to improve the project or fix any issues, feel free to submit a pull request or raise an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
