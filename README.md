NAO Prediction: Machine Learning for the North Atlantic Oscillation


📌 Project Overview
The North Atlantic Oscillation (NAO) is a major climatic phenomenon in the Northern Hemisphere, defined by the pressure difference between the Icelandic Low and the Azores High. It significantly impacts weather patterns across Europe and North America.

This project focuses on predicting the NAO Index using different time-series forecasting techniques, ranging from classical statistical methods to modern Deep Learning architectures.

📂 Project Structure
The repository is organized into the following modules to ensure a clear workflow from data analysis to final presentation:

1_Data_Characteristics/: Exploratory Data Analysis (EDA) and preprocessing.

2_Baseline_Model/: Implementation of the SARIMA statistical baseline.

3_Model/: Development and evaluation of Machine Learning and Deep Learning models.

4_Presentation/: Final project slides and documentation.

📊 Model Summary
We implemented a total of 1+1 Baseline and 1+3 Machine Learning models to evaluate different approaches to time-series forecasting:

SARIMA (Baseline): A Seasonal Autoregressive Integrated Moving Average model used to capture the linear seasonal trends in the NAO index.

Random Forest Regressor: An ensemble learning method used to capture non-linear relationships in the atmospheric data.

LSTM (Long Short-Term Memory): A Recurrent Neural Network (RNN) designed to learn long-term dependencies in sequential climate data.

XGBoost / ConvLSTM: (Note: Update this with your specific 3rd model—common choices for this project are XGBoost for gradient boosting or ConvLSTM for spatial-temporal data).

🚀 Getting Started
Prerequisites
Ensure you have Python 3.10+ installed. You can install the required libraries using:

Bash
pip install -r requirements.txt
Running the Project
Explore the data characteristics in the 1_Data_Characteristics notebook.

Run the baseline model in the 2_Baseline_Model folder.

Compare advanced models in the 3_Model directory.

📽 Presentation
Our final findings and model comparisons are available in the Project Slides.

👥 Contributors
Paula Gößling

Anil Kumar Gadamoni

Murali Udutha
