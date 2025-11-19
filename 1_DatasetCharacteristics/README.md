# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** [(https://ftp.cpc.ncep.noaa.gov/cwlinks/norm.daily.nao.cdas.z500.19500101_current.csv)]
- **Dataset Owner/Contact:** [NOAA/National Oceanic and Atmospheric Administration]

### Dataset Characteristics
- **Number of Observations:** [~27700 days from 1950-01-01 to today, daily updated. Resolution is daily, though we also did rolling means to get a monthly, yearly and centurily resolved dataset.]
- **Number of Features:** [Total number of features in your dataset]

### Target Variable/Label
- **Label Name:** [Name of the target variable/column]
- **Label Type:** [Classification/Regression/Clustering/Other]
- **Label Description:** [We want to predict the NAO index. The NAO is a pressure pattern in the North Atlantic, giving an idea about for example Europas winter weather tendency. The index is the difference of the sea level pressure in the icelandic low and the acores high.]
- **Label Values:** [For classification: list of classes and their meanings. For regression: range of values. For other tasks: describe the label structure]
- **Label Distribution:** [Brief description of class balance for classification or value distribution for regression]

### Feature Description
[Provide a brief description of each feature or group of features in your dataset. If you have many features, group them logically and describe each group. Include information about data types, ranges, and what each feature represents.]

**Example format:**
- **Feature 1 (feature_name):** [Description of what this feature represents, data type, and any relevant details]
- **Feature 2 (feature_name):** [Description of what this feature represents, data type, and any relevant details]
- **Feature Group (group_name):** [Description of a group of related features]

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions
- Missing value analysis
- Feature correlation analysis
- Data visualization and insights
- Data quality assessment
