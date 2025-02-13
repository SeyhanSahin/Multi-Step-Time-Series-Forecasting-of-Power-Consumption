<h1 align="center"><strong>Multi-Step Time Series Forecasting of Power Consumption</strong></h1>
<h2 align="center"><strong>Evaluation of Various Models Including CNN, LSTM, CNN-LSTM, and Multiple Linear Regression</strong></h2>

**Objectives of the project:**

This project has two specific aims:

    • Predicting weekly energy usage for individual household unit by analyzing its historical consumption levels,
    
    • Evaluating the strengths and weaknesses of various modeling approaches for time series forecasting.
    
On a broader scale, the objective includes optimizing energy forecasting to balance supply and demand effectively.

### **PROJECT WORKFLOW**
    1. Import the necessary libraries
    2. Import and explore the dataset
    • df.shape, df.head(), df.tail(), df.info()
    3. Data Pre-processing and Exploratory Data Analysis (EDA)
    • 3.1 Feature engineering (combining the date and time columns)
    • 3.2 Data type conversion (converting all the features to float64 data type)
    • 3.3 Handle missing values
    • 3.4 Problem framing (Downsample the dataset on daily basis)
    • 3.5 Handle duplicated values
    • 3.6 Outliers Detection
    4. Train-Test split (to avoid data leakage)
    5. Scale the data (MinMax Scaling)
    6. Convert the data into a supervised regression problem
    7. Build models using Deep Learning Architectures (CNN, LSTM, CNN-LSTM), make predictions, and perform evaluations on them
    • 7.1 CNN Models
    • 7.2 LSTM Models
    • 7.3 CNN-LSTM Models
    8. Build a model using Multiple Linear Regression (MLR), make predictions, and perform evaluations on it
    9. Best Performance Metrics of Four Models at Project Conclusion
    10. Future Work
