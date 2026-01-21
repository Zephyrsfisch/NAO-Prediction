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
- **Cross-Validation Score:** [Mean and standard deviation of CV scores, e.g., 0.82 ± 0.03]

### Evaluation Methodology
- **Data Split:** 80/20
- **Evaluation Metrics:** MSE, RMSE, ACC
- 
### Metric Practical Relevance
[Explain the practical relevance and business impact of each chosen evaluation metric. How do these metrics translate to real-world performance and decision-making? What do the metric values mean in the context of your specific problem domain?]

## Next Steps
This baseline model serves as a reference point for evaluating more sophisticated models in the [Model Definition and Evaluation](../3_Model/README.md) phase.
