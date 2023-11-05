# Future-Sales-Prediction


# Sales Prediction with Linear Regression and Decision Tree Regressor

This repository contains Python code for predicting sales using two different regression models: Linear Regression and Decision Tree Regressor. The code is accompanied by a sample dataset, and the README provides instructions on how to run the code and any dependencies.

## Dependencies

Before running the code, you need to ensure that you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib

You can install these dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## How to Run

1. Clone this repository or download the code files.

2. Open a Jupyter Notebook or Python environment (e.g., Jupyter Notebook, Google Colab) that supports the required libraries.

3. Upload the 'Sales.csv' dataset to the same directory as the code files. If you're using Google Colab, you can upload the file using the provided code snippet.

4. Open the Jupyter Notebook or Python script containing the code.

5. Run the code cells in the notebook or the script. The code includes the following main steps:

    a. Load the dataset and split it into features (X) and target (y).

    b. Split the data into training and testing sets using a 80/20 split ratio.

    c. Train a Linear Regression model and a Decision Tree Regressor on the training data.

    d. Make predictions using both models on the testing data.

    e. Calculate and print various regression metrics such as RMSE, MAE, and R-squared for both models.

    f. Plot a scatter graph to visualize the actual sales, Linear Regression predictions, and Decision Tree Regressor predictions against the TV advertising spending.

6. After running the code, you should see the evaluation metrics and the sales prediction plot.

## Customization

You can customize the code by replacing the 'Sales.csv' dataset with your own data or modifying the machine learning models, their parameters, and visualization.

