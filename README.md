# Heart Disease Predictor

## Project Overview
The Heart Disease Predictor is a machine learning project that aims to predict the presence of heart disease in patients based on various health metrics. This project utilizes several machine learning algorithms and statistical analysis techniques to achieve accurate predictions.

## Features
- Predicts heart disease presence based on user input data.
- Supports multiple machine learning models including Logistic Regression, Decision Trees, and Random Forests.
- User-friendly interface for data input and result visualization.
- Comprehensive data preprocessing steps, including normalization and feature selection.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Maheeshasamarasinhe/heart-disease-predictor.git
   cd heart-disease-predictor
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your input data according to the input format specified in the project.
2. Run the main application script:
   ```bash
   python app.py
   ```
3. Follow the on-screen instructions to input your data and receive predictions.

## File Structure
```
heart-disease-predictor/
│
├── app.py               # Main application script
├── model.py             # Contains model definitions and training logic
├── requirements.txt     # Required packages and dependencies
├── data/                # Directory for datasets
│   └── heart_data.csv   # Sample dataset used for prediction
├── src/                 # Source codes including training and testing scripts
│   └── train.py         # Script to train models on the dataset
└── README.md            # Documentation about the project
```

## License
This project is licensed under the MIT License.