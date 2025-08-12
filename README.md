# Logistic Regression ONNX App

This is a simple web app built with Streamlit that loads a Logistic Regression model saved in ONNX format and predicts output based on user input features.

## Features

- Load and run inference on an ONNX model using `onnxruntime`
- User-friendly interface to input features
- Real-time prediction results displayed on the web app
- Input validation for feature count

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/logistic_regression_onnx_app.git
   cd logistic_regression_onnx_app
pip install -r requirements.txt
streamlit run app.py
Enter the 4 feature values separated by commas and click Predict to get the prediction.

Requirements
Python 3.7+

streamlit

onnxruntime

numpy

Author
Ahmed Ghoneim
