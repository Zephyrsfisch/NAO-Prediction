# North Atlantic Oscillation (NAO) Prediction

## Repository Link

[https://github.com/Zephyrsfisch/NAO-Prediction]

## Description

The North Atlantic Oscillation (NAO) is a major climatic phenomenon in the Northern Hemisphere, defined by 
the pressure difference between the Icelandic Low and the Azores High. It significantly impacts weather 
patterns across Europe and North America.

### Task Type

Time-Series prediction

### Results Summary - monthly prediction

#### Best Model Performance
- **Best Model:** Random Forest regression model
- **Evaluation Metric:** ACC, (MSE, RMSE)
- **Final Performance:** ACC  : 0.95, (MSE  : 0.08, RMSE : 0.28)

#### Model Comparison
- **Baseline Performance:** ACC = 0.43, (MSE = 0.26, RMSE = 0.51)

- **Improvement Over Baseline:** ACC Improvement  : 118.64%, (MSE Improvement  : 69.32%, RMSE Improvement : 44.61%)

  
#### Key Insights
- **Most Important Features:** lag_1, lag_2, lag_3

### Results Summary - winter only prediction

#### Best Model Performance
- **Best Model:** ARIMAX and Ridge reduced (regularised linear regression)
- **Evaluation Metric:** ACC, MSE, RMSE
- **Final Performance:**
ARIMAX: ACC=0.46, (MSE=0.53, RMSE=0.73)
Ridge reduced: ACC=0.34, (MSE=0.20, RMSE =0.45)

  
#### Model Comparison
No fair comparison, since the baseline model predicts monthly whereas the analyzed model predicts a winter mean. The baseline winter only value is constant over time. In the following we never the less compare to the metrics as defined in the baseline model.
- **Baseline Performance:** ACC = 0.43, (MSE = 0.26, RMSE = 0.51)

- **Improvement Over Baseline:**
ARIMAX: ACC Improvement  : 7%, (MSE Improvement  : -104%, RMSE Improvement : -43)
Ridge reduced: ACC Improvement  : -21%, (MSE Improvement  : 23%, RMSE Improvement : 12%)

  
#### Key Insights
- **Most Important Features:** son_min (September-October minimum NAO index), nao_lowfreq_10yr (10yr rolling mean of NAO index)
- **Model Strengths:** Stability, interpretability, robustness
- **Model Limitations:** cannot capture nonlinear or state-dependent dynamics
- **Business Impact:** low real live application, since prediction is very unsure
  
## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)**
3. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**
4. **[Model Definition and Evaluation](3_Model/model_definition_evaluation)**
5. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Project Cover Image](CoverImage/cloud.jpg)
