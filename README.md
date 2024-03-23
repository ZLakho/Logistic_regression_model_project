# Customer Purchase Prediction Model

This repository contains code for a predictive model that forecasts customer purchase behavior in e-commerce based on demographic and behavioral data.

## Overview

In today's competitive e-commerce landscape, understanding customer behavior is crucial for businesses to optimize their marketing strategies and increase sales. This predictive model aims to provide insights into whether a customer is likely to purchase high-value products, thereby enabling companies to target potential customers more effectively.

## Features

- **Data**: The model utilizes customer data such as age, time spent on the website, and whether items were added to the cart.
- **Machine Learning**: Implemented using logistic regression algorithm from scikit-learn library in Python.
- **Accuracy**: The model achieves an accuracy score of 100% on the provided dataset.

## Usage

### Installation:

- Clone the repository:
  ```bash
  git clone https://github.com/ZLakho/Logistic_regression_model_project.git
  ```
- Install the required Python packages:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Model:

- Run the Jupyter notebook `customer_purchase_prediction.ipynb` to train and evaluate the model.

### Deployment:

- Once trained and tested, the model can be deployed in production environments to make real-time predictions.

## Dataset

The dataset used for training and evaluation is included in the repository as `customer_data.csv`. It contains the following columns:

- `Age`: Age of the customer
- `Hours`: Time spent on the website (in hours)
- `add_or_not`: Binary variable indicating whether items were added to the cart (1 for yes, 0 for no)

## Contributors

Zainab Lakho

## License

This project is licensed under the MIT License.
