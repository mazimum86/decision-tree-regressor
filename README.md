# Decision Tree Regressor

This repository contains an implementation of the Decision Tree Regressor algorithm. The Decision Tree Regressor is a popular machine learning model used for predicting continuous values based on input features. It builds a tree structure where each node represents a decision based on the features, and the leaves represent the predicted continuous values.

## Dataset

The dataset used in this implementation is suitable for regression tasks. It contains features that can be used to predict a continuous target variable.

## Contents

- **decision_tree_regressor.py**: The main script that implements the Decision Tree Regressor, including data preprocessing, model training, and prediction.
- **data.csv**: The dataset file used for training and testing the model.
- **requirements.txt**: A list of Python dependencies required to run the code.

## Implementation Details

The implementation follows these steps:

1. **Data Loading**: The dataset is loaded from `data.csv` and split into features and target variables.
2. **Data Preprocessing**: Necessary preprocessing steps, such as handling missing values and feature scaling, are applied.
3. **Model Training**: The Decision Tree Regressor model is trained using the preprocessed data.
4. **Prediction**: The trained model is used to predict continuous values on the test dataset.
5. **Evaluation**: The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared score.

## Usage

To use this code, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/mazimum86/decision-tree-regressor.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd decision-tree-regressor
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Decision Tree Regressor script:
    ```bash
    python decision_tree_regressor.py
    ```

## Dependencies

The following Python packages are required to run the code:

- pandas
- scikit-learn
- matplotlib

These dependencies are listed in the `requirements.txt` file and can be installed using `pip`.

## Results

The output includes the following:

- **Predicted Values**: The continuous values predicted by the model on the test dataset.
- **Evaluation Metrics**: Metrics such as Mean Squared Error (MSE) and R-squared score that provide insights into the model's performance.

## Contributing

Contributions are welcome! If you have any ideas for improvements or additional features, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
