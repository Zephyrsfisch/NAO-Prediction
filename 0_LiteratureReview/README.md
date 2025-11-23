# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: A Review of Predictability Studies of Atlantic Sector Climate on Decadal Time Scales

  - https://oceanrep.geomar.de/id/eprint/6884/1/JCLI3945.pdf

  - **Objective**:
                -To assess how predictable the North Atlantic climate system is, especially the NAO, across multi-year to decadal timescales.

  - **Methods**:
                -Review of observational datasets, reanalysis products, and long-term climate records.

                - Comparison of statistical models and decadal prediction model experiments.

                -Evaluation of forecast skill using hindcasts and perfect-model simulations.

  - **Outcomes**:
                -NAO predictability exists but is limited and strongly influenced by ocean conditions 

                - Models can capture long-term variability but struggle with short-term transitions.

                -Prediction skill varies by season, with winter NAO showing higher potential.

                -Large uncertainties arise from model bias and internal atmospheric variability.

  - **Relation to the Project**: 
                -Helps set realistic expectations for NAO prediction accuracy using machine learnig

                -Identifies important predictors such as SST anomalies and ocean circulation.

                -Highlights challenges like variability and noise, guiding data preprocessing and model design.


- **Source 2**: NAO Seasonal Forecast Using a Multivariate Air–Sea Coupled Deep Learning Model Combined with Causal Discovery. Mu, B., Jiang, X., Yuan, S., Cui, Y. & Qin, B.Atmosphere 14, 792 (2023)

  - **[[Link]](https://doi.org/10.3390/atmos14050792)()**
  - **Objective**: Proposes a data-driven, air–sea coupled deep learning model for NAO forecasting with causal discovery.
  - **Methods**: First the best predictors (-> features) are chosen by applying data-driven causal discovery models. These multivariate spatial–temporal prediction are then put into the NAO-MCD. Here they are first „encoded“ ConvLSTM-based, then „coupled“ with a two-layer GCN and „decoded“ symmetrical to the encoder by transforming convolution layers corresponding to the convolution layers in ConvLSTM. By this Sea Level Pressure is predicted, which is then transferred to NAO index.
  - **Outcomes**: Feature they tested, in brackets those which are not considered since not statistically significant for seasonal prediction: ENSO index, Sea ice extend, 500 hPa geopotential height, 10 m meridional wind, 10 m zonal wind, (Sea surface temperature), Sea surface latent heat flux.
2- to 6-month lead-time NAO forecasts outperform conventional numerical models.
Highly accurate seasonal forecasts of NAO
  - **Relation to the Project**: The presented model predicts the NAO with deep learning techniques as we plan to do though using a more complex model architecture and also spatial.
Maybe additionally a feature capturing the ocean part could improve our model?
Winter NAO prediction is more robust, maybe we should also try that.

- **Source 3**: [Title of Source 3]

  - **[Link]()**
  - **Objective**:
  - **Methods**:
  - **Outcomes**:
  - **Relation to the Project**:
