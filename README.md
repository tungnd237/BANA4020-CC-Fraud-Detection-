# Credit Card Fraud Detection Project

This project aims to detect credit card fraud using various machine learning models. The goal is to identify fraudulent transactions effectively and minimize false positives by comparing the performance of different models under multiple scenarios.

## Project Structure

The project consists of four Jupyter Notebook files:

1. **EDA_and_Predict_without_handle_imbalance.ipynb**: 
   - Performs Exploratory Data Analysis (EDA) and initial prediction without handling class imbalance.
   - Provides insights into the dataset and sets a baseline performance for the models.

2. **Oversampling.ipynb**: 
   - Implements oversampling techniques to address class imbalance.
   - Evaluates the performance of models with oversampled data to improve the detection of fraudulent transactions.

3. **Predict_without_handle_imbalance.ipynb**: 
   - Focuses on model prediction without applying any resampling techniques to handle class imbalance.
   - Serves as a comparison to understand the impact of not addressing class imbalance.
   - This is just part of the first file, without the EDA.

4. **Undersampling.ipynb**: 
   - Applies undersampling techniques to balance the dataset.
   - Assesses the performance of models with undersampled data, aiming to mitigate the class imbalance issue.

## How to Run the Code

Running the code is straightforward. Simply execute each notebook in the following order:

1. Start with `EDA_and_Predict_without_handle_imbalance.ipynb` to understand the dataset and establish a baseline performance.
2. Proceed with `Predict_without_handle_imbalance.ipynb` to compare the initial model performance.
3. Run `Oversampling.ipynb` to apply oversampling techniques and evaluate model improvements.
4. Finally, run `Undersampling.ipynb` to apply undersampling techniques and compare results.

Each notebook is designed to be run sequentially, and outputs are generated within the notebooks. Ensure you have the necessary Python libraries installed to execute the code.

## Requirements

To run these notebooks, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- catboost
- lightgbm

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn catboost lightgbm
