# README

## Project Title: Data Analysis and Forecasting Project

### Overview

This project focuses on analyzing a dataset to extract meaningful insights through data processing, visualization, and predictive modeling. It also evaluates different forecasting models and explores environmental factors affecting air pollution levels.

### Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Model implementation: ARIMA, XGBoost, LSTM
- Model evaluation using MAE and RMSE
- Environmental factor analysis

### Dataset

The dataset includes various air pollutant measurements and meteorological factors. The primary focus is on analyzing relationships between pollutants and external conditions like temperature, humidity, wind speed, and precipitation.

### Model Performance

| Model   | MAE    | RMSE   |
| ------- | ------ | ------ |
| ARIMA   | 0.1107 | 0.1550 |
| XGBoost | 0.1307 | 0.1474 |
| LSTM    | 0.0488 | 0.0640 |

LSTM outperformed the other models, showing the lowest error rates.

### Environmental Analysis Highlights

- **Strong correlations among CO, NO₂, SO₂, and PM2.5** suggest common sources like vehicle emissions.
- **Temperature increases ozone levels** but reduces NO₂ concentration.
- **Humidity reduces ozone levels** but has a limited effect on PM2.5.
- **Wind disperses pollution, but low-wind conditions cause accumulation.**
- **Rain helps clear PM2.5 particles, improving air quality.**

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or script to process and analyze the data.

### Usage

- Execute the scripts to preprocess the dataset and perform analysis.
- Visualize the results using matplotlib and seaborn.
- Compare the forecasting model performances and extract key insights.

### Recommendations

1. Implement ozone warnings during heatwaves.
2. Leverage rainfall forecasting for natural pollution reduction.
3. Design urban areas with wind circulation strategies.
4. Further tune ARIMA and XGBoost for better forecasting accuracy.

### Contributors

- Yun Zhu

### License

This project is licensed under the MIT License.
