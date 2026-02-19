# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** [(https://ftp.cpc.ncep.noaa.gov/cwlinks/norm.daily.nao.cdas.z500.19500101_current.csv)]
- **Dataset Owner/Contact:** [NOAA/National Oceanic and Atmospheric Administration]

### Dataset Characteristics
- **Number of Observations:** [>27700 days from 1950-01-01 to today, daily updated. Resolution is daily. For this project we will take monthly means.]
- **Number of Features:** [month, (season), decade, many more for winter_only prediction, see model file itself for that]
- additional ideas: other climate Indexes as AMV or ENSO, oceanic features as AMOC strength or Sea Surface Temperature.

### Target Variable/Label
- **Label Name:** [nao_index_cdas, 4]
- **Label Type:** [timeseries prediction]
- **Label Description:** [We want to predict the NAO index. The NAO is a pressure pattern in the North Atlantic, giving an idea about for example Europas winter weather tendency. The index is the difference of the sea level pressure in the icelandic low and the acores high.]
- **Label Values:** [Minimum NAO: -1.55, Maximum NAO: 1.71]
- **Label Distribution:** [The index is slighly skewed (-0.057), but nearly normal distributed with μ=0.03 and σ=0.5.]

### Feature Description
- **Feature 1 (decade):** [The decade of the time series. Eg. 1950-1959 is decade labeled 1959.]
- **Feature 2 (season_flag):** [November-April = Winter = 1, Mai-October = Summer 0 -1. Sorted by mean seasonality/climatology in generally positiv or negativ values.]
- **Feature 3 (month, month_sin, month_cos):** [Month of time series, circular]

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
