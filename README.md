# E-Commerce Discount Prediction

This project demonstrates Regression techniques in Machine Learning using an E-commerce dataset. The goal is to create models that predict the optimum discount percentage for a product based on various factors.

## Business Problem

The aim is to understand and model the relationship between product features and the discount percentage that can be offered to customers. This can help e-commerce platforms optimize their pricing strategies and maximize sales/conversions.

## Dataset

The dataset contains sales data from an e-commerce aggregator with the following variables:

### Independent Variables
- **User ID**: Unique identifier for each user
- **Product ID**: Unique identifier for each product
- **Category**: Product category
- **Price**: Maximum Retail Price (MRP)
- **Final Price**: Price after discount
- **Payment Method**: Type of payment (e.g., credit card, net banking)

### Dependent Variable
- **Discount**: Discount offered (in percentage)

## Approach

Multiple regression models are explored and implemented, including:
- **Linear Regression**
- **Polynomial Regression**
- **Ridge Regression**
- **Lasso Regression**
- **ElasticNet Regression**

Each model is developed in its respective Jupyter Notebook:
- [`E-commerce Dataset (Linear Regression).ipynb`](E-commerce%20Dataset%20(Linear%20Regression).ipynb)
- [`E-commerce Dataset (Polynomial Regression).ipynb`](E-commerce%20Dataset%20(Polynomial%20Regression).ipynb)
- [`E-commerce Dataset (Ridge Regression).ipynb`](E-commerce%20Dataset%20(Ridge%20Regression).ipynb)
- [`E-commerce Dataset (Lasso Regression).ipynb`](E-commerce%20Dataset%20(Lasso%20Regression).ipynb)
- [`E-commerce Dataset (ElasticNet Regression).ipynb`](E-commerce%20Dataset%20(ElasticNet%20Regression).ipynb)
- The cleaned dataset is located in [`E-commerce Dataset (Cleaned).ipynb`](E-commerce%20Dataset%20(Cleaned).ipynb)

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/shantanu056/E-Commerce-Discount-Prediction.git
    ```
2. Open the notebooks using Jupyter Notebook or JupyterLab.
3. Make sure you have the following Python libraries installed:
    - numpy
    - pandas
    - matplotlib
    - seaborn
    - scikit-learn

4. Run each notebook to explore data cleaning, feature engineering, model training, and evaluation.

## Results

- Each regression technique is evaluated for its ability to predict discounts using metrics such as RMSE, R^2 Score, etc. Model comparison helps identify the best approach for this regression task.
- The Polynomial(Non-Linear) Regression model turns out to be the best Regression Fit for the given dataset.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or suggestions.

## License

This project is licensed under the MIT License.

---

> **Note:** Only files found in recent code search are listed above. For a full list of files and details, visit the [repository on GitHub](https://github.com/shantanu056/E-Commerce-Discount-Prediction).
