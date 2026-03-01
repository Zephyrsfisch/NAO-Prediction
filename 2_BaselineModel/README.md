# Baseline Model

**[Notebook](baseline_model.ipynb)**

## Baseline Model Results

### Model Selection
- **Baseline Model Type:** Autoregressive
- **Rationale:** The seasonality is an important and simple feature of the NAO index. An easy (but not so good) prediction would be, to just take that.

### Model Performance
- **Evaluation Metric:** MSE, RMSE, ACC
- **Performance Score:** MSE climatology:  0.28
MSE SARIMA:  0.26
RMSE climatology:  0.53
RMSE SARIMA:  0.51
ACC climatology:  0.38
ACC SARIMA:  0.43

### Evaluation Methodology
- **Data Split:** 80/20
- **Evaluation Metrics:** MSE, RMSE, ACC
- 
### Metric Practical Relevance
MSE: Measures the average squared difference between predicted and actual values. By squaring the unit gets unhandy. Outliers are punished strongly. Good for regression problems for training. It is very broughtly used.

RMSE: Same as MSE but the root of it. By this the unit is the same as the original values. Maybe better for reporting.

ACC: Pearson correlation coefficient between predicted and correct values. By this, the computation of the pattern or the variability is in the focus and not the "raw" numbers. It is used for time series predictions as for example weather predictions and climate modeling.

MSE and RMSE are used since they are very well known, punish outliers while ACC is maybe a more relevant metric. Looking at both/all three gives information about both, the pattern accuracy and the "number" accuracy.

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
