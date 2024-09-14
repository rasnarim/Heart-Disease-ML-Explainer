# Heart-Disease-ML-Explainer

## Project Overview
This project uses machine learning models to predict the presence of heart disease and explains the model’s predictions with SHAP (SHapley Additive exPlanations). The dataset contains various medical and diagnostic features, and models like Logistic Regression and Random Forest are employed to identify the key factors contributing to heart disease predictions.

## Features
- **Exploratory Data Analysis (EDA)**: Data visualization and summary statistics to understand the dataset.
- **Machine Learning Models**: Logistic Regression and Random Forest for heart disease prediction.
- **SHAP Explanations**: SHAP-based visualizations for both global and local interpretability of the model predictions.
  
## Dataset
The dataset used for this project contains several features, such as age, cholesterol levels, maximum heart rate, and other medical diagnostics. It is used to predict the target variable indicating the presence (1) or absence (0) of heart disease.

Source: [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)

## Usage
To use the code in this repository:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Heart-Disease-ML-Explainer.git
    cd Heart-Disease-ML-Explainer
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the analysis:
    - Exploratory Data Analysis (EDA)
    - Model training (Logistic Regression, Random Forest)
    - SHAP visualizations for model interpretability

## Results
- **Feature Importance**: Identified key medical features such as max heart rate, cholesterol levels, and age as important factors.
- **Model Interpretability**: SHAP summary plots and force plots illustrate how individual features influence predictions.

## Contributing
Feel free to submit issues or pull requests. Contributions are welcome to enhance the model or improve the interpretability features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
