# Crop Recommendation System

## Overview
This repository contains a Crop Recommendation System that suggests the best crop to cultivate based on soil and environmental parameters. The model is built using machine learning techniques and trained on a dataset of various soil properties and crop yields.

## Files in the Repository

- **Crop_recommendation.csv**: The dataset containing soil parameters and corresponding crop recommendations.
- **Crop_recommendation.xls**: Excel version of the dataset.
- **crop_recommendation.ipynb**: Jupyter Notebook implementing the machine learning model for crop recommendation.
- **model.pkl**: Trained machine learning model saved in pickle format.
- **minmaxscaler.pkl**: MinMaxScaler used for data normalization.
- **standscaler.pkl**: StandardScaler used for data standardization.

## Installation and Usage

### Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- Jupyter Notebook
- Required Python libraries: `numpy`, `pandas`, `scikit-learn`, `pickle`, `matplotlib`, `seaborn`

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/crop-recommendation.git
   cd crop-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the `crop_recommendation.ipynb` file.

## Model and Methodology
- The dataset contains soil parameters like Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.
- The model is trained using machine learning techniques such as Decision Trees, Random Forest, or SVM.
- Data preprocessing includes feature scaling using MinMaxScaler and StandardScaler.
- The trained model is saved as `model.pkl` for future use.

## How to Use
- Provide input values for soil and environmental parameters.
- The model predicts the most suitable crop for the given conditions.

## Contribution
Feel free to contribute by creating pull requests. You can improve the model, dataset, or add new features.

## License
This project is open-source and available under the MIT License.

## Contact
For any issues or suggestions, please open an issue or reach out at arevanth27@gmai.com.

